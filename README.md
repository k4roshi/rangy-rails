# rangy-rails

A simple Rails asset pipeline wrapper
for [Rangy](https://code.google.com/p/rangy/), "a cross-browser JavaScript range and
selection library" written by the magnificent [Tim Down](http://www.timdown.co.uk/).

The `rangy-rails` gem includes Rangy core and all of it's modules.  The `rangy-rails` version
will be kept in sync with Rangy's version as this gem really adds nothing but a convenient
way of getting Rangy into your Rails app.

## Installation

Add this line to your application's Gemfile:

    gem 'rangy-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rangy-rails

## Usage

Easy! Just edit `app/assets/javascripts/application.js` and adjust it to your heart's delight.

Here's an example configuration that would include Rangy and all of it's modules:

    //= require rangy-core
    //= require rangy-cssclassapplier
    //= require rangy-highlighter
    //= require rangy-selectionsaverestore
    //= require rangy-serializer
    //= require rangy-textrange

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request