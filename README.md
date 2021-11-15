# @stenito/tiny

![npm (scoped)](https://img.shields.io/npm/v/@stenito/tiny)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@stenito/tiny)

Removes all spaces from a string.

## Install

``` commandline
npm install @stenito/tiny
```

## Usage

``` javascript
const tiny = require("@stenito/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
