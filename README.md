# npmdoc-each

#### api documentation for  [each (v0.6.1)](http://www.adaltas.com/projects/node-each/)  [![npm package](https://img.shields.io/npm/v/npmdoc-each.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-each) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-each.svg)](https://travis-ci.org/npmdoc/node-npmdoc-each)

#### Chained and parallel async iterator in one elegant function

[![NPM](https://nodei.co/npm/each.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/each)

- [https://npmdoc.github.io/node-npmdoc-each/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-each/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-each/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-each/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-each/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-each/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "each",
    "version": "0.6.1",
    "description": "Chained and parallel async iterator in one elegant function",
    "homepage": "http://www.adaltas.com/projects/node-each/",
    "author": "David Worms <david@adaltas.com>",
    "license": "BSD-3-Clause",
    "contributors": [
        {
            "name": "David Worms"
        }
    ],
    "dependencies": {
        "glob": "~7.0.0"
    },
    "devDependencies": {
        "coffee-script": "1.10.0",
        "should": "~8.3.1",
        "mocha": "~2.4.5"
    },
    "engines": {
        "node": ">= 0.9.0"
    },
    "main": "./lib/index",
    "keywords": [
        "control flow",
        "asynchronous",
        "array",
        "object",
        "each"
    ],
    "repository": {
        "type": "git",
        "url": "https://github.com/wdavidw/node-each.git"
    },
    "scripts": {
        "coffee": "./node_modules/.bin/coffee -b -o lib src",
        "pretest": "./node_modules/.bin/coffee -b -o lib src",
        "test": "NODE_ENV=test ./node_modules/.bin/mocha --compilers coffee:coffee-script/register --reporter dot"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
