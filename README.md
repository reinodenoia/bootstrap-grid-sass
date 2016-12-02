# bootstrap-grid-sass
[![Bower version](https://badge.fury.io/bo/bootstrap-grid-sass.svg)](https://badge.fury.io/bo/bootstrap-grid-sass)


Bootstrap's grid and responsive classes. Works with Sass

## Included
- Standard [Bootstrap grid classes](http://getbootstrap.com/css/#grid): .row, columns (.col-xs-\*, .col-md-\* ...), offsets (.col-xs-offset-\* ...), etc
- Standard [Bootstrap responsive utility classes](http://getbootstrap.com/css/#responsive-utilities): .visible-\*, .hidden-\*, etc
- [Helper classes] (http://getbootstrap.com/css/#helper-classes-clearfix): .clearfix, .center-block, etc

## Installation

Please see the appropriate guide for your environment of choice:
* [Manually](#a-manually)
* [Bower](#b-bower)

### a. Manually
You can use it in two different ways:
- You can include the precompiled file `boostrap-grid-sass.css` in your site.
- You can customize and compile the sass files. More information about Sass [here](http://sass-lang.com/guide).
  1. Copy the repository in your assets/css folder. 
  2. Include the main file in your application.css.scss    
       
```css
@import bootstrap-grid-sass
```
##### Example to compile the main file with Sass
```console
sass --watch bootstrap-grid-sass.scss:bootstrap-grid-sass.css
```

### b. Bower
You can install bootstrap-grid-only-sass Bower package with: 
```console
$ bower install bootstrap-grid-only-sass
```

By default, `bower.json` main field list only the main `bootstrap-grid-sass.scss`
