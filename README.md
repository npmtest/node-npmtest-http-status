# npmtest-http-status

#### basic test coverage for  [http-status (v1.0.1)](http://www.adaltas.com/projects/node-http-status)  [![npm package](https://img.shields.io/npm/v/npmtest-http-status.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-http-status) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-http-status.svg)](https://travis-ci.org/npmtest/node-npmtest-http-status)

#### Interact with HTTP status code

[![NPM](https://nodei.co/npm/http-status.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/http-status)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-http-status/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-status/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-http-status/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-http-status/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-http-status/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-http-status/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-http-status/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-http-status/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-http-status/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-http-status/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-http-status/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-status/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-http-status/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-http-status/build/test-report.html](https://npmtest.github.io/node-npmtest-http-status/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-http-status/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-http-status/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-http-status/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-http-status/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-status/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-status/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-http-status/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-http-status/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Worms"
    },
    "bugs": {
        "url": "http://github.com/wdavidw/node-http-status/issues"
    },
    "contributors": [
        {
            "name": "David Worms"
        },
        {
            "name": "Daniel Gasienica"
        }
    ],
    "dependencies": {},
    "description": "Interact with HTTP status code",
    "devDependencies": {
        "coffee-script": "latest",
        "mocha": "latest",
        "should": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "dc43001a8bfc50ac87d485a892f7578964bc94a2",
        "tarball": "https://registry.npmjs.org/http-status/-/http-status-1.0.1.tgz"
    },
    "engines": {
        "node": ">= 0.4.0"
    },
    "gitHead": "ffc8111f5a427860ed2ee67066bfd8347328b35d",
    "homepage": "http://www.adaltas.com/projects/node-http-status",
    "keywords": [
        "http",
        "express",
        "connect"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "david"
        }
    ],
    "name": "http-status",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wdavidw/node-http-status.git"
    },
    "scripts": {
        "coffee": "coffee -b -o lib src",
        "test": "NODE_ENV=test node_modules/.bin/mocha --compilers coffee:coffee-script/register --reporter dot"
    },
    "version": "1.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
