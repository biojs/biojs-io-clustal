biojs-io-clustal
----------------

[![Build Status](https://drone.io/github.com/biojs/biojs-io-clustal/status.png)](https://drone.io/github.com/biojs/biojs-io-clustal/latest)
[![NPM version](http://img.shields.io/npm/v/biojs-io-clustal.svg)](https://www.npmjs.org/package/biojs-io-clustal)
[![Dependencies](https://david-dm.org/biojs/biojs-io-clustal.png)](https://david-dm.org/biojs/biojs-io-clustal)
[![Code Climate](https://codeclimate.com/github/biojs/biojs-io-clustal/badges/gpa.svg)](https://codeclimate.com/github/biojs/biojs-io-clustal)
[![NPM downloads](http://img.shields.io/npm/dm/biojs-io-clustal.svg)](https://www.npmjs.org/package/biojs-io-clustal)

```
npm install biojs-io-clustal
```

Use in your browser
-------------------

[Download](https://drone.io/github.com/biojs/biojs-io-clustal/files) a compiled version for browser use.

```
npm run build-browser
```

The namespace is `biojs.io.clustal`.

How-to
------

### 1. read a url

```
Clustal.read(url, function(seqs) { }
```

`function` is your async callback.

### 2. parse string

```
var seqs = Clustal.parse(str);
```

Sequence object
---------------

```
this.seq 
this.name 
this.id 
```