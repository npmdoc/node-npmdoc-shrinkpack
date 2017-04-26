# npmdoc-shrinkpack

#### basic api documentation for  [shrinkpack (v0.18.1)](https://github.com/JamieMason/shrinkpack)  [![npm package](https://img.shields.io/npm/v/npmdoc-shrinkpack.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-shrinkpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-shrinkpack.svg)](https://travis-ci.org/npmdoc/node-npmdoc-shrinkpack)

#### Fast, resilient, reproducible builds with npm install.

[![NPM](https://nodei.co/npm/shrinkpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shrinkpack)

- [https://npmdoc.github.io/node-npmdoc-shrinkpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shrinkpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shrinkpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shrinkpack/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-shrinkpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-shrinkpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jamie Mason",
        "url": "https://github.com/JamieMason"
    },
    "ava": {
        "files": [
            "test/e2e/test.js"
        ]
    },
    "bin": {
        "shrinkpack": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/JamieMason/shrinkpack/issues"
    },
    "config": {
        "commitizen": {
            "path": "./node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Andrew Levine",
            "url": "https://github.com/DrewML"
        },
        {
            "name": "Chris Wheatley",
            "url": "https://github.com/swirlycheetah"
        },
        {
            "name": "David Cook",
            "url": "https://github.com/divergentdave"
        },
        {
            "name": "Dmytro Tolstyi",
            "url": "https://github.com/GitAngel"
        },
        {
            "name": "Dylan Piercey",
            "url": "https://github.com/DylanPiercey"
        },
        {
            "name": "Emil Sågfors",
            "url": "https://github.com/lime"
        },
        {
            "name": "Jason Hewison",
            "url": "https://github.com/ChunkySamurai"
        },
        {
            "name": "Kirill Fomichev",
            "url": "https://github.com/fanatid"
        },
        {
            "name": "Mark Erikson",
            "url": "https://github.com/markerikson"
        },
        {
            "name": "Scott Sidwell",
            "url": "https://github.com/5id"
        },
        {
            "name": "Zlatan Vasović",
            "url": "https://github.com/zdroid"
        }
    ],
    "dependencies": {
        "chalk": "1.1.3",
        "commander": "2.9.0",
        "execa": "0.5.0",
        "graceful-fs": "4.1.11",
        "gunzip-maybe": "1.3.1",
        "lodash.assign": "4.2.0",
        "when": "3.7.7"
    },
    "description": "Fast, resilient, reproducible builds with npm install.",
    "devDependencies": {
        "ava": "0.17.0",
        "commit-release": "0.6.2",
        "cz-conventional-changelog": "1.2.0",
        "husky": "0.12.0",
        "rimraf": "2.5.4",
        "validate-commit-msg": "2.8.2",
        "xo": "0.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "be220959997e4a45441181a1f048ed0075c8f536",
        "tarball": "https://registry.npmjs.org/shrinkpack/-/shrinkpack-0.18.1.tgz"
    },
    "engines": {
        "node": ">=4.0",
        "npm": "<3.8.8 || >3.10.3"
    },
    "files": [
        "cli.js",
        "index.js",
        "src"
    ],
    "gitHead": "5cc246966d5e4638782151b99a6dd2c400ef6e54",
    "homepage": "https://github.com/JamieMason/shrinkpack",
    "keywords": [
        "bundle",
        "cache",
        "deploy",
        "deployments",
        "import",
        "install",
        "npm",
        "offline",
        "package",
        "save",
        "shrinkwrap"
    ],
    "license": "MIT",
    "main": "shrinkpack",
    "maintainers": [
        {
            "name": "fold_left"
        }
    ],
    "name": "shrinkpack",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jamiemason/shrinkpack.git"
    },
    "scripts": {
        "commit-release": "commit-release",
        "commitmsg": "validate-commit-msg",
        "lint": "xo --fix",
        "precommit": "npm run lint",
        "test": "ava"
    },
    "version": "0.18.1",
    "xo": {
        "envs": [
            "node"
        ],
        "esnext": false,
        "space": 2
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
