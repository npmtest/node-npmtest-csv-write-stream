# npmtest-csv-write-stream

#### test coverage for  [csv-write-stream (v2.0.0)](https://github.com/maxogden/csv-write-stream)  [![npm package](https://img.shields.io/npm/v/npmtest-csv-write-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csv-write-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csv-write-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-csv-write-stream)

#### A CSV encoder stream that produces properly escaped CSVs.

[![NPM](https://nodei.co/npm/csv-write-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csv-write-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csv-write-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv-write-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csv-write-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csv-write-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csv-write-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csv-write-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csv-write-stream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csv-write-stream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csv-write-stream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv-write-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csv-write-stream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csv-write-stream/build/test-report.html](https://npmtest.github.io/node-npmtest-csv-write-stream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csv-write-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csv-write-stream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csv-write-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csv-write-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csv-write-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csv-write-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csv-write-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csv-write-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "csv-write": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/csv-write-stream/issues"
    },
    "dependencies": {
        "argparse": "^1.0.7",
        "generate-object-property": "^1.0.0",
        "ndjson": "^1.3.0"
    },
    "description": "A CSV encoder stream that produces properly escaped CSVs.",
    "devDependencies": {
        "concat-stream": "~1.4.1",
        "tape": "~2.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "fc2da21a48d6ea5f8c17fde39cfb911e4f0292b0",
        "tarball": "https://registry.npmjs.org/csv-write-stream/-/csv-write-stream-2.0.0.tgz"
    },
    "gitHead": "c817170d6b7812eb552da20fcbd5cb3a4012b9d1",
    "homepage": "https://github.com/maxogden/csv-write-stream",
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "finnpauls"
        },
        {
            "name": "mafintosh"
        },
        {
            "name": "maxogden"
        },
        {
            "name": "slang"
        }
    ],
    "name": "csv-write-stream",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/maxogden/csv-write-stream.git"
    },
    "scripts": {
        "test": "node test.js"
    },
    "testling": {
        "files": "test.js",
        "browsers": [
            "ie/8..latest",
            "firefox/17..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "2.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
