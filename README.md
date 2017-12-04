Node-english-regular-verbs
=========================

[![NPM Version][npm-version-image]][npm-url]
[![NPM Downloads][npm-downloads-image]][npm-url]
[![Node.js Version][node-image]][node-url]

## Description

node-english-regular-verbs Is a very extensive list of english regular verbs.

## Installation

```bash
npm install node-english-regular-verbs
```

## Usage

```js
var regularVerbs = require('node-english-regular-verbs');

for (let i = 0; i < regularVerbs.verbs.length; i++) {
  if (regularVerbs.verbs[i] == "zoom") {
    console.log("is verb!");
  }
}
```

```
https://cdn.rawgit.com/Franceskynov/node-english-regular-verbs/master/dist/list.json
```

## License

(MIT License)

Copyright 2017,  franceskynov

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[npm-version-image]: https://img.shields.io/npm/v/node-english-regular-verbs.svg
[npm-downloads-image]: https://img.shields.io/npm/dm/node-english-regular-verbs.svg
[npm-url]: https://npmjs.org/package/node-english-regular-verbs
[node-image]: https://img.shields.io/node/v/node-english-regular-verbs.svg
[node-url]: http://nodejs.org/download/