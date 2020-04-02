# @willyan-fidelis/first-package

[![npm (scoped)](https://img.shields.io/npm/v/@willyan-fidelis/first-package.svg)](https://www.npmjs.com/package/@willyan-fidelis/first-package)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@willyan-fidelis/first-package.svg)](https://www.npmjs.com/package/@willyan-fidelis/first-package)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@willyan-fidelis/first-package");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1