# npmtest-inotify

#### basic test coverage for  [inotify (v1.4.1)](https://github.com/c4milo/node-inotify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-inotify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-inotify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-inotify.svg)](https://travis-ci.org/npmtest/node-npmtest-inotify)

#### inotify bindings for v8 javascript engine

[![NPM](https://nodei.co/npm/inotify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inotify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-inotify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-inotify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-inotify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-inotify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-inotify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-inotify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-inotify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-inotify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-inotify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-inotify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-inotify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-inotify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-inotify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-inotify/build/test-report.html](https://npmtest.github.io/node-npmtest-inotify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-inotify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-inotify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-inotify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inotify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inotify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inotify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-inotify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-inotify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Camilo Aguilar"
    },
    "bugs": {
        "url": "https://github.com/c4milo/node-inotify/issues"
    },
    "contributors": [
        {
            "name": "Adrian Estrada"
        },
        {
            "name": "Alexander Makarenko"
        },
        {
            "name": "Brian Ingalls"
        },
        {
            "name": "Brian White"
        },
        {
            "name": "Camilo Aguilar"
        },
        {
            "name": "Dan VerWeire"
        },
        {
            "name": "FrozenCow"
        },
        {
            "name": "Michael Boe"
        },
        {
            "name": "Yannick Croissant"
        },
        {
            "name": "ikokostya"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.3"
    },
    "description": "inotify bindings for v8 javascript engine",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "8abdeb7ee9cbc291542a252df00d848b2a8f9287",
        "tarball": "https://registry.npmjs.org/inotify/-/inotify-1.4.1.tgz"
    },
    "email": "camilo.aguilar@gmail.com",
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "c1416dfada3ca4f3fb40e65eededc52461822ec5",
    "gypfile": true,
    "homepage": "https://github.com/c4milo/node-inotify#readme",
    "keywords": [
        "inotify",
        "watch",
        "monitor",
        "watch files",
        "watch directories"
    ],
    "license": "MIT",
    "main": "inotify",
    "maintainers": [
        {
            "name": "camilo"
        },
        {
            "name": "c4milo"
        }
    ],
    "name": "inotify",
    "optionalDependencies": {},
    "os": [
        "linux"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/c4milo/node-inotify.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node-gyp configure build"
    },
    "version": "1.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
