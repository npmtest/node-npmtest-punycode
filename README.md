# npmtest-punycode

#### basic test coverage for  [punycode (v2.1.0)](https://mths.be/punycode)  [![npm package](https://img.shields.io/npm/v/npmtest-punycode.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-punycode) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-punycode.svg)](https://travis-ci.org/npmtest/node-npmtest-punycode)

#### A robust Punycode converter that fully complies to RFC 3492 and RFC 5891, and works on nearly all JavaScript platforms.

[![NPM](https://nodei.co/npm/punycode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/punycode)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-punycode/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-punycode/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-punycode/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-punycode/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-punycode/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-punycode/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-punycode/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-punycode/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-punycode/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-punycode/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-punycode/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-punycode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-punycode/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-punycode/build/test-report.html](https://npmtest.github.io/node-npmtest-punycode/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-punycode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-punycode/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-punycode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-punycode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-punycode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-punycode/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-punycode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-punycode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Bynens",
        "url": "https://mathiasbynens.be/"
    },
    "bugs": {
        "url": "https://github.com/bestiejs/punycode.js/issues"
    },
    "contributors": [
        {
            "name": "Mathias Bynens",
            "url": "https://mathiasbynens.be/"
        }
    ],
    "dependencies": {},
    "description": "A robust Punycode converter that fully complies to RFC 3492 and RFC 5891, and works on nearly all JavaScript platforms.",
    "devDependencies": {
        "codecov": "^1.0.1",
        "istanbul": "^0.4.1",
        "mocha": "^2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "5f863edc89b96db09074bad7947bf09056ca4e7d",
        "tarball": "https://registry.npmjs.org/punycode/-/punycode-2.1.0.tgz"
    },
    "engines": {
        "node": ">=6"
    },
    "files": [
        "LICENSE-MIT.txt",
        "punycode.js",
        "punycode.es6.js"
    ],
    "gitHead": "9aeca525bba478206c6e1b5501e063f3db7bda7f",
    "homepage": "https://mths.be/punycode",
    "jsnext:main": "punycode.es6.js",
    "jspm": {
        "map": {
            "./punycode.js": {
                "node": "@node/punycode"
            }
        }
    },
    "keywords": [
        "punycode",
        "unicode",
        "idn",
        "idna",
        "dns",
        "url",
        "domain"
    ],
    "license": "MIT",
    "main": "punycode.js",
    "maintainers": [
        {
            "name": "mathias"
        },
        {
            "name": "reconbot"
        }
    ],
    "name": "punycode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bestiejs/punycode.js.git"
    },
    "scripts": {
        "prepublish": "node scripts/prepublish.js",
        "test": "mocha tests"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
