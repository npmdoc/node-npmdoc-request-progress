# npmdoc-request-progress

#### api documentation for  [request-progress (v3.0.0)](https://github.com/IndigoUnited/node-request-progress#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-request-progress.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-request-progress) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-request-progress.svg)](https://travis-ci.org/npmdoc/node-npmdoc-request-progress)

#### Tracks the download progress of a request made with mikeal/request, giving insight of various metrics including progress percent, download speed and time remaining

[![NPM](https://nodei.co/npm/request-progress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-progress)

- [https://npmdoc.github.io/node-npmdoc-request-progress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-progress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-progress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-progress/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-request-progress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-request-progress/build/screenCapture.npmPackageDependencyTree.svg)



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
