# api documentation for  [gulp-sass (v3.1.0)](https://github.com/dlmanning/gulp-sass#readme)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-sass.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-sass)
#### Gulp plugin for sass

[![NPM](https://nodei.co/npm/gulp-sass.png?downloads=true)](https://www.npmjs.com/package/gulp-sass)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-sass/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-gulp-sass_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-sass/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-gulp-sass/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "David Manning"
    },
    "bugs": {
        "url": "https://github.com/dlmanning/gulp-sass/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0",
        "lodash.clonedeep": "^4.3.2",
        "node-sass": "^4.2.0",
        "through2": "^2.0.0",
        "vinyl-sourcemaps-apply": "^0.2.0"
    },
    "description": "Gulp plugin for sass",
    "devDependencies": {
        "autoprefixer-core": "^5.2.1",
        "eslint": "^2.9.0",
        "globule": "^1.0.0",
        "gulp": "^3.8.11",
        "gulp-postcss": "^5.1.10",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-tap": "^0.1.3",
        "mocha": "^2.2.1",
        "rimraf": "^2.4.3",
        "should": "^8.3.1"
    },
    "directories": {},
    "dist": {
        "shasum": "53dc4b68a1f5ddfe4424ab4c247655269a8b74b7",
        "tarball": "https://registry.npmjs.org/gulp-sass/-/gulp-sass-3.1.0.tgz"
    },
    "gitHead": "25d37e799a358ab11c176860fad1b6327be40329",
    "homepage": "https://github.com/dlmanning/gulp-sass#readme",
    "keywords": [
        "gulpplugin",
        "sass",
        "gulp"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dlmanning",
            "email": "dlmanning@me.com"
        },
        {
            "name": "snugug",
            "email": "sam@snug.ug"
        },
        {
            "name": "xzyfer",
            "email": "xzyfer@gmail.com"
        }
    ],
    "name": "gulp-sass",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/dlmanning/gulp-sass.git"
    },
    "scripts": {
        "test": "mocha test"
    },
    "version": "3.1.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module gulp-sass](#apidoc.module.gulp-sass)
1.  [function <span class="apidocSignatureSpan">gulp-sass.</span>logError (error)](#apidoc.element.gulp-sass.logError)
1.  [function <span class="apidocSignatureSpan">gulp-sass.</span>sync (options)](#apidoc.element.gulp-sass.sync)
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types.Boolean.prototype
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types.Color.prototype
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types.List.prototype
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types.Map.prototype
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types.Number.prototype
1.  object <span class="apidocSignatureSpan">gulp-sass.</span>compiler.types.String.prototype

#### [module gulp-sass.compiler](#apidoc.module.gulp-sass.compiler)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.</span>render (opts, cb)](#apidoc.element.gulp-sass.compiler.render)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.</span>renderSync (opts)](#apidoc.element.gulp-sass.compiler.renderSync)
1.  object <span class="apidocSignatureSpan">gulp-sass.compiler.</span>FALSE
1.  object <span class="apidocSignatureSpan">gulp-sass.compiler.</span>NULL
1.  object <span class="apidocSignatureSpan">gulp-sass.compiler.</span>TRUE
1.  object <span class="apidocSignatureSpan">gulp-sass.compiler.</span>types
1.  string <span class="apidocSignatureSpan">gulp-sass.compiler.</span>info

#### [module gulp-sass.compiler.types](#apidoc.module.gulp-sass.compiler.types)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Boolean ()](#apidoc.element.gulp-sass.compiler.types.Boolean)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Color ()](#apidoc.element.gulp-sass.compiler.types.Color)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Error ()](#apidoc.element.gulp-sass.compiler.types.Error)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>List ()](#apidoc.element.gulp-sass.compiler.types.List)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Map ()](#apidoc.element.gulp-sass.compiler.types.Map)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Null ()](#apidoc.element.gulp-sass.compiler.types.Null)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Number ()](#apidoc.element.gulp-sass.compiler.types.Number)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>String ()](#apidoc.element.gulp-sass.compiler.types.String)

#### [module gulp-sass.compiler.types.Boolean.prototype](#apidoc.module.gulp-sass.compiler.types.Boolean.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Boolean.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.Boolean.prototype.getValue)

#### [module gulp-sass.compiler.types.Color.prototype](#apidoc.module.gulp-sass.compiler.types.Color.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getA ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getA)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getB ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getB)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getG ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getG)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getR ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getR)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setA ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setA)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setB ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setB)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setG ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setG)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setR ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setR)

#### [module gulp-sass.compiler.types.List.prototype](#apidoc.module.gulp-sass.compiler.types.List.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>getLength ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.getLength)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>getSeparator ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.getSeparator)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>setSeparator ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.setSeparator)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.setValue)

#### [module gulp-sass.compiler.types.Map.prototype](#apidoc.module.gulp-sass.compiler.types.Map.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>getKey ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.getKey)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>getLength ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.getLength)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>setKey ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.setKey)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.setValue)

#### [module gulp-sass.compiler.types.Number.prototype](#apidoc.module.gulp-sass.compiler.types.Number.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>getUnit ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.getUnit)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>setUnit ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.setUnit)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.setValue)

#### [module gulp-sass.compiler.types.String.prototype](#apidoc.module.gulp-sass.compiler.types.String.prototype)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.String.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.String.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">gulp-sass.compiler.types.String.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.String.prototype.setValue)



# <a name="apidoc.module.gulp-sass"></a>[module gulp-sass](#apidoc.module.gulp-sass)

#### <a name="apidoc.element.gulp-sass.logError"></a>[function <span class="apidocSignatureSpan">gulp-sass.</span>logError (error)](#apidoc.element.gulp-sass.logError)
- description and source-code
```javascript
function logError(error) {
  var message = new gutil.PluginError('sass', error.messageFormatted).toString();
  process.stderr.write(message + '\n');
  this.emit('end');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.sync"></a>[function <span class="apidocSignatureSpan">gulp-sass.</span>sync (options)](#apidoc.element.gulp-sass.sync)
- description and source-code
```javascript
function sync(options) {
  return gulpSass(options, true);
}
```
- example usage
```shell
...
'use strict';

var gulp = require('gulp');
var sass = require('gulp-sass');

gulp.task('sass', function () {
  return gulp.src('./sass/**/*.scss')
    .pipe(sass.sync().on('error', sass.logError))
    .pipe(gulp.dest('./css'));
});

gulp.task('sass:watch', function () {
  gulp.watch('./sass/**/*.scss', ['sass']);
});
'''
...
```



# <a name="apidoc.module.gulp-sass.compiler"></a>[module gulp-sass.compiler](#apidoc.module.gulp-sass.compiler)

#### <a name="apidoc.element.gulp-sass.compiler.render"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.</span>render (opts, cb)](#apidoc.element.gulp-sass.compiler.render)
- description and source-code
```javascript
render = function (opts, cb) {
  var options = getOptions(opts, cb);

  // options.error and options.success are for libsass binding
  options.error = function(err) {
    var payload = assign(new Error(), JSON.parse(err));

    if (cb) {
      options.context.callback.call(options.context, payload, null);
    }
  };

  options.success = function() {
    var result = options.result;
    var stats = endStats(result.stats);
    var payload = {
      css: result.css,
      map: result.map,
      stats: stats
    };

    if (cb) {
      options.context.callback.call(options.context, null, payload);
    }
  };

  var importer = options.importer;

  if (importer) {
    if (Array.isArray(importer)) {
      options.importer = [];
      importer.forEach(function(subject, index) {
        options.importer[index] = function(file, prev, bridge) {
          function done(result) {
            bridge.success(result === module.exports.NULL ? null : result);
          }

          var result = subject.call(options.context, file, prev, done);

          if (result !== undefined) {
            done(result);
          }
        };
      });
    } else {
      options.importer = function(file, prev, bridge) {
        function done(result) {
          bridge.success(result === module.exports.NULL ? null : result);
        }

        var result = importer.call(options.context, file, prev, done);

        if (result !== undefined) {
          done(result);
        }
      };
    }
  }

  var functions = clonedeep(options.functions);

  if (functions) {
    options.functions = {};

    Object.keys(functions).forEach(function(subject) {
      var cb = normalizeFunctionSignature(subject, functions[subject]);

      options.functions[cb.signature] = function() {
        var args = Array.prototype.slice.call(arguments),
          bridge = args.pop();

        function done(data) {
          bridge.success(data);
        }

        var result = tryCallback(cb.callback.bind(options.context), args.concat(done));

        if (result) {
          done(result);
        }
      };
    });
  }

  if (options.data) {
    binding.render(options);
  } else if (options.file) {
    binding.renderFile(options);
  } else {
    cb({status: 3, message: 'No input specified: provide a file name or a source string to process' });
  }
}
```
- example usage
```shell
...
  callback = function(error, obj) {
    if (error) {
      return errorM(error);
    }
    filePush(obj);
  };

  gulpSass.compiler.render(opts, callback);
}
else {
  //////////////////////////////
  // Sync Sass render
  //////////////////////////////
  try {
    result = gulpSass.compiler.renderSync(opts);
...
```

#### <a name="apidoc.element.gulp-sass.compiler.renderSync"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.</span>renderSync (opts)](#apidoc.element.gulp-sass.compiler.renderSync)
- description and source-code
```javascript
renderSync = function (opts) {
  var options = getOptions(opts);
  var importer = options.importer;

  if (importer) {
    if (Array.isArray(importer)) {
      options.importer = [];
      importer.forEach(function(subject, index) {
        options.importer[index] = function(file, prev) {
          var result = subject.call(options.context, file, prev);

          return result === module.exports.NULL ? null : result;
        };
      });
    } else {
      options.importer = function(file, prev) {
        var result = importer.call(options.context, file, prev);

        return result === module.exports.NULL ? null : result;
      };
    }
  }

  var functions = clonedeep(options.functions);

  if (options.functions) {
    options.functions = {};

    Object.keys(functions).forEach(function(signature) {
      var cb = normalizeFunctionSignature(signature, functions[signature]);

      options.functions[cb.signature] = function() {
        return tryCallback(cb.callback.bind(options.context), arguments);
      };
    });
  }

  var status;
  if (options.data) {
    status = binding.renderSync(options);
  } else if (options.file) {
    status = binding.renderFileSync(options);
  } else {
    throw new Error('No input specified: provide a file name or a source string to process');
  }

  var result = options.result;

  if (status) {
    result.stats = endStats(result.stats);
    return result;
  }

  throw assign(new Error(), JSON.parse(result.error));
}
```
- example usage
```shell
...
  gulpSass.compiler.render(opts, callback);
}
else {
  //////////////////////////////
  // Sync Sass render
  //////////////////////////////
  try {
    result = gulpSass.compiler.renderSync(opts);

    filePush(result);
  }
  catch (error) {
    return errorM(error);
  }
}
...
```



# <a name="apidoc.module.gulp-sass.compiler.types"></a>[module gulp-sass.compiler.types](#apidoc.module.gulp-sass.compiler.types)

#### <a name="apidoc.element.gulp-sass.compiler.types.Boolean"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Boolean ()](#apidoc.element.gulp-sass.compiler.types.Boolean)
- description and source-code
```javascript
function SassBoolean() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Color ()](#apidoc.element.gulp-sass.compiler.types.Color)
- description and source-code
```javascript
function SassColor() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Error"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Error ()](#apidoc.element.gulp-sass.compiler.types.Error)
- description and source-code
```javascript
function SassError() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.List"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>List ()](#apidoc.element.gulp-sass.compiler.types.List)
- description and source-code
```javascript
function SassList() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Map"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Map ()](#apidoc.element.gulp-sass.compiler.types.Map)
- description and source-code
```javascript
function SassMap() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Null"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Null ()](#apidoc.element.gulp-sass.compiler.types.Null)
- description and source-code
```javascript
function SassNull() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Number"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>Number ()](#apidoc.element.gulp-sass.compiler.types.Number)
- description and source-code
```javascript
function SassNumber() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.String"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.</span>String ()](#apidoc.element.gulp-sass.compiler.types.String)
- description and source-code
```javascript
function SassString() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-sass.compiler.types.Boolean.prototype"></a>[module gulp-sass.compiler.types.Boolean.prototype](#apidoc.module.gulp-sass.compiler.types.Boolean.prototype)

#### <a name="apidoc.element.gulp-sass.compiler.types.Boolean.prototype.getValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Boolean.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.Boolean.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-sass.compiler.types.Color.prototype"></a>[module gulp-sass.compiler.types.Color.prototype](#apidoc.module.gulp-sass.compiler.types.Color.prototype)

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.getA"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getA ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getA)
- description and source-code
```javascript
function getA() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.getB"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getB ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getB)
- description and source-code
```javascript
function getB() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.getG"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getG ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getG)
- description and source-code
```javascript
function getG() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.getR"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>getR ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.getR)
- description and source-code
```javascript
function getR() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.setA"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setA ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setA)
- description and source-code
```javascript
function setA() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.setB"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setB ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setB)
- description and source-code
```javascript
function setB() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.setG"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setG ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setG)
- description and source-code
```javascript
function setG() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Color.prototype.setR"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Color.prototype.</span>setR ()](#apidoc.element.gulp-sass.compiler.types.Color.prototype.setR)
- description and source-code
```javascript
function setR() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-sass.compiler.types.List.prototype"></a>[module gulp-sass.compiler.types.List.prototype](#apidoc.module.gulp-sass.compiler.types.List.prototype)

#### <a name="apidoc.element.gulp-sass.compiler.types.List.prototype.getLength"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>getLength ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.getLength)
- description and source-code
```javascript
function getLength() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.List.prototype.getSeparator"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>getSeparator ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.getSeparator)
- description and source-code
```javascript
function getSeparator() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.List.prototype.getValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.List.prototype.setSeparator"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>setSeparator ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.setSeparator)
- description and source-code
```javascript
function setSeparator() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.List.prototype.setValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.List.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.List.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-sass.compiler.types.Map.prototype"></a>[module gulp-sass.compiler.types.Map.prototype](#apidoc.module.gulp-sass.compiler.types.Map.prototype)

#### <a name="apidoc.element.gulp-sass.compiler.types.Map.prototype.getKey"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>getKey ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.getKey)
- description and source-code
```javascript
function getKey() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Map.prototype.getLength"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>getLength ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.getLength)
- description and source-code
```javascript
function getLength() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Map.prototype.getValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Map.prototype.setKey"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>setKey ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.setKey)
- description and source-code
```javascript
function setKey() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Map.prototype.setValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Map.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.Map.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-sass.compiler.types.Number.prototype"></a>[module gulp-sass.compiler.types.Number.prototype](#apidoc.module.gulp-sass.compiler.types.Number.prototype)

#### <a name="apidoc.element.gulp-sass.compiler.types.Number.prototype.getUnit"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>getUnit ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.getUnit)
- description and source-code
```javascript
function getUnit() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Number.prototype.getValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Number.prototype.setUnit"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>setUnit ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.setUnit)
- description and source-code
```javascript
function setUnit() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.Number.prototype.setValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.Number.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.Number.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.gulp-sass.compiler.types.String.prototype"></a>[module gulp-sass.compiler.types.String.prototype](#apidoc.module.gulp-sass.compiler.types.String.prototype)

#### <a name="apidoc.element.gulp-sass.compiler.types.String.prototype.getValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.String.prototype.</span>getValue ()](#apidoc.element.gulp-sass.compiler.types.String.prototype.getValue)
- description and source-code
```javascript
function getValue() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.gulp-sass.compiler.types.String.prototype.setValue"></a>[function <span class="apidocSignatureSpan">gulp-sass.compiler.types.String.prototype.</span>setValue ()](#apidoc.element.gulp-sass.compiler.types.String.prototype.setValue)
- description and source-code
```javascript
function setValue() { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
