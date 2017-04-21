# npmtest-express-redirect

#### basic test coverage for  express-redirect (v1.2.2)  [![npm package](https://img.shields.io/npm/v/npmtest-express-redirect.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-redirect) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-redirect.svg)](https://travis-ci.org/npmtest/node-npmtest-express-redirect)

#### Flexible redirection plugin

[![NPM](https://nodei.co/npm/express-redirect.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-redirect)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-redirect/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-redirect/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-redirect/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-redirect/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-redirect/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-redirect/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-redirect/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-redirect/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-redirect/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-redirect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-redirect/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-redirect/build/test-report.html](https://npmtest.github.io/node-npmtest-express-redirect/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-redirect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-redirect/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-redirect/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-redirect/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-redirect/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-redirect/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-redirect/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-redirect/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-redirect",
    "description": "Flexible redirection plugin",
    "version": "1.2.2",
    "author": "Jan Buschtöns <buschtoens@gmail.com>",
    "contributors": [
        {
            "name": "Jan Buschtöns",
            "url": "https://github.com/buschtoens"
        }
    ],
    "license": "MIT",
    "keywords": [
        "express",
        "express-plugin",
        "connect",
        "redirect",
        "redirection",
        "rewrite",
        "middleware",
        "plugin"
    ],
    "repository": "git://github.com/buschtoens/express-redirect",
    "main": "index",
    "engines": {
        "node": "*"
    },
    "scripts": {
        "prepublish": "npm prune",
        "test": "mocha -R spec -r should"
    },
    "dependencies": {
        "sanitize-arguments": "~2.0"
    },
    "devDependencies": {
        "mocha": "~1.7.3",
        "should": "~1.2.1",
        "express": "~3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
