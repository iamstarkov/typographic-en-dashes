# typographic-en-dashes

[![NPM version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Coveralls Status][coveralls-image]][coveralls-url]
[![Dependency Status][depstat-image]][depstat-url]
[![DevDependency Status][depstat-dev-image]][depstat-dev-url]

> [Use them, don’t confuse them][rtfm]

Micro module to help eliminate one of the [bad typewriter habits][habits]. Safely replacing hyphens in a range of values with en dashes only.


## Install

```sh
npm install --save typographic-en-dashes
```


## Usage

```js
var endashes = require('typographic-en-dashes');

endashes(`Kurt Cobain (1967-1994)`); // Kurt Cobain (1967–1994)
```

## License

MIT © [Vladimir Starkov](https://iamstarkov.com/)

[rtfm]: http://practicaltypography.com/hyphens-and-dashes.html
[habits]: http://practicaltypography.com/typewriter-habits.html

[npm-url]: https://npmjs.org/package/typographic-en-dashes
[npm-image]: http://img.shields.io/npm/v/typographic-en-dashes.svg

[travis-url]: https://travis-ci.org/iamstarkov/typographic-en-dashes
[travis-image]: http://img.shields.io/travis/iamstarkov/typographic-en-dashes.svg

[coveralls-url]: https://coveralls.io/r/iamstarkov/typographic-en-dashes
[coveralls-image]: http://img.shields.io/coveralls/iamstarkov/typographic-en-dashes.svg

[depstat-url]: https://david-dm.org/iamstarkov/typographic-en-dashes
[depstat-image]: https://david-dm.org/iamstarkov/typographic-en-dashes.svg

[depstat-dev-url]: https://david-dm.org/iamstarkov/typographic-en-dashes
[depstat-dev-image]: https://david-dm.org/iamstarkov/typographic-en-dashes/dev-status.svg
