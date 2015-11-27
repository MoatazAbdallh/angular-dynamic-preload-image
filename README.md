# angular-dynamic-preload-image
A simple AngularJS module to make it easy to pre-load images with dynamic attr interpolation.

#Installation

##Install with bower

```
bower install angular-dynamic-preload-image
```

##Include script files

```html
<script src="bower_components/angular/angular.min.js"></script>
<script src="bower_components/angular-preload-image/angular-dynamic-preload-image.min.js"></script>
```

##Add module dependency

```javascript
angular.module('app', ['angular-dynamic-preload-image']);
```

#Usage

##Pre-load background images with interpolation attr

```html
<div preload-bg-image="{{imgSrc}}" default-image="[URL]" fallback-image="[URL]"></div>
```

##Pre-load standard images

```html
<img preload-image ng-src="{{imgSrc}}" default-image="[URL]" fallback-image="[URL]" />
```

#Licence

MIT

#Demo

Check out the [demo](http://revillweb.github.io/angular-preload-image/) for an example of pre-loading background images and pre-loading standard images with AngularJS.

#Build
```javascript
npm install 
```
```javascript
gulp serve
```
the minified gulp file will be under dist folder
 
#Credit
Editing project forked from [Repo](https://github.com/RevillWeb/angular-preload-image)

Inspiration taken from Ben Nadel's [post](http://www.bennadel.com/blog/2597-preloading-images-in-angularjs-with-promises.htm) about pre-loading images.

