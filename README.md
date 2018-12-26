# @mlyncheski/hg-one

[![npm (scoped)](https://img.shields.io/npm/v/@mlyncheski/tiny.svg)](https://www.npmjs.com/package/@mlyncheski/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mlyncheski/tiny.svg)](https://www.npmjs.com/package/@mlyncheski/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @mlyncheski/tiny
```

## Usage

```js
const tiny = require("@mlyncheski/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```