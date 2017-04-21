# npmtest-mv

#### basic test coverage for  [mv (v2.1.1)](https://github.com/andrewrk/node-mv)  [![npm package](https://img.shields.io/npm/v/npmtest-mv.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mv) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mv.svg)](https://travis-ci.org/npmtest/node-npmtest-mv)

#### fs.rename but works across devices. same as the unix utility 'mv'

[![NPM](https://nodei.co/npm/mv.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mv)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mv/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mv/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mv/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mv/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mv/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mv/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mv/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mv/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mv/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mv/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mv/build/test-report.html](https://npmtest.github.io/node-npmtest-mv/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mv/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mv/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mv/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mv/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mv/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mv/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mv/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrew Kelley"
    },
    "bugs": {
        "url": "https://github.com/andrewrk/node-mv/issues"
    },
    "dependencies": {
        "mkdirp": "~0.5.1",
        "ncp": "~2.0.0",
        "rimraf": "~2.4.0"
    },
    "description": "fs.rename but works across devices. same as the unix utility 'mv'",
    "devDependencies": {
        "mocha": "~2.2.5"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "ae6ce0d6f6d5e0a4f7d893798d03c1ea9559b6a2",
        "tarball": "https://registry.npmjs.org/mv/-/mv-2.1.1.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "645d8f4c783abf84204be704098fdd41f36ab195",
    "homepage": "https://github.com/andrewrk/node-mv",
    "keywords": [
        "mv",
        "move",
        "rename",
        "device",
        "recursive",
        "folder"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "superjoe"
        }
    ],
    "name": "mv",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/andrewrk/node-mv.git"
    },
    "scripts": {
        "test": "mocha test/test.js --reporter spec"
    },
    "version": "2.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
