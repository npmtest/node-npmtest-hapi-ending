# npmtest-hapi-ending

#### basic test coverage for  [hapi-ending (v0.9.2)](https://github.com/desirable-objects/hapi-ending#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-hapi-ending.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hapi-ending) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hapi-ending.svg)](https://travis-ci.org/npmtest/node-npmtest-hapi-ending)

#### Creates documentation of the endpoints of an application

[![NPM](https://nodei.co/npm/hapi-ending.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hapi-ending)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hapi-ending/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-ending/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-ending/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hapi-ending/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-ending/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-hapi-ending/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-hapi-ending/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hapi-ending/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hapi-ending/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hapi-ending/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hapi-ending/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-ending/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hapi-ending/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hapi-ending/build/test-report.html](https://npmtest.github.io/node-npmtest-hapi-ending/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hapi-ending/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hapi-ending/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hapi-ending/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hapi-ending/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hapi-ending/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hapi-ending/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hapi-ending/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hapi-ending/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/desirable-objects/hapi-ending/issues"
    },
    "dependencies": {
        "code": "2.1.0",
        "coveralls": "2.11.6",
        "dot-object": "^1.4.1",
        "handlebars": "4.0.5",
        "hapi": "12.1.0",
        "hoek": "^3.0.4",
        "inert": "3.2.0",
        "joi": "7.2.2",
        "lodash": "4.0.0",
        "sf": "0.1.8",
        "shortid": "2.2.4",
        "vision": "4.0.1"
    },
    "description": "Creates documentation of the endpoints of an application",
    "devDependencies": {
        "cheerio": "0.19.0",
        "jshint": "2.9.1",
        "lab": "8.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b22e2f060071600e4f897d8823bcf05f4a13c90d",
        "tarball": "https://registry.npmjs.org/hapi-ending/-/hapi-ending-0.9.2.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "d8d0fef90c65799ec62d7eaa094e439577a60ed9",
    "homepage": "https://github.com/desirable-objects/hapi-ending#readme",
    "keywords": [
        "hapi",
        "endpoints",
        "api",
        "rest",
        "documentation",
        "docs",
        "slate",
        "swagger"
    ],
    "main": "plugin.js",
    "maintainers": [
        {
            "name": "antony"
        }
    ],
    "name": "hapi-ending",
    "optionalDependencies": {},
    "publishConfig": {
        "registry": "https://registry.npmjs.org"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/desirable-objects/hapi-ending.git"
    },
    "scripts": {
        "coverage": "./node_modules/lab/bin/lab -lr lcov",
        "demo": "node test/demo.js",
        "test": "./node_modules/lab/bin/lab -l"
    },
    "version": "0.9.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
