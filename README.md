# Number.isInteger <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Number.isInteger` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@npmtuanmap/ut-quas-amet-possimus).

## Getting started

```sh
npm install --save @npmtuanmap/ut-quas-amet-possimus
```

## Usage/Examples

```js
console.log(Number.isInteger(-3)); // true
console.log(Number.isInteger(2 ** 54)); // true
console.log(Number.isInteger(2.3)); // false
console.log(Number.isInteger(Infinity)); // false
console.log(Number.isInteger("7")); // false
```

## Tests

Clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@npmtuanmap/ut-quas-amet-possimus
[npm-version-svg]: https://versionbadg.es/npmtuanmap/ut-quas-amet-possimus.svg
[deps-svg]: https://david-dm.org/npmtuanmap/ut-quas-amet-possimus.svg
[deps-url]: https://david-dm.org/npmtuanmap/ut-quas-amet-possimus
[dev-deps-svg]: https://david-dm.org/npmtuanmap/ut-quas-amet-possimus/dev-status.svg
[dev-deps-url]: https://david-dm.org/npmtuanmap/ut-quas-amet-possimus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@npmtuanmap/ut-quas-amet-possimus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@npmtuanmap/ut-quas-amet-possimus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@npmtuanmap/ut-quas-amet-possimus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@npmtuanmap/ut-quas-amet-possimus
[codecov-image]: https://codecov.io/gh/npmtuanmap/ut-quas-amet-possimus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/npmtuanmap/ut-quas-amet-possimus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/npmtuanmap/ut-quas-amet-possimus
[actions-url]: https://github.com/npmtuanmap/ut-quas-amet-possimus/actions
