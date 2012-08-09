# Pictos icons


## Install via Rails asset pipeline 

Simply require the css (or scss) stylesheet in your stylesheet manifest, fx `app/assets/stylesheets/application.css`

```css
/*
 *= require pictos
*/
```

## Usage

Use like this:

```html
<ul class='pictos'>
  <li class='pic action'></li>
</ul>
```

Or in HAML

```haml
%ul.pictos
  %li.pic.action
```

You don't have to use an unordered list with list items, but it gives a nice result. You simply have to ensure that you are using block elements that can take a background image ;).

See the *world-flags* gem for more info, tips etc. Also includes some nice sprite utils for generating sprite sets of different sizes :)

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

