# MagicSuggest Gem for Rails

[MagicSuggest](http://nicolasbize.com/magicsuggest/index.html) for the Rails asset pipeline.

## Installation


Add this line to your application's Gemfile:

    gem 'magic_suggest'


And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install magic_suggest

Add this line to your application.js file

    //= require magicsuggest
    or
    //= require magicsuggest.min

Add this line to your application.css file

    *= require magicsuggest
    or
    *= require magicsuggest.min

## Usage

Given an input field, add a class of your choice to it.

    <div id="magicsuggest"></div>

Then tokenize the input field as follows.

    $(function() {
      $('#magicsuggest').magicSuggest({
        [...] // configuration options
      });
    });

Check out the [demo and docs](http://nicolasbize.com/magicsuggest/index.html).

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Changelog

<ul>
  <li>Released gem v.0.0.1</li>
</ul>

## Contributors

[Viktor Oleksyn](https://github.com/bartezic)

### License

Available under the MIT License.
