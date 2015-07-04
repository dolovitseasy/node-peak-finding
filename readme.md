# node-peak-finding [![Build Status](https://travis-ci.org/vinimdocarmo/node-peak-finding.svg?branch=master)](https://travis-ci.org/vinimdocarmo/node-peak-finding) [![Coverage Status](https://coveralls.io/repos/vinimdocarmo/node-peak-finding/badge.svg)](https://coveralls.io/r/vinimdocarmo/node-peak-finding) [![devDependency Status](https://david-dm.org/vinimdocarmo/node-peak-finding/dev-status.svg)](https://david-dm.org/vinimdocarmo/node-peak-finding) [![Code Climate](https://codeclimate.com/github/vinimdocarmo/node-peak-finding/badges/gpa.svg)](https://codeclimate.com/github/vinimdocarmo/node-peak-finding)

Find an element in an array where the element peaks. Notice that the method does not return the highest peak, it just finds and returns **a** peak.

**A element is a peak if this element is larger or equal to both the elements on its sides.**

## Install

```
$ npm install --save peak-finding
```

## Usage

```js
var peakFinding = require('peak-finding');

peakFinding([1, 3, 4, 3, 5, 1, 3]);
//=> 4
```

## Time complexity
&Theta;(log2(n)) where *n* is the lenght of the input list.

## API

### peakFinding(list)

#### list

*Required*  
Type: `Array`

## License

MIT © [Vinícius do Carmo](http://vinimdocarmo.js.org)
