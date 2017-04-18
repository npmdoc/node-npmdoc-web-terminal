# npmdoc-web-terminal

#### api documentation for  [web-terminal (v0.7.0)](https://github.com/rabchev/web-terminal)  [![npm package](https://img.shields.io/npm/v/npmdoc-web-terminal.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-web-terminal) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-web-terminal.svg)](https://travis-ci.org/npmdoc/node-npmdoc-web-terminal)

#### Web-Terminal is a terminal server that provides remote CLI via standard web browser and HTTP protocol.

[![NPM](https://nodei.co/npm/web-terminal.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web-terminal)

- [https://npmdoc.github.io/node-npmdoc-web-terminal/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web-terminal/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web-terminal/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web-terminal/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-web-terminal/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-web-terminal/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Boyan Rabchev"
    },
    "bin": {
        "web-terminal": "./bin/run.js"
    },
    "bugs": {
        "url": "https://github.com/rabchev/web-terminal/issues"
    },
    "config": {
        "port": "8088",
        "root": "/terminal",
        "requireSSL": "false",
        "key": "",
        "cert": "",
        "pfx": ""
    },
    "contributors": [
        {
            "name": "Boyan Rabchev"
        }
    ],
    "dependencies": {
        "authenticate-pam": "*",
        "commander": "*",
        "connect": "*",
        "lodash": "*",
        "send": "*",
        "socket.io": "*",
        "uid-number": "*"
    },
    "description": "Web-Terminal is a terminal server that provides remote CLI via standard web browser and HTTP protocol.",
    "devDependencies": {
        "nodeunit": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "a976633da64b542cdfc39ad1e1700563a67d6cc8",
        "tarball": "https://registry.npmjs.org/web-terminal/-/web-terminal-0.7.0.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "82eb0e5c0d5131c2e0214fe22ca185a584e82d3a",
    "homepage": "https://github.com/rabchev/web-terminal",
    "keywords": [
        "command",
        "shell",
        "command-line",
        "text",
        "terminal",
        "browser",
        "web",
        "node",
        "TTY",
        "JavaScript",
        "REPL"
    ],
    "license": {
        "type": "MIT",
        "url": "http://github.com/rabchev/web-terminal/blob/master/LICENSE"
    },
    "main": "index",
    "maintainers": [
        {
            "name": "rabchev"
        }
    ],
    "name": "web-terminal",
    "optionalDependencies": {
        "authenticate-pam": "*",
        "uid-number": "*"
    },
    "preferGlobal": "false",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rabchev/web-terminal.git"
    },
    "scripts": {
        "start": "node ./bin/run.js",
        "test": "node test"
    },
    "version": "0.7.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
