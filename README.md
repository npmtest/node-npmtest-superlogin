# npmtest-superlogin

#### basic test coverage for  [superlogin (v0.6.1)](https://github.com/colinskow/superlogin)  [![npm package](https://img.shields.io/npm/v/npmtest-superlogin.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-superlogin) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-superlogin.svg)](https://travis-ci.org/npmtest/node-npmtest-superlogin)

#### Powerful authentication for APIs and single page apps using the CouchDB ecosystem which supports a variety of providers.

[![NPM](https://nodei.co/npm/superlogin.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/superlogin)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-superlogin/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-superlogin/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-superlogin/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-superlogin/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-superlogin/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-superlogin/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-superlogin/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-superlogin/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-superlogin/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-superlogin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-superlogin/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-superlogin/build/test-report.html](https://npmtest.github.io/node-npmtest-superlogin/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-superlogin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-superlogin/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-superlogin/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-superlogin/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-superlogin/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-superlogin/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-superlogin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-superlogin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Colin Skow"
    },
    "bugs": {
        "url": "https://github.com/colinskow/superlogin/issues"
    },
    "dependencies": {
        "bluebird": "^3.3.4",
        "couch-pwd": "0.0.1",
        "ejs": "^2.3.1",
        "express": "^4.13.3",
        "extend": "^3.0.0",
        "node-uuid": "^1.4.3",
        "nodemailer": "^2.3.0",
        "nodemailer-stub-transport": "^1.0.0",
        "passport": "^0.3.2",
        "passport-http-bearer-sl": "^1.0.1",
        "passport-local": "^1.0.0",
        "pouchdb": "~5.3.1",
        "pouchdb-seed-design": "^0.2.0",
        "redis": "^2.5.2",
        "sofa-model": "^0.2.0",
        "superagent": "^1.2.0",
        "urlsafe-base64": "1.0.0"
    },
    "description": "Powerful authentication for APIs and single page apps using the CouchDB ecosystem which supports a variety of providers.",
    "devDependencies": {
        "body-parser": "^1.9.2",
        "chai": "^3.5.0",
        "gulp": "^3.8.6",
        "gulp-jshint": "^2.0.0",
        "gulp-mocha": "^2.2.0",
        "jshint": "^2.9.1",
        "jshint-stylish": "^2.1.0",
        "mocha": "^2.4.5",
        "morgan": "^1.5.2"
    },
    "directories": {},
    "dist": {
        "shasum": "d783382ec76913d01ef859e82ab9300659f5136e",
        "tarball": "https://registry.npmjs.org/superlogin/-/superlogin-0.6.1.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "17900816e8a5495da16917cab1c2ccd7187c625d",
    "homepage": "https://github.com/colinskow/superlogin",
    "keywords": [
        "authentication",
        "login",
        "PouchDB",
        "CouchDB",
        "Cloudant",
        "passport",
        "oauth",
        "Facebook",
        "Twitter",
        "Node",
        "Express"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "colinskow"
        }
    ],
    "name": "superlogin",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/colinskow/superlogin.git"
    },
    "scripts": {
        "test": "gulp"
    },
    "version": "0.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
