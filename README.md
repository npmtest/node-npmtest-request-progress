# npmtest-request-progress

#### basic test coverage for  [request-progress (v3.0.0)](https://github.com/IndigoUnited/node-request-progress#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-request-progress.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-request-progress) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-request-progress.svg)](https://travis-ci.org/npmtest/node-npmtest-request-progress)

#### Tracks the download progress of a request made with mikeal/request, giving insight of various metrics including progress percent, download speed and time remaining

[![NPM](https://nodei.co/npm/request-progress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-progress)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-request-progress/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-progress/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-request-progress/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-request-progress/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-request-progress/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-request-progress/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-request-progress/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-request-progress/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-request-progress/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-request-progress/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-request-progress/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-progress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-request-progress/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-request-progress/build/test-report.html](https://npmtest.github.io/node-npmtest-request-progress/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-request-progress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-request-progress/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-request-progress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-progress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-progress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-progress/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-request-progress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-request-progress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "IndigoUnited",
        "url": "http://indigounited.com"
    },
    "bugs": {
        "url": "http://github.com/IndigoUnited/node-request-progress/issues"
    },
    "dependencies": {
        "throttleit": "^1.0.0"
    },
    "description": "Tracks the download progress of a request made with mikeal/request, giving insight of various metrics including progress percent, download speed and time remaining",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "expect.js": "^0.3.1",
        "istanbul": "^0.4.1",
        "mocha": "^3.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4ca754081c7fec63f505e4faa825aa06cd669dbe",
        "tarball": "https://registry.npmjs.org/request-progress/-/request-progress-3.0.0.tgz"
    },
    "gitHead": "329976448037eaef4c1af2c28690067adba91d07",
    "homepage": "https://github.com/IndigoUnited/node-request-progress#readme",
    "keywords": [
        "progress",
        "request",
        "mikeal",
        "size",
        "bytes",
        "percent",
        "percentage",
        "speed",
        "eta",
        "etr"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "satazor"
        }
    ],
    "name": "request-progress",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/IndigoUnited/node-request-progress.git"
    },
    "scripts": {
        "test": "mocha --bail",
        "test-cov": "istanbul cover --dir test/coverage _mocha -- --bail && echo open test/coverage/lcov-report/index.html",
        "test-travis": "istanbul cover _mocha --report lcovonly -- --bail && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "version": "3.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
