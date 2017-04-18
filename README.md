# test coverage for  [dnscache (v1.0.1)](https://github.com/yahoo/dnscache#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-dnscache.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-dnscache) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-dnscache.svg)](https://travis-ci.org/npmtest/node-npmtest-dnscache)
#### dnscache for Node

[![NPM](https://nodei.co/npm/dnscache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dnscache)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-dnscache/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-dnscache/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-dnscache/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-dnscache/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-dnscache/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-dnscache/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-dnscache/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-dnscache/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-dnscache/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-dnscache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-dnscache/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-dnscache/build/test-report.html](https://npmtest.github.io/node-npmtest-dnscache/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-dnscache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-dnscache/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-dnscache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dnscache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dnscache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dnscache/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-dnscache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-dnscache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vinit Sacheti"
    },
    "bugs": {
        "url": "http://github.com/yahoo/dnscache/issues"
    },
    "dependencies": {
        "asap": "~2.0.3",
        "lodash.clone": "~4.3.2"
    },
    "description": "dnscache for Node",
    "devDependencies": {
        "async": "~1.5.2",
        "istanbul": "~0.4.3",
        "jenkins-mocha": "~2.6.0",
        "jshint": "~2.9.2",
        "yui-lint": "~0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "42cb2b9bfb5e8fbdfa395aac74e127fc05074d31",
        "tarball": "https://registry.npmjs.org/dnscache/-/dnscache-1.0.1.tgz"
    },
    "gitHead": "3669aafb400a406b00c5af5ed02dd53fdb3f5b9b",
    "homepage": "https://github.com/yahoo/dnscache#readme",
    "keywords": [
        "dnscache",
        "dns"
    ],
    "license": "BSD",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "davglass"
        },
        {
            "name": "drewfolta"
        },
        {
            "name": "sylviom"
        },
        {
            "name": "vsacheti"
        }
    ],
    "name": "dnscache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/yahoo/dnscache.git"
    },
    "scripts": {
        "posttest": "istanbul check-coverage",
        "pretest": "jshint --config ./node_modules/yui-lint/jshint.json ./lib/ ./test/",
        "test": "jenkins-mocha ./test/*.js"
    },
    "version": "1.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
