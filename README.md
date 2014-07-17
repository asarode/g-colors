g-colors
========

Here's a [list of all the Google material design colors.](http://www.google.com/design/spec/style/color.html) You can download the g-colors partial to use them without having to copy + paste from the site all the time! There's a bunch of them, so you should be able to create a nice palette with them.


##Usage
Download g-colors and import the _g-colors.scss partial into your styles.scss manifest file. If you're unfamiliar with Sass partials, you can read more about them on the [Sass guide.](http://sass-lang.com/guide) Make sure to import the g-colors partial towards the beginning of the file so the rest of your SCSS files can use the variables. Then it's as simple as using a variable for any google material color you want.

##Example
- `@import _g-colors.scss`
- Red 500 can be used with the variable `$red-500` 
- Deep Purple A400 with `$deep_purple-A400`

