# @caeser1996/haversine

[![npm (scoped)](https://img.shields.io/npm/v/@caeser1996/haversine.svg)](https://www.npmjs.com/package/@caeser1996/haversine)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@caeser1996/haversine.svg)](https://www.npmjs.com/package/@caeser1996/haversine)

Calculate distance between Two Coordinates using haversine.

## Install

```
$ npm install @caeser1996/haversine
```

## Usage

```js
const haversine = require("@caeser1996/haversine");


let coords1=[24.20,32.20] //[long,lat]
let coords2 =[32.20,45.20]//[long,lat]


haversineDistance(coords1,coords2,false);//false if you want it in kms

1601.612304937011

```
