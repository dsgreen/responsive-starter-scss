responsive-starter-scss
=======================
Responsive HTML, CSS and SCSS starter templates

##What is this?
This includes basic HTML, CSS and corresponding SCSS to use as a starting point for a project. This updates the earlier
[responsive-starter](https://github.com/dsgreen/responsive-starter) project with SCSS source to modernize it a bit, and make updates easier.

Why would you use this when other frameworks are available? This is designed to provide a light footprint, and excludes unnecessary components.
It is a starting point for your own custom styles, and not a framework that does everything or makes a lot of assumptions. It was created as an
update to an internal framework used on custom projects, and because the author was tired of constantly overriding the default styling used in
larger frameworks.

In some cases, the class names are designed to be similar or the same as other larger frameworks so that moving between frameworks is less of a
hassle. The SCSS source is provided, as well as plain CSS and a compressed version of the CSS.

Included is the [normalize.css](https://github.com/necolas/normalize.css) library, basic typography and styles, and a responsive grid. Column
classes accommodate different coding styles. For example, a seven column span could be defined with the class ".seven" (similar to Foundation 3
naming conventions), or ".col-7" (similar to Bootstrap 3 naming conventions). Additional classes are available for ".half," ".one-quarter,"
".two-thirds," etc.

##Browser/Platform Support
- Firefox
- Chrome
- Safari
- Internet Explorer 9-11
- Internet Explorer 8
    - mostly supported - certain CSS selectors are not supported, but classes can be added for full support
- Android
- iOS

View the demo for more information.