# Invincible

A series of miscellaneous functional JavaScript utility library.

[![Travis branch](https://img.shields.io/travis/chikara-chan/invincible/dev.svg)](https://travis-ci.org/chikara-chan/invincible)
[![Coveralls branch](https://img.shields.io/coveralls/chikara-chan/invincible/dev.svg)](https://coveralls.io/github/chikara-chan/invincible)
[![npm](https://img.shields.io/npm/v/invincible.svg)](https://www.npmjs.com/package/invincible)
[![npm](https://img.shields.io/npm/l/invincible.svg)](https://github.com/chikara-chan/invincible/blob/dev/LICENSE)

## Install

``` bash
$ npm install --save invincible
# Or
$ yarn add invincible
```

## Usage

``` js
var invincible = require('invincible')
// Or
import invincible from 'invincible'
// Or
import {subModule, ...others} from 'invincible'
// Or
import subModule from 'invincible/lib/subModule'
```

## API

#### invariant

``` js
invincible.invariant(false, 'something wrong') // Throw new Error('something wrong')
invincible.invariant(true, 'something wrong')  // Noop
```

## License

Released under the [MIT](https://github.com/chikara-chan/invincible/blob/dev/LICENSE) license.
