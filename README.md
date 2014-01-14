##  Starter.ghost
Twitter Bootstrap 3 theme for Ghost.js.
Written as starter template for future themes. For example, I made [Supernova][3] starting with this theme.

![Starter.ghost][1]

### Features

 - Twitter Bootstrap 3, normalize.css, Font Awesome
 - SCSS with [lib-sass][2] (written on C)
 - Grunt.js, Bower
 
### Install and use
 - Clone this repository to `/content/themes`
 - In Ghost's settings change "Theme" preference
 - Go to ``/content/themes/Starter.ghost``, make ``npm install && bower install``
 - Run ``grunt serve`` (for live compiling ``.scss`` files and concat ``.js`` files) or ``grunt`` for build
 
### Roadmap
 - Clean theme
 - Add livereload
 - Accept pull requests

  [1]: http://gm4.in/i/fgl.png
  [2]: http://libsass.org/
  [3]: https://github.com/theaqua/Supernova.ghost