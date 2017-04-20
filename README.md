# npmdoc-licensor

#### api documentation for  [licensor (v3.1.0)](http://jslicense.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-licensor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-licensor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-licensor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-licensor)

#### generate LICENSE and related files from package.json

[![NPM](https://nodei.co/npm/licensor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/licensor)

- [https://npmdoc.github.io/node-npmdoc-licensor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-licensor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-licensor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-licensor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-licensor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-licensor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "licensor",
    "description": "generate LICENSE and related files from package.json",
    "version": "3.1.0",
    "author": "Kyle E. Mitchell <kyle@kemitchell.com> (https://kemitchell.com)",
    "bin": "./licensor",
    "dependencies": {
        "apache-2.0": "^1.0.7",
        "glob": "^6.0.4",
        "gpl-3.0": "^1.0.1",
        "jslicense-0bsd": "^0.1.0",
        "jslicense-bsd-2-clause": "^0.1.0",
        "jslicense-bsd-3-clause": "^0.1.0",
        "jslicense-isc": "^0.1.0",
        "jslicense-mit": "^0.1.0",
        "jslicense-upl-1.0": "^1.0.2",
        "jslicense-wtfpl": "^0.1.0",
        "nopt": "^3.0.6",
        "normalize-package-data": "^2.1.0",
        "word-wrap": "^1.1.0"
    },
    "devDependencies": {
        "standard": "^8.4.0",
        "tap": "^5.1.2"
    },
    "files": [
        "LICENSE",
        "NOTICE",
        "README.md",
        "licensor"
    ],
    "homepage": "http://jslicense.org",
    "keywords": [
        "SPDX",
        "law",
        "legal",
        "license",
        "metadata",
        "package"
    ],
    "license": "Apache-2.0",
    "repository": "jslicense/licensor.js",
    "scripts": {
        "test": "tap tests/**/test.js",
        "lint": "standard"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
