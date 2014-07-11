# Uikit::Sass:Rails

[![Gem Version](https://badge.fury.io/rb/uikit-sass-rails.png)](http://badge.fury.io/rb/uikit-sass-rails)

Uikit::Sass:Rails is a gem to make it super easy to use UIkit in your Rails project. You can start using Uikit::Sass:Rails in your projects by following the instructions below.

## Installation

In Bundler:
```ruby
gem "uikit-sass-rails"
```

And then execute:
```bash
$ bundle
```

Or install it yourself as::
```bash
$ [sudo|rvm] gem install uikit-sass-rails
```

### Add UIkit to your CSS

Append the following line to your `app/assets/stylesheets/application.css` file:
```css
/*= require uikit */
```

If you're planning on using Sass, then you'll want to rename `application.css` to `application.scss`. That file should then look like:
```css
@import "uikit";
```

### Add UIkit to your JS

Append the following line to your `app/assets/javascripts/application.js` file:
```javascript
//= require uikit
```

## Components
* [UIkit](http://www.getuikit.com) is created by [YOOtheme](http://www.yootheme.com) and licensed under the [MIT license](http://opensource.org/licenses/MIT).
* The [Font Awesome](http://fontawesome.io) font, which is used by UIkit, is created by [Dave Gandy](https://github.com/davegandy) and licensed under the [SIL OFL 1.1](http://scripts.sil.org/OFL).


## Copyright and license
Copyright 2014 [Christian Worreschk](https://github.com/cworreschk), MarSec under the [European Union Public Licence V. 1.1](http://opensource.org/licenses/EUPL-1.1).

## Contributing
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
