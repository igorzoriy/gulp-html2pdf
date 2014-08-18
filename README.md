# gulp-html2pdf


## Requirements
[wkhtmltopdf](http://wkhtmltopdf.org/) v0.10 or later.

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

## API
There are [many options](http://wkhtmltopdf.org/usage/wkhtmltopdf.txt) available to
wkhtmltopdf.  All of the command line options are supported as documented on the page linked to above.  The options are camelCased instead-of-dashed as in the command line tool.

## License
MIT
