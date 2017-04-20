# npmtest-grunt-node-inspector

#### basic test coverage for  grunt-node-inspector (v0.4.2)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-node-inspector.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-node-inspector) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-node-inspector.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-node-inspector)

#### Run node-inspector with the rest of your workflow to debug node.js

[![NPM](https://nodei.co/npm/grunt-node-inspector.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-node-inspector)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-node-inspector/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-node-inspector/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-node-inspector/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-node-inspector/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-node-inspector/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-node-inspector/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-node-inspector/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-node-inspector/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-node-inspector",
    "version": "0.4.2",
    "description": "Run node-inspector with the rest of your workflow to debug node.js",
    "main": "tasks/inspector.js",
    "scripts": {
        "test": "grunt test"
    },
    "keywords": [
        "node-inspector",
        "gruntplugin",
        "grunt",
        "debug"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/ChrisWren/grunt-node-inspector.git"
    },
    "author": "ChrisWren",
    "license": "MIT",
    "devDependencies": {
        "grunt": ">=0.4.0",
        "grunt-release": "^0.13.1",
        "grunt-contrib-jshint": "^1.0.0",
        "matchdep": "^1.0.1",
        "should": "^9.0.0",
        "grunt-simple-mocha": "^0.4.1",
        "win-spawn": "^2.0.0"
    },
    "dependencies": {
        "node-inspector": "^0.12.8"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
