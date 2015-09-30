# Brunch With Bower , Bootstrap Sass And jQuery

[![project status](http://stillmaintained.com/hyyan/brunch-with-hyyan.png)](http://stillmaintained.com/hyyan/brunch-with-hyyan)
[![dependency Status](https://david-dm.org/hyyan/brunch-with-hyyan/status.svg)](https://david-dm.org/hyyan/brunch-with-hyyan#info=dependencies)

HTML5 application, built with [Brunch](http://brunch.io), Bootstrap Sass And jQuery

## Getting started
* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * [Bower](http://bower.io): `npm install -g bower`
    * Brunch plugins and Bower dependencies: `npm install`.
* Run:
    * `npm start`             — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
    * `brunch watch --server` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
    * `brunch build --production` — builds minified project for production
* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * Place styles in `app/scss/` to be compiled to `public/css/app.css`
    * Place javascripts in `app/scripts` to be concatenated to `public/js/app.js`
    * Static site support by [this Brunch plugin.](https://github.com/devinus/static-site-brunch)Add Handlebars templates to app/templates and they will be automatically compiled and placed in your `public/` directory.
    * [Brunch site](http://brunch.io)
    * [Sass site](http://sass-lang.com)
    * [Bootstrap site](http://getbootstrap.com)

