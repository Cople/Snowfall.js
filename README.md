Snowfall.js
===========

Let It Snow... on any page with CSS3 transforms and transitions in modern browsers.

## Example ##
[Demo](https://github.com/Cople/Snowfall.js)

## Usage ##

```html
<link rel="stylesheet" href="snowfall.css" />
<script src="snowfall.js"></script>
```

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
snow.config({});
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