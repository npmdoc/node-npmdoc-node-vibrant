# api documentation for  [node-vibrant (v2.1.2)](https://github.com/akfish/node-vibrant#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-vibrant.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-vibrant) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-vibrant.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-vibrant)
#### Node.js port of vibrant.js. Get color variations from an image. Basically a JS port of Android's Palette

[![NPM](https://nodei.co/npm/node-vibrant.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-vibrant)

- [https://npmdoc.github.io/node-npmdoc-node-vibrant/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-vibrant/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "akfish"
    },
    "browser": "lib/browser.js",
    "bugs": {
        "url": "https://github.com/akfish/node-vibrant/issues"
    },
    "dependencies": {
        "jimp": "^0.2.4",
        "quantize": "^1.0.1",
        "url": "^0.11.0"
    },
    "description": "Node.js port of vibrant.js. Get color variations from an image. Basically a JS port of Android's Palette",
    "devDependencies": {
        "bluebird": "^2.10.2",
        "browserify": "^10.2.4",
        "chai": "^3.0.0",
        "cli-table": "^0.3.1",
        "coffee-script": "^1.9.3",
        "coffeeify": "^1.1.0",
        "colors": "^1.1.2",
        "del": "^2.2.0",
        "finalhandler": "^0.4.0",
        "gulp": "^3.9.0",
        "gulp-bench": "^1.1.0",
        "gulp-coffee": "^2.3.1",
        "gulp-heap": "^2.0.0-alpha.1",
        "gulp-mocha": "^2.2.0",
        "gulp-uglify": "^1.2.0",
        "karma": "^0.13.14",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^0.2.1",
        "karma-coffee-preprocessor": "^0.3.0",
        "karma-firefox-launcher": "^0.1.6",
        "karma-ie-launcher": "^0.2.0",
        "karma-json-fixtures-preprocessor": "0.0.5",
        "karma-mocha": "^0.2.0",
        "mocha": "^2.3.3",
        "serve-static": "^1.10.0",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {
        "example": "examples"
    },
    "dist": {
        "shasum": "741fc2584c411650506e4f98c32e046638a2c08e",
        "tarball": "https://registry.npmjs.org/node-vibrant/-/node-vibrant-2.1.2.tgz"
    },
    "gitHead": "89ffaf0b34d2200b836cc21f2ae143a47ab4fce3",
    "homepage": "https://github.com/akfish/node-vibrant#readme",
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
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "akfish"
        }
    ],
    "name": "node-vibrant",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/akfish/node-vibrant.git"
    },
    "scripts": {
        "prepublish": "gulp clean && gulp clean:browser && gulp coffee && gulp browser",
        "pretest": "gulp coffee && gulp browser",
        "test": "gulp test"
    },
    "version": "2.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
