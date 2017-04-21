# npmdoc-goo.gl

#### api documentation for  [goo.gl (v0.1.4)](https://github.com/kaimallea/node-googl)  [![npm package](https://img.shields.io/npm/v/npmdoc-goo.gl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-goo.gl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-goo.gl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-goo.gl)

#### A url shortener and expander powered by Google's URL shortening service

[![NPM](https://nodei.co/npm/goo.gl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/goo.gl)

- [https://npmdoc.github.io/node-npmdoc-goo.gl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-goo.gl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-goo.gl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-goo.gl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-goo.gl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-goo.gl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "Kai Mallea <kmallea@gmail.com>",
    "name": "goo.gl",
    "description": "A url shortener and expander powered by Google's URL shortening service",
    "version": "0.1.4",
    "homepage": "https://github.com/kaimallea/node-googl",
    "keywords": [
        "google",
        "googl",
        "goo.gl",
        "url",
        "urls",
        "short",
        "shorten",
        "shortener",
        "expander"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/kaimallea/node-googl.git"
    },
    "engines": {
        "node": ">= v0.10.20"
    },
    "dependencies": {
        "request": "~2.40.0",
        "commander": "~2.2.0",
        "q": "~1.0.1"
    },
    "main": "lib/googl.js",
    "bin": {
        "goo.gl": "./cli.js"
    },
    "scripts": {
        "test": "node_modules/.bin/mocha"
    },
    "devDependencies": {
        "mocha": "~1.18.2",
        "chai": "~1.9.1",
        "chai-as-promised": "~4.1.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
