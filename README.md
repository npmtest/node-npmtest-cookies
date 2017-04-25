# npmtest-cookies

#### basic test coverage for  [cookies (v0.7.0)](https://github.com/pillarjs/cookies#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cookies.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cookies) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cookies.svg)](https://travis-ci.org/npmtest/node-npmtest-cookies)

#### Cookies, optionally signed using Keygrip.

[![NPM](https://nodei.co/npm/cookies.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cookies)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cookies/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookies/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cookies/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cookies/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cookies/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cookies/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cookies/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cookies/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cookies/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cookies/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cookies/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cookies/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cookies/build/test-report.html](https://npmtest.github.io/node-npmtest-cookies/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cookies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cookies/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cookies/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cookies/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cookies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cookies/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cookies/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cookies/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jed Schmidt",
        "url": "http://jed.is"
    },
    "bugs": {
        "url": "https://github.com/pillarjs/cookies/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {
        "depd": "~1.1.0",
        "keygrip": "~1.0.1"
    },
    "description": "Cookies, optionally signed using Keygrip.",
    "devDependencies": {
        "express": "4.9.8",
        "istanbul": "0.4.5",
        "mocha": "2.5.3",
        "restify": "2.8.1",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0bc961d910c35254980fc7c9eff5da12011bbf00",
        "tarball": "https://registry.npmjs.org/cookies/-/cookies-0.7.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "README.md",
        "index.js"
    ],
    "gitHead": "c582e55ef687d869ddfb50fa6cde4598164ed00e",
    "homepage": "https://github.com/pillarjs/cookies#readme",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "fishrock123"
        },
        {
            "name": "jed"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "cookies",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pillarjs/cookies.git"
    },
    "scripts": {
        "test": "mocha --require test/support/env --reporter spec --bail --check-leaks test/",
        "test-ci": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --require test/support/env --reporter spec --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --require test/support/env --reporter dot --check-leaks test/"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
