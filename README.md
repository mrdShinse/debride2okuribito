# DebrideToOkuribito

https://rubygems.org/gems/debride2okuribito

DebrideToOkuribito converts the execution result of "Debride" to yaml for "Okuribito".

## Description citation

### What is Debride

> Analyze code for potentially uncalled / dead methods, now with auto-removal.

Please, refer to the github repository for details: https://github.com/seattlerb/debride

### What is Okuribito

> Okuribito monitors the method call with YAML, and exec specified code.
>
> In other words, it can be used in order to extract the really uncalled method.

Please, refer to the github repository for details: https://github.com/muramurasan/okuribito

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'debride2okuribito'
```

And then execute:

```
$ bundle
```

Or install it yourself as:

```
$ gem install debride2okuribito
```

## Usage

Usage is very easy.

If you enter the following command, you can get yaml for "Okuribito" with potentially uncalled methods written.

```
$ debride2okuribito ./
--- Run debride...
--- Convert yaml...
--- 'okuribito.yml' has been generated.
```

The available options are "Debride" compliant.

```
$ debride2okuribito --rails app
--- Run debride...
--- Convert yaml...
--- 'okuribito.yml' has been generated.
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
Copyright 2016 Yasuhiro Matsumura.
