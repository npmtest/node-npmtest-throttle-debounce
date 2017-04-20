# npmtest-throttle-debounce

#### basic test coverage for  [throttle-debounce (v1.0.1)](https://github.com/niksy/throttle-debounce#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-throttle-debounce.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-throttle-debounce) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-throttle-debounce.svg)](https://travis-ci.org/npmtest/node-npmtest-throttle-debounce)

#### Throttle/debounce your functions.

[![NPM](https://nodei.co/npm/throttle-debounce.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/throttle-debounce)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-throttle-debounce/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-throttle-debounce/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-throttle-debounce/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-throttle-debounce/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-throttle-debounce/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-throttle-debounce/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-throttle-debounce/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-throttle-debounce/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-throttle-debounce/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-throttle-debounce/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-throttle-debounce/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-throttle-debounce/build/test-report.html](https://npmtest.github.io/node-npmtest-throttle-debounce/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-throttle-debounce/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-throttle-debounce/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-throttle-debounce/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-throttle-debounce/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-throttle-debounce/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-throttle-debounce/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-throttle-debounce/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-throttle-debounce/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "throttle-debounce",
    "version": "1.0.1",
    "description": "Throttle/debounce your functions.",
    "main": "index.js",
    "author": "Ivan Nikolić <niksy5@gmail.com> (http://ivannikolic.com/)",
    "contributors": [
        "Ben Alman (http://benalman.com)"
    ],
    "license": "MIT",
    "engines": {
        "node": ">=0.10.0"
    },
    "directories": {
        "test": "test"
    },
    "scripts": {
        "test": "eslint {index,test/*}.js && karma start --single-run --browsers PhantomJS"
    },
    "dependencies": {},
    "devDependencies": {
        "browserify": "^13.0.0",
        "eslint": "^1.10.3",
        "eslint-config-niksy": "^1.0.6",
        "karma": "^0.13.22",
        "karma-browserify": "^5.0.4",
        "karma-chrome-launcher": "^0.2.3",
        "karma-firefox-launcher": "^0.1.7",
        "karma-mocha-reporter": "^2.0.2",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-qunit": "^0.1.9",
        "mocha": "^2.4.5",
        "phantomjs-prebuilt": "^2.1.7",
        "qunitjs": "^1.23.1",
        "watchify": "^3.7.0"
    },
    "keywords": [
        "throttle",
        "debounce",
        "browserify"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/niksy/throttle-debounce.git"
    },
    "bugs": {
        "url": "https://github.com/niksy/throttle-debounce/issues"
    },
    "homepage": "https://github.com/niksy/throttle-debounce#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
