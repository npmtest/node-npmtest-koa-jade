# npmtest-koa-jade

#### basic test coverage for  [koa-jade (v2.1.0)](https://github.com/chrisyip/koa-jade)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-jade.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-jade) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-jade.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-jade)

#### A Jade middleware for Koa

[![NPM](https://nodei.co/npm/koa-jade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-jade)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-jade/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-jade/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-jade/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-jade/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-jade/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-jade/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-jade/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-jade/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-jade/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-jade/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-jade/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-jade/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-jade/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-jade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-jade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-jade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-jade/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-jade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-jade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chris Yip"
    },
    "bugs": {
        "url": "https://github.com/chrisyip/koa-jade/issues"
    },
    "dependencies": {
        "fs-extra": "^0.24.0",
        "jade": "^1.11.0",
        "lodash": "^3.10.1"
    },
    "description": "A Jade middleware for Koa",
    "devDependencies": {
        "bluebird": "^2.9.34",
        "chai": "^3.2.0",
        "cheerio": "^0.19.0",
        "eslint": "^1.10.2",
        "istanbul": "^0.3.19",
        "jstransformer-markdown-it": "^0.1.0",
        "koa": "^1.0.0",
        "koa-route": "^2.4.2",
        "koa-vhost": "^0.5.0",
        "marked": "^0.3.5",
        "mocha": "^2.3.0",
        "supertest": "^1.1.0",
        "supertest-koa-agent": "^0.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3d470c658b886e1c2cdbc5a1ca3f770503f1f513",
        "tarball": "https://registry.npmjs.org/koa-jade/-/koa-jade-2.1.0.tgz"
    },
    "engines": {
        "node": ">=0.11.9"
    },
    "gitHead": "0f1e836ac50e5fb6403a6d15e932734988802fee",
    "homepage": "https://github.com/chrisyip/koa-jade",
    "keywords": [
        "koa",
        "jade",
        "template"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "chrisyipw"
        }
    ],
    "name": "koa-jade",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/chrisyip/koa-jade.git"
    },
    "scripts": {
        "lint": "eslint .",
        "mocha": "node --harmony node_modules/istanbul/lib/cli.js cover node_modules/mocha/bin/_mocha --bail --check-leaks test/",
        "test": "npm run lint && npm run mocha"
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
