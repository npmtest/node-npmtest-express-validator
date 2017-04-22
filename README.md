# npmtest-express-validator

#### basic test coverage for  [express-validator (v3.2.0)](https://github.com/ctavan/express-validator)  [![npm package](https://img.shields.io/npm/v/npmtest-express-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-validator.svg)](https://travis-ci.org/npmtest/node-npmtest-express-validator)

#### Express middleware for the validator module.

[![NPM](https://nodei.co/npm/express-validator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-validator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-validator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-validator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-validator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-validator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-validator/build/test-report.html](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-validator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-validator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-validator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-validator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christoph Tavan"
    },
    "bugs": {
        "url": "https://github.com/ctavan/express-validator/issues"
    },
    "contributors": [
        {
            "name": "Chris O'Hara"
        },
        {
            "name": "@orfaust"
        },
        {
            "name": "@zero21xxx"
        },
        {
            "name": "Roman Kalyakin"
        },
        {
            "name": "Rusty Bailey"
        },
        {
            "name": "Gustavo Henke"
        },
        {
            "name": "Ayman Nedjmeddine"
        }
    ],
    "dependencies": {
        "@types/bluebird": "~3.0.36",
        "@types/express": "~4.0.34",
        "bluebird": "^3.4.0",
        "lodash": "^4.16.0",
        "validator": "~6.2.0"
    },
    "description": "Express middleware for the validator module.",
    "devDependencies": {
        "body-parser": "1.12.3",
        "chai": "2.3.0",
        "cookie-parser": "1.4.1",
        "coveralls": "2.11.14",
        "eslint": "^3.13.1",
        "express": "4.12.3",
        "mocha": "2.2.4",
        "nyc": "8.4.0",
        "supertest": "0.15.0",
        "typescript": "~2.0.10"
    },
    "directories": {},
    "dist": {
        "shasum": "9537abeb0f66e439f9e30b4ed16c4c6c231318e2",
        "tarball": "https://registry.npmjs.org/express-validator/-/express-validator-3.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "153de3209212ffae246377e1a4e046a5729b0b41",
    "homepage": "https://github.com/ctavan/express-validator",
    "keywords": [
        "express",
        "validator",
        "validation",
        "validate",
        "sanitize",
        "sanitization",
        "xss"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "ctavan"
        },
        {
            "name": "gustavohenke"
        },
        {
            "name": "rustybailey"
        }
    ],
    "name": "express-validator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ctavan/express-validator.git"
    },
    "scripts": {
        "lint": "eslint lib test",
        "report-coverage": "cat coverage/lcov.info | coveralls",
        "test": "nyc mocha && tsc",
        "travis-build": "npm test && npm run lint"
    },
    "types": "./index.d.ts",
    "version": "3.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
