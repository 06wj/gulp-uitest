# gulp-uitest

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/gulp-uitest.svg
[npm-url]: https://npmjs.org/package/gulp-uitest
[travis-image]: https://img.shields.io/travis/xudafeng/gulp-uitest.svg
[travis-url]: https://travis-ci.org/xudafeng/gulp-uitest
[coveralls-image]: https://img.shields.io/coveralls/xudafeng/gulp-uitest.svg
[coveralls-url]: https://coveralls.io/r/xudafeng/gulp-uitest?branch=master
[node-image]: https://img.shields.io/badge/node.js-%3E=_7-green.svg
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/gulp-uitest.svg
[download-url]: https://npmjs.org/package/gulp-uitest

> gulp uitest

## Installment

```bash
$ npm i gulp-uitest --save-dev
```

## Usage

```javascript
var uitest = require('gulp-uitest');

gulp.task('test', [], function() {
  return gulp
    .src('path/to/index.html')
    .pipe(uitest({
      width: 600,
      height: 480,
      hidpi: false,
      useContentSize: true,
      show: false
    }));
});
```

[xudafeng/uitest](//github.com/xudafeng/uitest)

<!-- GITCONTRIBUTOR_START -->

## Contributors

|[<img src="https://avatars.githubusercontent.com/u/1011681?v=4" width="100px;"/><br/><sub><b>xudafeng</b></sub>](https://github.com/xudafeng)<br/>|[<img src="https://avatars.githubusercontent.com/u/4006436?v=4" width="100px;"/><br/><sub><b>meowtec</b></sub>](https://github.com/meowtec)<br/>|
| :---: | :---: |


This project follows the git-contributor [spec](https://github.com/xudafeng/git-contributor), auto updated at `Sun Jul 18 2021 13:06:00 GMT+0800`.

<!-- GITCONTRIBUTOR_END -->

## License

The MIT License (MIT)
