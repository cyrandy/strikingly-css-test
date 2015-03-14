Strikingly HTML/CSS Test
=============

Use [Jade](http://jade-lang.com)/[Sass](http://sass-lang.com)/[Coffee](http://coffeescript.org) which will compile into html/css/js files.
Use gulp to watch, compile files, and also support livereload.

## Setup Environment

1. install Node.js (recommend using [nodebrew](https://github.com/hokaccha/nodebrew) to install Node.js for node version control)

2. install bundler `gem install bundler` (optional: set up `rbenv` or `rvm` first. Make sure gem run under folder in your home directory to prevent permission problem.)

3. `git@github.com:cyrandy/strikingly-css-test.git` and `cd strikingly-css-test`

4. `npm install` and `bundle install`

5. run `./node_modules/gulp/bin/gulp.js start` will auto build files and then open the result in your browser.
