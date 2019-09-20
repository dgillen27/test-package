# @dgillen/test-package

[![npm (scoped)](https://img.shields.io/npm/v/@dgillen27/test-package.svg)](https://github.com/dgillen27/test-package)

My First Package!

Removes all spaces from a string.

## Install

```
$ npm install @dgillen27/test-package
```

## Usage

```js
const testFunction = require("@dgillen27/test-package");

testFunction(1, 5);
//=> 6

testFunction("name");
//=> Uncaught TypeError: testFunction wants a number!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
