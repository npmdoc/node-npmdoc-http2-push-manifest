# npmdoc-http2-push-manifest

#### api documentation for  [http2-push-manifest (v1.0.1)](https://github.com/GoogleChrome/http2-push-manifest)  [![npm package](https://img.shields.io/npm/v/npmdoc-http2-push-manifest.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-http2-push-manifest) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-http2-push-manifest.svg)](https://travis-ci.org/npmdoc/node-npmdoc-http2-push-manifest)

#### Generate a list of static resources for http2 push and preload.

[![NPM](https://nodei.co/npm/http2-push-manifest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/http2-push-manifest)

- [https://npmdoc.github.io/node-npmdoc-http2-push-manifest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-http2-push-manifest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http2-push-manifest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http2-push-manifest/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-http2-push-manifest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-http2-push-manifest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "http2-push-manifest",
    "version": "1.0.1",
    "description": "Generate a list of static resources for http2 push and preload.",
    "homepage": "https://github.com/GoogleChrome/http2-push-manifest",
    "author": "Eric Bidelman <ebidel@>",
    "license": "Apache-2.0",
    "repository": {
        "type": "git",
        "url": "https://github.com/GoogleChrome/http2-push-manifest"
    },
    "bugs": {
        "url": "https://github.com/GoogleChrome/http2-push-manifest/issues"
    },
    "keywords": [
        "http2",
        "http2 push",
        "performance"
    ],
    "main": "lib/manifest.js",
    "bin": {
        "http2-push-manifest": "bin/http2-push-manifest"
    },
    "engines": {
        "node": ">=4.0"
    },
    "scripts": {
        "lint": "jshint --verbose lib",
        "test": "npm run lint; mocha"
    },
    "dependencies": {
        "dom5": "^1.1.1",
        "hydrolysis": "1.22.0",
        "nopt": "^3.0.4",
        "vulcanize": "^1.13.1"
    },
    "devDependencies": {
        "jshint": "^2.8.0",
        "mocha": "^2.3.3"
    },
    "optionalDependencies": {
        "update-notifier": "^0.5.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
