# @erboladaiorg/quod-nesciunt-cum <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @erboladaiorg/quod-nesciunt-cum
```

## Usage/Examples

```js
var regexTester = require('@erboladaiorg/quod-nesciunt-cum');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@erboladaiorg/quod-nesciunt-cum
[npm-version-svg]: https://versionbadg.es/ljharb/@erboladaiorg/quod-nesciunt-cum.svg
[deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/quod-nesciunt-cum.svg
[deps-url]: https://david-dm.org/ljharb/@erboladaiorg/quod-nesciunt-cum
[dev-deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/quod-nesciunt-cum/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@erboladaiorg/quod-nesciunt-cum#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/quod-nesciunt-cum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/quod-nesciunt-cum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/quod-nesciunt-cum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/quod-nesciunt-cum
[codecov-image]: https://codecov.io/gh/ljharb/@erboladaiorg/quod-nesciunt-cum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@erboladaiorg/quod-nesciunt-cum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@erboladaiorg/quod-nesciunt-cum
[actions-url]: https://github.com/erboladaiorg/quod-nesciunt-cum/actions
