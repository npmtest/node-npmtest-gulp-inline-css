# test coverage for  [gulp-inline-css (v3.1.0)](https://github.com/jonkemp/gulp-inline-css#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-inline-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-inline-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-inline-css.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-inline-css)
#### Inline linked css in an html file. Useful for emails.

[![NPM](https://nodei.co/npm/gulp-inline-css.png?downloads=true)](https://www.npmjs.com/package/gulp-inline-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-inline-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-inline-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-inline-css/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-gulp-inline-css%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-inline-css/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-inline-css%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-inline-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-inline-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Kemp",
        "email": "kempdogg@gmail.com",
        "url": "http://jonkemp.com/"
    },
    "bugs": {
        "url": "https://github.com/jonkemp/gulp-inline-css/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.0",
        "inline-css": "^2.2.1",
        "through2": "^0.6.1"
    },
    "description": "Inline linked css in an html file. Useful for emails.",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "event-stream": "^3.3.2",
        "gulp": "^3.9.0",
        "gulp-eslint": "^1.1.1",
        "gulp-mocha": "^2.0.0",
        "mocha": "*",
        "nyc": "^5.0.0",
        "should": "^4.6.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "71d6dff2adae5ba241eaf568798ffbd3a9c8cf09",
        "tarball": "https://registry.npmjs.org/gulp-inline-css/-/gulp-inline-css-3.1.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "b42157d3079f4ad0021907495a0ba68c8e54b557",
    "homepage": "https://github.com/jonkemp/gulp-inline-css#readme",
    "keywords": [
        "gulpplugin",
        "inline",
        "css",
        "html",
        "email"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonkemp",
            "email": "kempdogg@gmail.com"
        }
    ],
    "name": "gulp-inline-css",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonkemp/gulp-inline-css.git"
    },
    "scripts": {
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls",
        "lint": "gulp lint",
        "test": "mocha"
    },
    "version": "3.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
