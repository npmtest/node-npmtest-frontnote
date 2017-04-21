# npmtest-frontnote

#### basic test coverage for  [frontnote (v2.0.5)](https://github.com/frontainer/frontnote)  [![npm package](https://img.shields.io/npm/v/npmtest-frontnote.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-frontnote) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-frontnote.svg)](https://travis-ci.org/npmtest/node-npmtest-frontnote)

#### StyleGuide Generator FrontNote

[![NPM](https://nodei.co/npm/frontnote.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/frontnote)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-frontnote/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-frontnote/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-frontnote/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-frontnote/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-frontnote/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-frontnote/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-frontnote/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-frontnote/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-frontnote/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-frontnote/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-frontnote/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-frontnote/build/test-report.html](https://npmtest.github.io/node-npmtest-frontnote/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-frontnote/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-frontnote/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-frontnote/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-frontnote/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-frontnote/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-frontnote/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-frontnote/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-frontnote/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "frontnote",
    "version": "2.0.5",
    "description": "StyleGuide Generator FrontNote",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/frontainer/frontnote"
    },
    "author": "frontainer <frontainer@gmail.com> (http://frontainer.com)",
    "engines": {
        "node": ">=5.0.0"
    },
    "bin": {
        "frontnote": "./bin/index.js"
    },
    "scripts": {
        "changelog": "conventional-changelog -p eslint -i CHANGELOG.md -w -s -r 0",
        "test": "./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require intelli-espower-loader -R spec ./test/frontnote.js"
    },
    "keywords": [
        "styleguide",
        "sass",
        "less",
        "stylus",
        "css",
        "ejs"
    ],
    "dependencies": {
        "chalk": "^1.1.3",
        "commander": "^2.9.0",
        "cpx": "^1.5.0",
        "ejs": "^2.5.2",
        "extend": "^3.0.0",
        "fs-extra": "^0.30.0",
        "gaze": "^1.1.2",
        "glob": "^7.1.0",
        "marked": "^0.3.6",
        "memory-cache": "^0.1.6",
        "ora": "^0.3.0",
        "rxjs": "^5.0.0-beta.12",
        "sanitizer": "^0.1.3"
    },
    "devDependencies": {
        "conventional-changelog-cli": "^1.2.0",
        "espower-loader": "^1.0.1",
        "intelli-espower-loader": "^1.0.1",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.0",
        "power-assert": "^1.4.1"
    },
    "bugs": {
        "url": "https://github.com/frontainer/frontnote/issues"
    },
    "homepage": "https://github.com/frontainer/frontnote",
    "main": "index.js"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
