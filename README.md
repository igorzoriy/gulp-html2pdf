# gulp-html2pdf

## Install
```sh
$ npm install gulp-html2pdf --save-dev
```

## Usage

```javascript
var html2pdf = require('gulp-html2pdf');

gulp.task('pdf', function () {
    return gulp
        .src('./in/index.html')
        .pipe(html2pdf())
        .pipe(gulp.dest('./out/'));
});
```
## License
MIT
