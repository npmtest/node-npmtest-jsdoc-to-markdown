# test coverage for  [jsdoc-to-markdown (v3.0.0)](https://github.com/jsdoc2md/jsdoc-to-markdown#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-jsdoc-to-markdown.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsdoc-to-markdown) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsdoc-to-markdown.svg)](https://travis-ci.org/npmtest/node-npmtest-jsdoc-to-markdown)
#### Generates markdown API documentation from jsdoc annotated source code

[![NPM](https://nodei.co/npm/jsdoc-to-markdown.png?downloads=true)](https://www.npmjs.com/package/jsdoc-to-markdown)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsdoc-to-markdown/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsdoc-to-markdown/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-jsdoc-to-markdown%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsdoc-to-markdown/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-jsdoc-to-markdown%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsdoc-to-markdown/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsdoc-to-markdown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Lloyd Brookes"
    },
    "bin": {
        "jsdoc2md": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/jsdoc2md/jsdoc-to-markdown/issues"
    },
    "dependencies": {
        "array-back": "^1.0.4",
        "command-line-tool": "^0.7.0",
        "config-master": "^3.0.0",
        "dmd": "^3.0.0",
        "jsdoc-api": "^3.0.0",
        "jsdoc-parse": "^3.0.0",
        "jsdoc2md-stats": "^2.0.0",
        "walk-back": "^2.0.1"
    },
    "description": "Generates markdown API documentation from jsdoc annotated source code",
    "devDependencies": {
        "coveralls": "^2.11.16",
        "test-runner": "^0.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cc8a94f1f412ac1da4bac1657475b0975ee8161a",
        "tarball": "https://registry.npmjs.org/jsdoc-to-markdown/-/jsdoc-to-markdown-3.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "e31891d2d23e579914cc688a417e48c72f8b50c3",
    "homepage": "https://github.com/jsdoc2md/jsdoc-to-markdown#readme",
    "keywords": [
        "jsdoc",
        "markdown",
        "api",
        "generator",
        "javascript",
        "js",
        "documentation"
    ],
    "license": "MIT",
    "main": "lib/jsdoc-to-markdown.js",
    "maintainers": [
        {
            "name": "75lb",
            "email": "75pound@gmail.com"
        }
    ],
    "name": "jsdoc-to-markdown",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jsdoc2md/jsdoc-to-markdown.git"
    },
    "scripts": {
        "cover": "istanbul cover ./node_modules/.bin/test-runner test/*.js && cat coverage/lcov.info | ./node_modules/.bin/coveralls && rm -rf coverage; echo",
        "docs": "node bin/cli.js --separators lib/*.js --heading-depth 1 --template jsdoc2md/API.hbs > docs/API.md; echo ",
        "test": "test-runner test/*.js"
    },
    "standard": {
        "ignore": [
            "test/fixture"
        ]
    },
    "version": "3.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
