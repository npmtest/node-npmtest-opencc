# npmtest-opencc

#### basic test coverage for  [opencc (v1.0.5)](https://github.com/BYVoid/OpenCC#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-opencc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-opencc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-opencc.svg)](https://travis-ci.org/npmtest/node-npmtest-opencc)

#### Conversion between Traditional and Simplified Chinese

[![NPM](https://nodei.co/npm/opencc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/opencc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-opencc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-opencc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-opencc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-opencc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-opencc/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-opencc/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-opencc/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-opencc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-opencc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-opencc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-opencc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-opencc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-opencc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-opencc/build/test-report.html](https://npmtest.github.io/node-npmtest-opencc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-opencc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-opencc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-opencc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-opencc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-opencc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-opencc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-opencc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-opencc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "BYVoid"
    },
    "bugs": {
        "url": "https://github.com/BYVoid/Opencc/issues"
    },
    "contributors": [
        {
            "name": "Author:"
        },
        {
            "name": "BYVoid"
        },
        {
            "name": "Contributors:"
        },
        {
            "name": "Peng Huang"
        },
        {
            "name": "Kefu Chai"
        },
        {
            "name": "LI Daobing"
        },
        {
            "name": "Asias"
        },
        {
            "name": "Peng Wu"
        },
        {
            "name": "Xiaojun Ma"
        },
        {
            "name": "佛振"
        }
    ],
    "dependencies": {
        "nan": "^2.5.1"
    },
    "description": "Conversion between Traditional and Simplified Chinese",
    "devDependencies": {
        "mocha": "2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "53a928ac29dc3557a1b1e058d369b423673ab7e5",
        "tarball": "https://registry.npmjs.org/opencc/-/opencc-1.0.5.tgz"
    },
    "gitHead": "7fdaa43f1c548cc53ab9c7b59a697851060f4f46",
    "gypfile": true,
    "homepage": "https://github.com/BYVoid/OpenCC#readme",
    "keywords": [
        "opencc",
        "Chinese",
        "conversion",
        "unicode",
        "Simplified Chinese",
        "Traditional Chinese"
    ],
    "license": "Apache-2.0",
    "main": "node/opencc.js",
    "maintainers": [
        {
            "name": "byvoid"
        }
    ],
    "name": "opencc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/BYVoid/OpenCC.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha -R spec node/test.js"
    },
    "version": "1.0.5",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
