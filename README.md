# npmdoc-node-craigslist

#### api documentation for  node-craigslist (v1.1.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-craigslist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-craigslist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-craigslist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-craigslist)

#### a client library for searching, retrieving and creating Craigslist.com listings

[![NPM](https://nodei.co/npm/node-craigslist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-craigslist)

- [https://npmdoc.github.io/node-npmdoc-node-craigslist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-craigslist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-craigslist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-craigslist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-craigslist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-craigslist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-craigslist",
    "description": "a client library for searching, retrieving and creating Craigslist.com listings",
    "private": false,
    "version": "1.1.1",
    "author": "Joshua Thomas (http://github.com/brozeph)",
    "engine": "node >= 4",
    "keywords": [
        "craigslist",
        "search"
    ],
    "repository": {
        "type": "git",
        "url": "ssh://git@github.org:brozeph/node-craigslist.git"
    },
    "main": "./dist",
    "scripts": {
        "prepublish": "gulp build",
        "test": "gulp lint && gulp test-integration && gulp test-coverage"
    },
    "dependencies": {
        "babel-polyfill": "^6.13.0",
        "cheerio": "^0.20.0",
        "debug": "^2.2.0",
        "source-map-support": "^0.4.2"
    },
    "devDependencies": {
        "babel-eslint": "^6.1.2",
        "babel-preset-es2015": "^6.13.2",
        "babel-preset-stage-0": "^6.5.0",
        "chai": "^3.5.0",
        "del": "^2.2.1",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-coveralls": "^0.1.4",
        "gulp-eslint": "^3.0.1",
        "gulp-istanbul": "^1.0.0",
        "gulp-mocha": "^3.0.0",
        "gulp-sourcemaps": "^1.6.0",
        "gulp-util": "^3.0.7",
        "nock": "^8.0.0"
    },
    "directories": {
        "test": "test"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
