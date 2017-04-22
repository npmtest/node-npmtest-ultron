# npmtest-ultron

#### basic test coverage for  [ultron (v1.1.0)](https://github.com/unshiftio/ultron)  [![npm package](https://img.shields.io/npm/v/npmtest-ultron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ultron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ultron.svg)](https://travis-ci.org/npmtest/node-npmtest-ultron)

#### Ultron is high-intelligence robot. It gathers intel so it can start improving upon his rudimentary design

[![NPM](https://nodei.co/npm/ultron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ultron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ultron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ultron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ultron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ultron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ultron/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ultron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ultron/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ultron/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ultron/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ultron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ultron/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ultron/build/test-report.html](https://npmtest.github.io/node-npmtest-ultron/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ultron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ultron/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ultron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ultron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ultron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ultron/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ultron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ultron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Arnout Kazemier"
    },
    "bugs": {
        "url": "https://github.com/unshiftio/ultron/issues"
    },
    "dependencies": {},
    "description": "Ultron is high-intelligence robot. It gathers intel so it can start improving upon his rudimentary design",
    "devDependencies": {
        "assume": "1.4.x",
        "eventemitter3": "2.0.x",
        "istanbul": "0.4.x",
        "mocha": "~3.2.0",
        "pre-commit": "~1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b07a2e6a541a815fc6a34ccd4533baec307ca864",
        "tarball": "https://registry.npmjs.org/ultron/-/ultron-1.1.0.tgz"
    },
    "gitHead": "6eb97b74402978aebda4a9d497cb6243ec80c9f1",
    "homepage": "https://github.com/unshiftio/ultron",
    "keywords": [
        "Ultron",
        "robot",
        "gather",
        "intelligence",
        "event",
        "events",
        "eventemitter",
        "emitter",
        "cleanup"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "unshift"
        },
        {
            "name": "v1"
        },
        {
            "name": "3rdeden"
        }
    ],
    "name": "ultron",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/unshiftio/ultron.git"
    },
    "scripts": {
        "100%": "istanbul check-coverage --statements 100 --functions 100 --lines 100 --branches 100",
        "coverage": "istanbul cover _mocha -- test.js",
        "test": "mocha test.js",
        "test-travis": "istanbul cover _mocha --report lcovonly -- test.js",
        "watch": "mocha --watch test.js"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
