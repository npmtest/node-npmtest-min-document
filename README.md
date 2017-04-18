# npmtest-min-document

#### test coverage for  [min-document (v2.19.0)](https://github.com/Raynos/min-document)  [![npm package](https://img.shields.io/npm/v/npmtest-min-document.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-min-document) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-min-document.svg)](https://travis-ci.org/npmtest/node-npmtest-min-document)

#### A minimal DOM implementation

[![NPM](https://nodei.co/npm/min-document.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/min-document)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-min-document/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-min-document/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-min-document/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-min-document/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-min-document/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-min-document/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-min-document/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-min-document/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-min-document/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-min-document/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-min-document/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-min-document/build/test-report.html](https://npmtest.github.io/node-npmtest-min-document/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-min-document/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-min-document/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-min-document/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-min-document/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-min-document/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-min-document/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-min-document/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-min-document/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/min-document/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "dom-walk": "^0.1.0"
    },
    "description": "A minimal DOM implementation",
    "devDependencies": {
        "run-browser": "git://github.com/Raynos/run-browser.git",
        "tap-dot": "^0.2.1",
        "tap-spec": "^0.1.8",
        "tape": "^2.12.3"
    },
    "directories": {},
    "dist": {
        "shasum": "7bd282e3f5842ed295bb748cdd9f1ffa2c824685",
        "tarball": "https://registry.npmjs.org/min-document/-/min-document-2.19.0.tgz"
    },
    "gitHead": "97449f71bccf778f351dc4c8d9db0ebf6e8b39cb",
    "homepage": "https://github.com/Raynos/min-document",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/min-document/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos"
        },
        {
            "name": "mattesch"
        }
    ],
    "name": "min-document",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/min-document.git"
    },
    "scripts": {
        "browser": "run-browser test/index.js",
        "cover": "istanbul cover --report none --print detail ./test/index.js",
        "dot": "node ./test/index.js | tap-dot",
        "phantom": "run-browser test/index.js -b | tap-spec",
        "test": "node ./test/index.js | tap-spec",
        "view-cover": "istanbul report html && google-chrome ./coverage/index.html"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "2.19.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
