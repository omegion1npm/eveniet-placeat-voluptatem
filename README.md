# @omegion1npm/eveniet-placeat-voluptatem <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @omegion1npm/eveniet-placeat-voluptatem
```

## Usage/Examples

```js
var regexTester = require('@omegion1npm/eveniet-placeat-voluptatem');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@omegion1npm/eveniet-placeat-voluptatem
[npm-version-svg]: https://versionbadg.es/ljharb/@omegion1npm/eveniet-placeat-voluptatem.svg
[deps-svg]: https://david-dm.org/ljharb/@omegion1npm/eveniet-placeat-voluptatem.svg
[deps-url]: https://david-dm.org/ljharb/@omegion1npm/eveniet-placeat-voluptatem
[dev-deps-svg]: https://david-dm.org/ljharb/@omegion1npm/eveniet-placeat-voluptatem/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@omegion1npm/eveniet-placeat-voluptatem#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/eveniet-placeat-voluptatem.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/eveniet-placeat-voluptatem.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/eveniet-placeat-voluptatem.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/eveniet-placeat-voluptatem
[codecov-image]: https://codecov.io/gh/ljharb/@omegion1npm/eveniet-placeat-voluptatem/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@omegion1npm/eveniet-placeat-voluptatem/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@omegion1npm/eveniet-placeat-voluptatem
[actions-url]: https://github.com/omegion1npm/eveniet-placeat-voluptatem/actions
