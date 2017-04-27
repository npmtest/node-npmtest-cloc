# npmtest-cloc

#### basic test coverage for  [cloc (v2.2.0)](https://github.com/kentcdodds/cloc#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cloc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cloc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cloc.svg)](https://travis-ci.org/npmtest/node-npmtest-cloc)

#### An npm module for distributing cloc by Al Danial http://cloc.sourceforge.net/

[![NPM](https://nodei.co/npm/cloc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cloc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cloc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cloc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cloc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cloc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cloc/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cloc/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cloc/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cloc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cloc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cloc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cloc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cloc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cloc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cloc/build/test-report.html](https://npmtest.github.io/node-npmtest-cloc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cloc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cloc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cloc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cloc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cloc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cloc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cloc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cloc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kent C. Dodds",
        "url": "http://kentcdodds.com"
    },
    "bin": {
        "cloc": "lib/cloc"
    },
    "bugs": {
        "url": "https://github.com/kentcdodds/cloc/issues"
    },
    "dependencies": {},
    "description": "An npm module for distributing cloc by Al Danial http://cloc.sourceforge.net/",
    "devDependencies": {
        "semantic-release": "^6.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "ee38e476fd050edc1d2ef8357cbde274b7c7efb4",
        "tarball": "https://registry.npmjs.org/cloc/-/cloc-2.2.0.tgz"
    },
    "gitHead": "5c6584e45681f7ce7242a8f7acc1fe43d462db43",
    "homepage": "https://github.com/kentcdodds/cloc#readme",
    "keywords": [
        "cloc",
        "count lines of code",
        "lines of code",
        "loc"
    ],
    "license": "GPL-2.0",
    "main": "lib/cloc",
    "maintainers": [
        {
            "name": "kentcdodds"
        }
    ],
    "name": "cloc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kentcdodds/cloc.git"
    },
    "scripts": {
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "test": "echo \"Error: no test specified\""
    },
    "version": "2.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
