# npmdoc-node-vibrant

#### api documentation for  node-vibrant (v3.0.0-alpha.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-vibrant.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-vibrant) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-vibrant.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-vibrant)

#### Extract prominent colors from an image. Supports both node and browser environment.

[![NPM](https://nodei.co/npm/node-vibrant.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-vibrant)

- [https://npmdoc.github.io/node-npmdoc-node-vibrant/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-vibrant",
    "version": "3.0.0-alpha.2",
    "description": "Extract prominent colors from an image. Supports both node and browser environment.",
    "main": "lib/index.js",
    "browser": "lib/browser.js",
    "types": "lib/index.d.ts",
    "directories": {
        "example": "examples"
    },
    "dependencies": {
        "@types/bluebird": "^3.0.37",
        "@types/jimp": "^0.2.0",
        "@types/lodash": "^4.14.53",
        "@types/node": "^7.0.5",
        "bluebird": "^3.4.7",
        "jimp": "^0.2.27",
        "lodash": "^4.17.4",
        "url": "^0.11.0"
    },
    "devDependencies": {
        "@types/chai": "^3.4.35",
        "@types/finalhandler": "0.0.31",
        "@types/mocha": "^2.2.39",
        "@types/serve-static": "^1.7.31",
        "@types/table": "^4.0.1",
        "chai": "^3.5.0",
        "finalhandler": "^1.0.0",
        "karma": "^1.5.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-commonjs": "^1.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-webpack": "^2.0.2",
        "mocha": "^3.2.0",
        "rimraf": "^2.6.1",
        "serve-static": "^1.11.2",
        "table": "^4.0.1",
        "ts-loader": "^2.0.1",
        "typescript": "^2.2.1",
        "webpack": "^2.2.1"
    },
    "scripts": {
        "clean": "npm run clean:browser && npm run clean:node",
        "clean:browser": "./node_modules/.bin/rimraf dist",
        "clean:node": "./node_modules/.bin/rimraf lib",
        "build": "npm run build:browser && npm run build:node",
        "build:browser": "./node_modules/.bin/webpack --config webpack.config.js",
        "build:node": "./node_modules/.bin/tsc",
        "pretest": "npm run clean && npm run build",
        "test": "npm run test:node && npm run test:browser",
        "test:node": "./node_modules/.bin/mocha lib/test/**/*.spec.js",
        "test:browser": "./node_modules/.bin/karma start karma.conf.js",
        "prepublish": "npm run clean && npm run build"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/akfish/node-vibrant.git"
    },
    "keywords": [
        "color",
        "detection",
        "varation",
        "image",
        "picture",
        "canvas",
        "vibrant",
        "muted",
        "colour"
    ],
    "author": "akfish",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
