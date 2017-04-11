# test coverage for  [node-dev (v3.1.3)](https://github.com/fgnass/node-dev#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-dev.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-dev) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-dev.svg)](https://travis-ci.org/npmtest/node-npmtest-node-dev)
#### Restarts your app when files are modified

[![NPM](https://nodei.co/npm/node-dev.png?downloads=true)](https://www.npmjs.com/package/node-dev)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-dev/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-dev/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-dev/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-dev/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-dev/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-dev/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-dev/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-dev/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-node-dev/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-dev/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-node-dev%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-dev/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-dev/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-node-dev%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-dev/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-dev/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-dev/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Felix Gnass"
    },
    "bin": {
        "node-dev": "./bin/node-dev"
    },
    "bugs": {
        "url": "https://github.com/fgnass/node-dev/issues"
    },
    "contributors": [
        {
            "name": "Daniel Gasienica",
            "email": "daniel@gasienica.ch",
            "url": "https://github.com/gasi/"
        }
    ],
    "dependencies": {
        "dateformat": "~1.0.4-1.2.3",
        "dynamic-dedupe": "^0.2.0",
        "filewatcher": "~3.0.0",
        "minimist": "^1.1.3",
        "node-notifier": "^4.0.2",
        "resolve": "^1.0.0"
    },
    "description": "Restarts your app when files are modified",
    "devDependencies": {
        "coffee-script": "^1.8.0",
        "eslint": "^2.0.0",
        "eslint-config-airbnb-base": "^3.0.1",
        "eslint-plugin-import": "^1.8.1",
        "tap": "^5.2.0",
        "touch": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "582719223ebdef5d63059e6a7fbcd2399fc0f84d",
        "tarball": "https://registry.npmjs.org/node-dev/-/node-dev-3.1.3.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "55d67b0406947bf8c5e1f206d7469d55378a8655",
    "homepage": "https://github.com/fgnass/node-dev#readme",
    "keywords": [
        "restart",
        "reload",
        "supervisor",
        "monitor",
        "watch"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "fgnass",
            "email": "fgnass@gmail.com"
        },
        {
            "name": "gasi",
            "email": "daniel@gasienica.ch"
        },
        {
            "name": "tomekwi",
            "email": "t.wiszniewski@gmail.com"
        }
    ],
    "name": "node-dev",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/fgnass/node-dev.git"
    },
    "scripts": {
        "test": "tap test/*.js"
    },
    "version": "3.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
