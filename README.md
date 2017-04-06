# api documentation for  [electron-json-storage (v3.0.4)](https://github.com/jviotti/electron-json-storage)  [![npm package](https://img.shields.io/npm/v/npmdoc-electron-json-storage.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-electron-json-storage) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-electron-json-storage.svg)](https://travis-ci.org/npmdoc/node-npmdoc-electron-json-storage)
#### Easily write and read user settings in Electron apps

[![NPM](https://nodei.co/npm/electron-json-storage.png?downloads=true)](https://www.npmjs.com/package/electron-json-storage)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-electron-json-storage_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-electron-json-storage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Juan Cruz Viotti",
        "email": "jviottidc@gmail.com"
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
        "shasum": "3b4e3e95e979eb1743edf55174f8daf69416c6fd",
        "tarball": "https://registry.npmjs.org/electron-json-storage/-/electron-json-storage-3.0.4.tgz"
    },
    "gitHead": "84ae376b4ce0026dc2690a5342f1358628c5f635",
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
            "name": "jviotti",
            "email": "jviottidc@gmail.com"
        }
    ],
    "name": "electron-json-storage",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/jviotti/electron-json-storage.git"
    },
    "scripts": {
        "lint": "jshint --config .jshintrc --reporter unix lib tests",
        "readme": "jsdoc2md --template doc/README.hbs lib/storage.js > README.md",
        "test": "electron-mocha --recursive tests -R spec && electron-mocha --renderer --recursive tests -R spec"
    },
    "version": "3.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module electron-json-storage](#apidoc.module.electron-json-storage)



# <a name="apidoc.module.electron-json-storage"></a>[module electron-json-storage](#apidoc.module.electron-json-storage)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
