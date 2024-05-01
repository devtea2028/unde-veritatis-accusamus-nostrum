# @devtea2028/unde-veritatis-accusamus-nostrum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const humanFileSize = require('@devtea2028/unde-veritatis-accusamus-nostrum');

console.log(humanFileSize(67229)); //67.2 KB
console.log(humanFileSize(67229, true, 2)); //67.23 KB
console.log(humanFileSize(67229, false)); //65.7 KiB
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2028/unde-veritatis-accusamus-nostrum
[npm-version-svg]: https://versionbadg.es/devtea2028/unde-veritatis-accusamus-nostrum.svg
[npm-badge-png]: https://nodei.co/npm/@devtea2028/unde-veritatis-accusamus-nostrum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2028/unde-veritatis-accusamus-nostrum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2028/unde-veritatis-accusamus-nostrum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2028/unde-veritatis-accusamus-nostrum