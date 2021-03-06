# npmdoc-express-status-monitor

#### basic api documentation for  [express-status-monitor (v0.1.9)](https://github.com/RafalWilinski/express-status-monitor#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-status-monitor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-status-monitor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-status-monitor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-status-monitor)

#### Realtime Monitoring for Express-based Node applications

[![NPM](https://nodei.co/npm/express-status-monitor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-status-monitor)

- [https://npmdoc.github.io/node-npmdoc-express-status-monitor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-status-monitor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-status-monitor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-status-monitor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-status-monitor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-status-monitor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rafal Wilinski",
        "url": "http://rwilinski.me"
    },
    "bugs": {
        "url": "https://github.com/RafalWilinski/express-status-monitor/issues"
    },
    "contributors": [
        {
            "name": "Julien Breux",
            "url": "https://github.com/JulienBreux/"
        },
        {
            "name": "Ferdinand Mütsch",
            "url": "https://github.com/n1try/"
        },
        {
            "name": "Mattia Richetto",
            "url": "https://github.com/mattiaerre"
        },
        {
            "name": "Jiri Spac",
            "url": "https://github.com/capaj/"
        }
    ],
    "dependencies": {
        "on-headers": "^1.0.1",
        "pidusage": "^1.1.0",
        "socket.io": "^1.5.1"
    },
    "description": "Realtime Monitoring for Express-based Node applications",
    "devDependencies": {
        "bithound": "^1.7.0",
        "chai": "^3.5.0",
        "eslint": "^3.12.2",
        "istanbul": "^0.4.5",
        "mocha": "^3.0.2",
        "sinon": "^1.17.5",
        "snyk": "^1.19.1"
    },
    "directories": {},
    "dist": {
        "shasum": "dd505c7ca4aba5022b633af1a21afc9fe4c52db5",
        "tarball": "https://registry.npmjs.org/express-status-monitor/-/express-status-monitor-0.1.9.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "7652f891667eca1e4056bc96bc6e9c37ee34af58",
    "homepage": "https://github.com/RafalWilinski/express-status-monitor#readme",
    "keywords": [
        "node",
        "status",
        "monitoring",
        "express",
        "charts"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rwilinski"
        }
    ],
    "name": "express-status-monitor",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/RafalWilinski/express-status-monitor.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha test --  --recursive",
        "eslint": "eslint .",
        "example": "cd examples && npm start",
        "prepublish": "npm run snyk-protect",
        "snyk-protect": "snyk protect",
        "test": "mocha --recursive"
    },
    "snyk": true,
    "version": "0.1.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
