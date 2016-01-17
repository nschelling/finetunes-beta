#Superbright MOBILE FIRST DEV STACK

## PROJECT COMPONENTS

    NODE.JS with http://expressjs.com/ 
    NUNJUCKS templating system https://mozilla.github.io/nunjucks/
    SKEL.IO for responsive skeleton https://github.com/n33/skel
    SASS is the main css generator, and kicks ass

## APPROACH

    This stack is used for quick deployment and prototyping. Does not have testing, which I think is too project dependent to be included in a skeleton.

    Does not include REACT or ANGULAR or any large scale front end platforms either, because they are necessary either. And should be used with enough architecture considerations in larger projects.

    Does not include any DB, uses a export JSON data for any quick DB testing.

## Templates (NunJucks)
    Each template can use a master template system by extending the layout.nunjucks template {% extends "layout.nunjucks" %}

    layout.nunjucks incorporates a banner tamplate for the header from macros for a consistent, responsive navigation.
    Footer is embedded in the layout.nunjucks, but can be separated to another partial or macro.

## INSTALL && KICK OFF

NPM INSTALL to install packages <br>
NPM START to start on localhost:3000


## TODO
    Need to finish the gulp.js and integrate it to NPM
    Currently Gulp contains a script to separately compile NunJucks, like to add Sass and a good listening system for updating the browers
