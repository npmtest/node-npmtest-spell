# npmtest-spell

#### basic test coverage for  [spell (v1.0.0)](http://github.com/dscape/spell)  [![npm package](https://img.shields.io/npm/v/npmtest-spell.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-spell) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-spell.svg)](https://travis-ci.org/npmtest/node-npmtest-spell)

#### javascript dictionary module for node.js, and the browser

[![NPM](https://nodei.co/npm/spell.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spell)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-spell/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-spell/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-spell/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-spell/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-spell/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-spell/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-spell/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-spell/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-spell/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-spell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-spell/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-spell/build/test-report.html](https://npmtest.github.io/node-npmtest-spell/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-spell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-spell/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-spell/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spell/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spell/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-spell/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-spell/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nuno Job",
        "url": "http://nunojob.com"
    },
    "bugs": {
        "url": "https://github.com/dscape/spell/issues"
    },
    "contributors": [
        {
            "name": "Pedro Teixeira",
            "url": "http://metaduck.com"
        }
    ],
    "dependencies": {},
    "description": "javascript dictionary module for node.js, and the browser",
    "devDependencies": {
        "mocha": "0.3.6",
        "should": "0.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "10a3b9b056a184b64a1b120e2425f6f7a250aa85",
        "tarball": "https://registry.npmjs.org/spell/-/spell-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.3.6"
    },
    "homepage": "http://github.com/dscape/spell",
    "keywords": [
        "spell",
        "speller",
        "dictionary",
        "nlp",
        "dict",
        "spell check"
    ],
    "main": "./spell.js",
    "maintainers": [
        {
            "name": "dscape"
        }
    ],
    "name": "spell",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dscape/spell.git"
    },
    "scripts": {
        "perf1": "node --prof --trace-opt --trace-bailout --trace-deopt test/perf.js 1",
        "perf2": "node --prof --trace-opt --trace-bailout --trace-deopt test/perf.js 2",
        "test": "./node_modules/mocha/bin/mocha --globals _test_spell -r should test/spell.js"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
