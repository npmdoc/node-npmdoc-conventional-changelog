# npmdoc-conventional-changelog

#### api documentation for  [conventional-changelog (v1.1.3)](https://github.com/conventional-changelog/conventional-changelog#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-conventional-changelog.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-conventional-changelog) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-conventional-changelog.svg)](https://travis-ci.org/npmdoc/node-npmdoc-conventional-changelog)

#### Generate a changelog from git metadata

[![NPM](https://nodei.co/npm/conventional-changelog.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/conventional-changelog)

- [https://npmdoc.github.io/node-npmdoc-conventional-changelog/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-conventional-changelog/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-conventional-changelog/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-conventional-changelog/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-conventional-changelog/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-conventional-changelog/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/conventional-changelog/conventional-changelog/issues"
    },
    "contributors": [
        {
            "name": "Brian Ford"
        },
        {
            "name": "Vojta Jína"
        },
        {
            "name": "Andrew Joslin"
        }
    ],
    "dependencies": {
        "conventional-changelog-angular": "^1.3.3",
        "conventional-changelog-atom": "^0.1.0",
        "conventional-changelog-codemirror": "^0.1.0",
        "conventional-changelog-core": "^1.8.0",
        "conventional-changelog-ember": "^0.2.5",
        "conventional-changelog-eslint": "^0.1.0",
        "conventional-changelog-express": "^0.1.0",
        "conventional-changelog-jquery": "^0.1.0",
        "conventional-changelog-jscs": "^0.1.0",
        "conventional-changelog-jshint": "^0.1.0"
    },
    "description": "Generate a changelog from git metadata",
    "devDependencies": {
        "chai": "^3.0.0",
        "concat-stream": "^1.4.10",
        "jscs": "^2.0.0",
        "jshint": "^2.8.0",
        "mocha": "*",
        "shelljs": "^0.6.0",
        "through2": "^2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "26283078ac38c094df2af1604b0a46bbc0165c4d",
        "tarball": "https://registry.npmjs.org/conventional-changelog/-/conventional-changelog-1.1.3.tgz"
    },
    "homepage": "https://github.com/conventional-changelog/conventional-changelog#readme",
    "keywords": [
        "conventional-changelog",
        "conventional",
        "changelog",
        "log"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "andytjoslin"
        },
        {
            "name": "bcoe"
        },
        {
            "name": "stevemao"
        }
    ],
    "name": "conventional-changelog",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/conventional-changelog/conventional-changelog.git"
    },
    "scripts": {
        "lint": "jshint test *.js --exclude node_modules && jscs test *.js",
        "test": "npm run-script lint && mocha --timeout 30000",
        "test-windows": "mocha --timeout 30000"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
