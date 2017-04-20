# npmdoc-browser-repl

#### api documentation for  browser-repl (v0.4.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-browser-repl.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-browser-repl) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-browser-repl.svg)](https://travis-ci.org/npmdoc/node-npmdoc-browser-repl)

#### CLI utility to set up a remote browser repl

[![NPM](https://nodei.co/npm/browser-repl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/browser-repl)

- [https://npmdoc.github.io/node-npmdoc-browser-repl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-browser-repl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-browser-repl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-browser-repl/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-browser-repl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-browser-repl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "browser-repl",
    "version": "0.4.0",
    "description": "CLI utility to set up a remote browser repl",
    "dependencies": {
        "array-map": "0.0.0",
        "express": "3.4.8",
        "foreach": "2.0.4",
        "minimist": "0.0.7",
        "ngrok": "0.1.99",
        "socket.io": "1.3.5",
        "socket.io-client": "1.3.5",
        "to-array": "0.1.4",
        "util-inspect": "0.1.8",
        "wd": "0.3.11"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/Automattic/browser-repl.git"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/Automattic/browser-repl/issues"
    },
    "bin": {
        "repl": "./repl.js"
    },
    "scripts": {
        "prepublish": "make build"
    },
    "devDependencies": {
        "browserify": "8.1.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
