# nerf-dart

[![Build Status](https://travis-ci.org/boennemann/nerf-dart.svg?branch=master)](https://travis-ci.org/boennemann/nerf-dart)
[![Coverage Status](https://coveralls.io/repos/boennemann/nerf-dart/badge.svg?branch=master&service=github)](https://coveralls.io/github/boennemann/nerf-dart?branch=master)
[![Dependency Status](https://david-dm.org/boennemann/nerf-dart/master.svg)](https://david-dm.org/boennemann/nerf-dart/master)
[![devDependency Status](https://david-dm.org/boennemann/nerf-dart/master/dev-status.svg)](https://david-dm.org/boennemann/nerf-dart/master#info=dependencies)

> Maps a URL to an identifier.

```js

var toNerfDart = require('nerf-dart')

toNerfDart('http://registry.npmjs.org')
// //registry.npmjs.org/
```

Originally from [npm](http://npmjs.com/). Taken from https://github.com/npm/npm/blob/master/lib/config/nerf-dart.js and made available as a standalone package for easier reuse.
