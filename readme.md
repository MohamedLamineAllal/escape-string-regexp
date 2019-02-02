# escape-string-regexp [![Build Status](https://travis-ci.org/sindresorhus/escape-string-regexp.svg?branch=master)](https://travis-ci.org/sindresorhus/escape-string-regexp)

This is a fork to https://travis-ci.org/sindresorhus/escape-string-regexp

it add slash escape (which wiredly wasn't handled by the original package)

(a pull request would be sent. And waiting for update ! _this is temporal_ [but it will still here. You can use it safely])

> Escape RegExp special characters

## Install

```
$ npm install --save escape-string-regexp
```

## Usage

```js
const escapeStringRegexp = require("escape-string-regexp");

const escapedString = escapeStringRegexp("// how much $ for a unicorn?");
//=> '\/\/ how much \$ for a unicorn\?'

new RegExp(escapedString);
```

## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
