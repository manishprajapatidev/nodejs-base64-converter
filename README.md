# base64 encode/decode methods in nodejs
[![npm version](https://badge.fury.io/js/nodejs-base64-converter.svg)](https://badge.fury.io/js/nodejs-base64-converter)
The ultimate small js library for the base64 encode/decode conversion in Node.js.

## Usage ##

```js
var nodeBase64 = require('nodejs-base64-converter');

console.log(nodeBase64.encode("test text")); //dGVzdCB0ZXh0
console.log(nodeBase64.decode("dGVzdCB0ZXh0")); //test text
```

## Installation ##

Install from command line:

```
npm i --save nodejs-base64-converter
```

## Test ##
```
npm test
```