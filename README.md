# api documentation for  [jscoverage (v0.6.0)](https://github.com/fishbar/jscoverage)  [![npm package](https://img.shields.io/npm/v/npmdoc-jscoverage.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jscoverage) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jscoverage.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jscoverage)
#### a javascript coverage tool, can be used in node dev, and browser side js dev

[![NPM](https://nodei.co/npm/jscoverage.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jscoverage)

- [https://npmdoc.github.io/node-npmdoc-jscoverage/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jscoverage/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jscoverage/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jscoverage/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jscoverage/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jscoverage/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "fish"
    },
    "bin": {
        "jscoverage": "./bin/jscoverage"
    },
    "bugs": {
        "url": "https://github.com/fishbar/jscoverage/issues"
    },
    "contributors": [
        {
            "name": "christineRR"
        }
    ],
    "dependencies": {
        "coffee-script": "*",
        "commander": "^2.6.0",
        "debug": "~1.0.3",
        "ejs": "1.0.0",
        "optimist": "^0.6.1",
        "uglify-js": "~2.4.15",
        "xfs": "~0.1.8"
    },
    "description": "a javascript coverage tool, can be used in node dev, and browser side js dev",
    "devDependencies": {
        "expect.js": "*",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "f5e13a9e13776338768c1ee02e1ae71d515cdac9",
        "tarball": "https://registry.npmjs.org/jscoverage/-/jscoverage-0.6.0.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "5e77cc662f0cd8e9e136e25ec10441e5d11edbff",
    "homepage": "https://github.com/fishbar/jscoverage",
    "keywords": [
        "jscoverage",
        "node",
        "javascript",
        "coverage",
        "dev",
        "tool"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "kate.sf"
        },
        {
            "name": "fish"
        },
        {
            "name": "sunfang1cn"
        },
        {
            "name": "fishbar"
        }
    ],
    "name": "jscoverage",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/fishbar/jscoverage.git"
    },
    "scripts": {
        "test": "./node_modules/mocha/bin/_mocha -t 60000 -r ./index.js -R spec --covinject true test/"
    },
    "version": "0.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
