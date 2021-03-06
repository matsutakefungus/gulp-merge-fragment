# gulp-fragment-merge
合并页面中引用文件到当前页面
## Usage

First, install `gulp-merge-fragment` as a development dependency:

```shell
npm install --save-dev gulp-fragment-merge
```

Then, add it to your `gulpfile.js`:

```javascript
var merge-fragment = require("gulp-merge-fragment");

gulp.src("./src/*.ext")
	.pipe(merge-fragment({
		msg: "Hello Gulp!"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### merge-fragment(options)

#### options.msg
Type: `String`  
Default: `Hello World`

The message you wish to attach to file.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)