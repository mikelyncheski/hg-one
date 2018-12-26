# @mlyncheski/hg-one

[![npm (scoped)](https://img.shields.io/npm/v/@mlyncheski/hg-one.svg)](https://www.npmjs.com/package/@mlyncheski/hg-one)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mlyncheski/hg-one.svg)](https://www.npmjs.com/package/@mlyncheski/hg-one)

Removes all spaces from a string.

## Install

```
$ npm install @mlyncheski/hg-one
```

## Usage

```js
const hg-one = require("@mlyncheski/hg-one");

hg-one("So much space!");
//=> "Somuchspace!"

hg-one(1337);
//=> Uncaught TypeError: hg-one wants a string!
//    at hg-one (<anonymous>:2:41)
//    at <anonymous>:1:1
```