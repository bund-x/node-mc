# node-mc

[![NPM version][npm-image]][npm-url]
[![Build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![Dependency Status][david-image]][david-url]
[![License][license-image]][license-url]

Midnight Commander written in React/Node stack.

![](https://raw.githubusercontent.com/azproduction/talk-back-to-text-ui/master/pictures/node-mc.png)

[How it works](https://www.youtube.com/watch?v=ee_U2t-8L48)

## Installing

 - `npm i node-mc` or global `npm i node-mc -g`
 - Install `PhantomJS 2.0` – `brew install phantomjs` or `sudo apt-get install phantomjs`.

## Running

`nmc` or `npm start`

Currently it has font rendering issues due to PhantomJS, in order to have
full experience, please run `nmc` in development mode (see below).

## Running in development mode

```
git clone git://github.com/azproduction/node-mc.git
cd node-mc
npm install
npm run debug
```

[npm-image]: https://img.shields.io/npm/v/node-mc.svg?style=flat-square
[npm-url]: https://npmjs.org/package/node-mc
[github-tag]: http://img.shields.io/github/tag/azproduction/node-mc.svg?style=flat-square
[github-url]: https://github.com/azproduction/node-mc/tags
[travis-image]: https://img.shields.io/travis/azproduction/node-mc.svg?style=flat-square
[travis-url]: https://travis-ci.org/azproduction/node-mc
[coveralls-image]: https://img.shields.io/coveralls/azproduction/node-mc.svg?style=flat-square
[coveralls-url]: https://coveralls.io/r/azproduction/node-mc
[david-image]: http://img.shields.io/david/azproduction/node-mc.svg?style=flat-square
[david-url]: https://david-dm.org/azproduction/node-mc
[license-image]: http://img.shields.io/npm/l/node-mc.svg?style=flat-square
[license-url]: LICENSE
