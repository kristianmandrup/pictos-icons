# Pictos icons

Pictos icons for the Rails asset pipeline. Extracted from Sencha Touch GNU license framework. The sprite icons come in the following sizes:

* 15 px
* 30 px
* 60 px

## Install via Rails asset pipeline 

Simply require the css (or scss) stylesheet in your stylesheet manifest, fx `app/assets/stylesheets/application.css`

```css
/*
 *= require pictos
 *= require pictos-15
 *= require pictos-30
 *= require pictos-60
*/
```

## Usage

Use like this:

```html
<ul class='p30.pictos'>
  <li class='pic action'></li>
</ul>

<ul class='p15.pictos'>
  <li class='pic search'></li>
</ul>

```

Or in HAML

```haml
%ul.p60.pictos
  %li.pic.action
  %li.pic.search
```

You don't have to use an unordered list with list items, but it gives a nice result. You simply have to ensure that you are using block elements that can take a background image ;).

See the *world-flags* gem for more info, tips etc. 

## Auto Resize

This gem also includes a sprite utility: `lib/tools/resize_css.rb` for generating sprite sets of different sizes :)

Usage example

```text
$ cd lib/pictos-icons/tools/
$ edit resize_css.rb # change the run arguments at the bottom!
$ ruby resize_css.rb
```

TODO: Make resize tool into a rake task or similar which can take arguments!

## Contributing to pictos-icons
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (c) 2012 Kristian Mandrup. See LICENSE.txt for
further details. (Icons extracted from Sencha Touch 2 GNU version)

