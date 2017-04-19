# npmtest-wiredep

#### basic test coverage for  [wiredep (v4.0.0)](https://github.com/taptapship/wiredep#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-wiredep.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-wiredep) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-wiredep.svg)](https://travis-ci.org/npmtest/node-npmtest-wiredep)

#### Wire Bower dependencies to your source code.

[![NPM](https://nodei.co/npm/wiredep.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wiredep)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-wiredep/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-wiredep/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-wiredep/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-wiredep/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-wiredep/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-wiredep/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-wiredep/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-wiredep/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-wiredep/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-wiredep/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-wiredep/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-wiredep/build/test-report.html](https://npmtest.github.io/node-npmtest-wiredep/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-wiredep/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-wiredep/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-wiredep/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-wiredep/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wiredep/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wiredep/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-wiredep/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-wiredep/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stephen Sawchuk"
    },
    "bugs": {
        "url": "https://github.com/taptapship/wiredep/issues"
    },
    "dependencies": {
        "bower-config": "^1.3.0",
        "glob": "^7.0.3",
        "lodash": "^4.6.1",
        "propprop": "^0.3.0",
        "through2": "^2.0.1",
        "wiredep-cli": "^0.1.0"
    },
    "description": "Wire Bower dependencies to your source code.",
    "devDependencies": {
        "chai": "^3.5.0",
        "fs-extra": "^0.26.7",
        "istanbul": "^0.4.2",
        "jshint": "*",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "ee9548a9504dfe7e85401a435dbed2c9b4ea2e44",
        "tarball": "https://registry.npmjs.org/wiredep/-/wiredep-4.0.0.tgz"
    },
    "files": [
        "lib/",
        "LICENSE",
        "wiredep.js"
    ],
    "gitHead": "3416e1e6eb61b1498adcdf9dd42262a01fdc1b19",
    "homepage": "https://github.com/taptapship/wiredep#readme",
    "keywords": [
        "bower",
        "package",
        "management",
        "inject",
        "script",
        "dependencies"
    ],
    "license": "MIT",
    "main": "./wiredep.js",
    "maintainers": [
        {
            "name": "cwspear"
        },
        {
            "name": "eddiemonge"
        },
        {
            "name": "ruyadorno"
        },
        {
            "name": "stephenplusplus"
        }
    ],
    "name": "wiredep",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/taptapship/wiredep.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- -R spec",
        "test": "jshint *.js lib/*.js test/*.js && NODE_ENV=test mocha -R spec"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
