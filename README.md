# npmtest-loopback

#### basic test coverage for  [loopback (v3.6.0)](http://loopback.io)  [![npm package](https://img.shields.io/npm/v/npmtest-loopback.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-loopback) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-loopback.svg)](https://travis-ci.org/npmtest/node-npmtest-loopback)

#### LoopBack: Open Source Framework for Node.js

[![NPM](https://nodei.co/npm/loopback.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/loopback)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-loopback/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-loopback/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-loopback/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-loopback/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-loopback/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-loopback/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-loopback/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-loopback/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-loopback/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-loopback/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-loopback/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-loopback/build/test-report.html](https://npmtest.github.io/node-npmtest-loopback/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-loopback/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-loopback/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-loopback/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-loopback/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-loopback/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-loopback/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-loopback/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-loopback/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "express": "./lib/browser-express.js",
        "./lib/server-app.js": "./lib/browser-express.js",
        "connect": false,
        "nodemailer": false,
        "supertest": false,
        "depd": "loopback-datasource-juggler/lib/browser.depd.js",
        "bcrypt": false
    },
    "bugs": {
        "url": "https://github.com/strongloop/loopback/issues"
    },
    "config": {
        "ci": {
            "debug": "*,-mocha:*,-eslint:*"
        }
    },
    "dependencies": {
        "async": "^2.0.1",
        "bcryptjs": "^2.1.0",
        "bluebird": "^3.1.1",
        "body-parser": "^1.12.0",
        "canonical-json": "0.0.4",
        "debug": "^2.1.2",
        "depd": "^1.0.0",
        "ejs": "^2.3.1",
        "express": "^4.14.0",
        "inflection": "^1.6.0",
        "isemail": "^2.2.1",
        "loopback-connector-remote": "^3.0.0",
        "loopback-datasource-juggler": "^3.0.0",
        "loopback-phase": "^3.0.0",
        "nodemailer": "^2.5.0",
        "nodemailer-stub-transport": "^1.0.0",
        "serve-favicon": "^2.2.0",
        "stable": "^0.1.5",
        "strong-globalize": "^2.7.0",
        "strong-remoting": "^3.0.0",
        "uid2": "0.0.3",
        "underscore.string": "^3.0.3"
    },
    "description": "LoopBack: Open Source Framework for Node.js",
    "devDependencies": {
        "babel-preset-es2015": "^6.22.0",
        "babelify": "^7.3.0",
        "browserify": "^13.1.0",
        "chai": "^3.5.0",
        "cookie-parser": "^1.3.4",
        "coveralls": "^2.11.15",
        "dirty-chai": "^1.2.2",
        "eslint-config-loopback": "^8.0.0",
        "express-session": "^1.14.0",
        "grunt": "^1.0.1",
        "grunt-browserify": "^5.0.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-eslint": "^19.0.0",
        "grunt-karma": "^2.0.0",
        "grunt-mocha-test": "^0.12.7",
        "karma": "^1.1.2",
        "karma-browserify": "^4.4.2",
        "karma-chrome-launcher": "^1.0.1",
        "karma-es6-shim": "^1.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-html2js-preprocessor": "^1.0.0",
        "karma-junit-reporter": "~1.0.0",
        "karma-mocha": "^1.1.1",
        "karma-phantomjs-launcher": "^1.0.0",
        "karma-script-launcher": "^1.0.0",
        "loopback-boot": "^2.7.0",
        "loopback-context": "^1.0.0",
        "mocha": "^3.0.0",
        "nyc": "^10.1.2",
        "phantomjs-prebuilt": "^2.1.7",
        "sinon": "^1.13.0",
        "sinon-chai": "^2.8.0",
        "strong-error-handler": "^1.0.1",
        "strong-task-emitter": "^0.0.6",
        "supertest": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a114bb4c1ade1952594527e00b8581be08a0735a",
        "tarball": "https://registry.npmjs.org/loopback/-/loopback-3.6.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "0499d09d6b34aec87f4f05a576851ba3d5ac4dc6",
    "homepage": "http://loopback.io",
    "keywords": [
        "web",
        "restful",
        "rest",
        "api",
        "express",
        "restify",
        "koa",
        "auth",
        "security",
        "oracle",
        "mysql",
        "nosql",
        "mongo",
        "mongodb",
        "sqlserver",
        "mssql",
        "postgres",
        "postgresql",
        "soap",
        "StrongLoop",
        "framework",
        "mobile",
        "mBaaS"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "0candy"
        },
        {
            "name": "amir-61"
        },
        {
            "name": "b-admike"
        },
        {
            "name": "bajtos"
        },
        {
            "name": "chandadharap"
        },
        {
            "name": "davidcheung"
        },
        {
            "name": "hacksparrow"
        },
        {
            "name": "ibmcloud-admin"
        },
        {
            "name": "jannyhou2016"
        },
        {
            "name": "kjdelisle"
        },
        {
            "name": "kraman"
        },
        {
            "name": "loay"
        },
        {
            "name": "loopback-admin"
        },
        {
            "name": "octet"
        },
        {
            "name": "qpresley"
        },
        {
            "name": "rashmihunt"
        },
        {
            "name": "rfeng"
        },
        {
            "name": "ritch"
        },
        {
            "name": "rmg"
        },
        {
            "name": "setogit"
        },
        {
            "name": "strongloop"
        },
        {
            "name": "superkhau"
        },
        {
            "name": "thegman"
        },
        {
            "name": "tonyf-ibm"
        }
    ],
    "name": "loopback",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/strongloop/loopback.git"
    },
    "scripts": {
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "lint": "grunt eslint",
        "test": "nyc grunt mocha-and-karma"
    },
    "version": "3.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
