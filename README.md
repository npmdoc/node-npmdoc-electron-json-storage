# npmdoc-electron-json-storage

#### api documentation for  [electron-json-storage (v3.0.5)](https://github.com/jviotti/electron-json-storage)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-json-storage.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-json-storage) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-json-storage.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-json-storage)

#### Easily write and read user settings in Electron apps

[![NPM](https://nodei.co/npm/electron-json-storage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron-json-storage)

- [https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juan Cruz Viotti"
    },
    "bugs": {
        "url": "https://github.com/jviotti/electron-json-storage/issues"
    },
    "dependencies": {
        "async": "^2.0.0",
        "lodash": "^4.0.1",
        "mkdirp": "^0.5.1",
        "rimraf": "^2.5.1"
    },
    "description": "Easily write and read user settings in Electron apps",
    "devDependencies": {
        "electron-mocha": "^3.3.0",
        "electron-prebuilt": "^1.2.7",
        "jsdoc-to-markdown": "^2.0.1",
        "jshint": "^2.9.1",
        "mochainon": "^1.0.0",
        "tmp": "0.0.31"
    },
    "directories": {
        "test": "tests"
    },
    "dist": {
        "shasum": "51702d2c25dc5c752c8d4ca50412ee80a57683a4",
        "tarball": "https://registry.npmjs.org/electron-json-storage/-/electron-json-storage-3.0.5.tgz"
    },
    "gitHead": "60a34b5915fd3ea6edbd5394f2455ab549f1b8d5",
    "homepage": "https://github.com/jviotti/electron-json-storage",
    "keywords": [
        "electron",
        "json",
        "storage",
        "user",
        "app",
        "data"
    ],
    "license": "MIT",
    "main": "lib/storage.js",
    "maintainers": [
        {
            "name": "jviotti"
        }
    ],
    "name": "electron-json-storage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jviotti/electron-json-storage.git"
    },
    "scripts": {
        "lint": "jshint --config .jshintrc --reporter unix lib tests",
        "readme": "jsdoc2md --template doc/README.hbs lib/storage.js > README.md",
        "test": "electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec"
    },
    "version": "3.0.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
