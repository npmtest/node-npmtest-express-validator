# test coverage for  [express-validator (v3.1.3)](https://github.com/ctavan/express-validator)  [![npm package](https://img.shields.io/npm/v/npmtest-express-validator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-validator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-validator.svg)](https://travis-ci.org/npmtest/node-npmtest-express-validator)
#### Express middleware for the validator module.

[![NPM](https://nodei.co/npm/express-validator.png?downloads=true)](https://www.npmjs.com/package/express-validator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-validator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-validator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-validator/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-express-validator/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-express-validator%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-validator/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-validator/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-express-validator%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-validator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-validator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christoph Tavan",
        "email": "dev@tavan.de"
    },
    "bugs": {
        "url": "https://github.com/ctavan/express-validator/issues"
    },
    "contributors": [
        {
            "name": "Chris O'Hara",
            "email": "cohara87@gmail.com"
        },
        {
            "name": "@orfaust"
        },
        {
            "name": "@zero21xxx"
        },
        {
            "name": "Roman Kalyakin",
            "email": "roman@kalyakin.com"
        },
        {
            "name": "Rusty Bailey",
            "email": "rustylbailey@gmail.com"
        },
        {
            "name": "Gustavo Henke",
            "email": "guhenke@gmail.com"
        },
        {
            "name": "Ayman Nedjmeddine",
            "email": "theycallmethedr@gmail.com"
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
        "shasum": "5670a37921340c1e529c7b6fabc3551ee1dbcf6d",
        "tarball": "https://registry.npmjs.org/express-validator/-/express-validator-3.1.3.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "b983e4f31b7d6ccccf53b1349329c9f93c84f5b0",
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
            "name": "ctavan",
            "email": "dev@tavan.de"
        },
        {
            "name": "gustavohenke",
            "email": "guhenke@gmail.com"
        },
        {
            "name": "rustybailey",
            "email": "rustylbailey@gmail.com"
        }
    ],
    "name": "express-validator",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "3.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
