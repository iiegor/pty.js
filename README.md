# ptyw.js [![Dependency Status](https://david-dm.org/iiegor/ptyw.js.svg)](https://david-dm.org/iiegor/ptyw.js) [![Build Status](https://travis-ci.org/iiegor/ptyw.js.svg?branch=master)](https://travis-ci.org/iiegor/ptyw.js)

A fork of [pty.js](https://github.com/chjj/pty.js) to have a more updated module. 

## API

#### spawn(*command[, args, opts]*)

##### command
###### Type: String

##### args
###### Type: Array

##### opts
###### Type: Object

Example:
```sh
ptyw.spawn('java', ['-version'], {
  cols: 80,
  rows: 30,
  env: process.env
});
```
