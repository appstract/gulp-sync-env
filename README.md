# gulp-sync-env
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url]  [![Coverage Status][coveralls-image]][coveralls-url] [![Dependency Status][depstat-image]][depstat-url]

> sync-env plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-sync-env` as a development dependency:

```shell
npm install --save-dev gulp-sync-env
```

Then, add it to your `gulpfile.js`:

```javascript
var sync-env = require("gulp-sync-env");

gulp.src("./src/*.ext")
	.pipe(sync-env({
		msg: "Hello Gulp!"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### sync-env(options)

#### options.msg
Type: `String`  
Default: `Hello World`

The message you wish to attach to file.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)

[npm-url]: https://npmjs.org/package/gulp-sync-env
[npm-image]: https://badge.fury.io/js/gulp-sync-env.png

[travis-url]: http://travis-ci.org/303k/gulp-sync-env
[travis-image]: https://secure.travis-ci.org/303k/gulp-sync-env.png?branch=master

[coveralls-url]: https://coveralls.io/r/303k/gulp-sync-env
[coveralls-image]: https://coveralls.io/repos/303k/gulp-sync-env/badge.png

[depstat-url]: https://david-dm.org/303k/gulp-sync-env
[depstat-image]: https://david-dm.org/303k/gulp-sync-env.png