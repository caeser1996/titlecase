# @caeser1996/titlecase

[![npm (scoped)](https://img.shields.io/npm/v/@caeser1996/titlecase.svg)](https://www.npmjs.com/package/@caeser1996/titlecase)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@caeser1996/titlecase.svg)](https://www.npmjs.com/package/@caeser1996/titlecase)

Make your string Title case.

## Install

```
$ npm install @caeser1996/titlecase
```

## Usage

```js
const tiny = require("@caeser1996/titlecase");

to_title("so much space!");
//=> "So Much Space!"

to_title(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
