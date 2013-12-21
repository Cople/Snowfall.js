Snowfall.js
===========

Let It Snow... on any page with CSS3 transforms and transitions in modern browsers.

## Demo ##
http://cople.github.io/Snowfall.js/

## Usage ##
```javascript
var snow = new Snowfall();
```
or
```javascript
var snow = new Snowfall({
    type: "image",
    conetnt: ["img/flake1.png", "img/flake2.png"],
    maxSize: 40
});
```

## Functions ##
```javascript
snow.config({/* options */});
snow.play();
snow.stop();
```

## Options ##
```javascript
var defaultOptions = {
    minSize: 10,
    maxSize: 30,
    type: "text",
    content: "&#10052",
    fadeOut: true,
    autoplay: true,
    interval: 200
};
```