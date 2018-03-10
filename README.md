# undeclared-identifiers

find undeclared identifiers and property accesses in a javascript file.

[![npm][npm-image]][npm-url]
[![travis][travis-image]][travis-url]
[![standard][standard-image]][standard-url]

[npm-image]: https://img.shields.io/npm/v/undeclared-identifiers.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/undeclared-identifiers
[travis-image]: https://img.shields.io/travis/goto-bus-stop/undeclared-identifiers.svg?style=flat-square
[travis-url]: https://travis-ci.org/goto-bus-stop/undeclared-identifiers
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[standard-url]: http://npm.im/standard

## Install

```
npm install undeclared-identifiers
```

## Usage

```js
var undeclaredIdentifiers = require('undeclared-identifiers')

undeclaredIdentifiers(src)
// { identifiers: ['Buffer'],
//   properties: ['Buffer.isBuffer'] }
```

## License

[Apache-2.0](LICENSE.md)
