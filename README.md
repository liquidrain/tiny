# @liquidrain/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@liquidrain/tiny.svg)](https://www.npmjs.com/package/@liquidrain/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @liquidrain/tiny
```

## Usage

```js
const tiny = require("@liquidrain/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```