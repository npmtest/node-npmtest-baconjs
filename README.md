# npmtest-baconjs

#### basic test coverage for  [baconjs (v0.7.93)](https://github.com/baconjs/bacon.js)  [![npm package](https://img.shields.io/npm/v/npmtest-baconjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-baconjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-baconjs.svg)](https://travis-ci.org/npmtest/node-npmtest-baconjs)

#### A small functional reactive programming lib for JavaScript.

[![NPM](https://nodei.co/npm/baconjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/baconjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-baconjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-baconjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-baconjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-baconjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-baconjs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-baconjs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-baconjs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-baconjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-baconjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-baconjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-baconjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-baconjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-baconjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-baconjs/build/test-report.html](https://npmtest.github.io/node-npmtest-baconjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-baconjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-baconjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-baconjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-baconjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-baconjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-baconjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-baconjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-baconjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juha Paananen",
        "url": "https://twitter.com/raimohanska"
    },
    "bugs": {
        "url": "https://github.com/baconjs/bacon.js/issues"
    },
    "contributors": [
        {
            "name": "Daniel K",
            "url": "https://twitter.com/xflowwolf"
        }
    ],
    "dependencies": {},
    "description": "A small functional reactive programming lib for JavaScript.",
    "devDependencies": {
        "babel": "^5.8.23",
        "benchmark": "1.0.0",
        "bluebird": "^2",
        "bower-json": "^0.6.0",
        "browserify": "^11.2.0",
        "browserstack-runner": "^0.3.8",
        "chai": "^3.3.0",
        "coffee-script": "^1.9.1",
        "coffeeify": "^1.0.0",
        "coffeelint": "^1.9.2",
        "es6-promise": "^3.0.2",
        "escodegen": "^1.6.1",
        "esprima": "^2.0.0",
        "estraverse": "^1.9.1",
        "git-rev": "^0.2.1",
        "github": "^0.2.4",
        "grunt": "0.4",
        "grunt-cli": "0.1.13",
        "grunt-coffeelint": "0.0.13",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-eslint": "^17.2.0",
        "grunt-shell": "^1.1.2",
        "jasmine-node": "^1.14.5",
        "jquery": "^2.1.4",
        "jsstana": "^0.1.5",
        "lodash": "^4.0.0",
        "mocha": "^2.1.0",
        "rxjs": "^5.2.0",
        "shelljs": "^0.5.3",
        "sinon": "^1.12.2",
        "uglify-js": "^2.4.16",
        "when": "^3.6.4",
        "zen-observable": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9b056a1689e09eabb3d907a5ac30bb6b47861765",
        "tarball": "https://registry.npmjs.org/baconjs/-/baconjs-0.7.93.tgz"
    },
    "gitHead": "5e4ebe1dea04e7d2b32c27db3c67ff5a7723486c",
    "homepage": "https://github.com/baconjs/bacon.js",
    "keywords": [
        "bacon.js",
        "bacon",
        "frp",
        "functional",
        "reactive",
        "programming",
        "stream",
        "streams",
        "EventStream",
        "Rx",
        "RxJs",
        "Observable"
    ],
    "license": "MIT",
    "main": "dist/Bacon.js",
    "maintainers": [
        {
            "name": "raimohanska"
        },
        {
            "name": "pnex2000"
        }
    ],
    "name": "baconjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/baconjs/bacon.js.git"
    },
    "scripts": {
        "pre-publish": "grunt",
        "test": "./runtests"
    },
    "version": "0.7.93",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
