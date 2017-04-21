# npmtest-shipit-deploy

#### basic test coverage for  [shipit-deploy (v2.4.0)](https://github.com/shipitjs/shipit-deploy)  [![npm package](https://img.shields.io/npm/v/npmtest-shipit-deploy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shipit-deploy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shipit-deploy.svg)](https://travis-ci.org/npmtest/node-npmtest-shipit-deploy)

#### Set of deployment tasks for Shipit based on git and rsync commands.

[![NPM](https://nodei.co/npm/shipit-deploy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shipit-deploy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shipit-deploy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shipit-deploy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shipit-deploy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shipit-deploy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shipit-deploy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shipit-deploy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shipit-deploy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shipit-deploy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shipit-deploy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shipit-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shipit-deploy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shipit-deploy/build/test-report.html](https://npmtest.github.io/node-npmtest-shipit-deploy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shipit-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shipit-deploy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shipit-deploy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shipit-deploy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shipit-deploy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "shipit-deploy",
    "version": "2.4.0",
    "description": "Set of deployment tasks for Shipit based on git and rsync commands. ",
    "main": "index.js",
    "directories": {
        "test": "test"
    },
    "files": [
        "index.js",
        "tasks",
        "lib"
    ],
    "scripts": {
        "test": "mocha --recursive"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/shipitjs/shipit-deploy.git"
    },
    "keywords": [
        "shipit",
        "deploy",
        "task"
    ],
    "author": "Greg Bergé <berge.greg@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/shipitjs/shipit-deploy/issues"
    },
    "homepage": "https://github.com/shipitjs/shipit-deploy",
    "devDependencies": {
        "chai": "^3.4.1",
        "mocha": "^2.1.0",
        "rewire": "^2.1.4",
        "shipit-cli": "^1.4.1",
        "sinon": "^1.12.2",
        "sinon-as-promised": "^4.0.0",
        "sinon-chai": "^2.7.0"
    },
    "dependencies": {
        "bluebird": "^3.0.6",
        "chalk": "^1.0.0",
        "lodash": "^4.6.1",
        "mkdirp": "^0.5.0",
        "moment": "^2.12.0",
        "path2": "^0.1.0",
        "shipit-utils": "^1.1.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
