[![npm version](https://badge.fury.io/js/gulp-yaml-merge.svg)](https://badge.fury.io/js/gulp-yaml-merge)
[![Code Climate](https://codeclimate.com/github/ivansky/gulp-yaml-merge/badges/gpa.svg)](https://codeclimate.com/github/ivansky/gulp-yaml-merge)
[![Build Status](https://travis-ci.org/ivansky/gulp-yaml-merge.svg?branch=master)](https://travis-ci.org/ivansky/gulp-yaml-merge)

## Installation

Install package with NPM and add it to your development dependencies:

`npm install --save-dev gulp-yaml-merge`

## Usage

```js
var yamlMerge = require('gulp-yaml-merge');

gulp.task('yaml', function() {
  return gulp.src('./swagger/**/*.yaml')
    .pipe(yamlMerge('bundle.yaml'))
    .pipe(gulp.dest('./dist/'));
});
```

## LICENSE

Copyright (c) 2016

Permission is hereby granted, free of charge, to any person obtaining 
a copy of this software and associated documentation files (the "Software"), 
to deal in the Software without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, 
and/or sell copies of the Software, and to permit persons to whom 
the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included 
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, 
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES 
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, 
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, 
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH 
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
