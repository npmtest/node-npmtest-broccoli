# npmtest-broccoli

#### basic test-coverage for  [broccoli (v1.1.1)](https://github.com/broccolijs/broccoli)  [![npm package](https://img.shields.io/npm/v/npmtest-broccoli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-broccoli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-broccoli.svg)](https://travis-ci.org/npmtest/node-npmtest-broccoli)

#### Fast client-side asset builder

[![NPM](https://nodei.co/npm/broccoli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/broccoli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-broccoli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-broccoli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-broccoli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-broccoli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-broccoli/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-broccoli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-broccoli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-broccoli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-broccoli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-broccoli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-broccoli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-broccoli/build/test-report.html](https://npmtest.github.io/node-npmtest-broccoli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-broccoli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-broccoli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-broccoli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-broccoli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-broccoli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-broccoli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-broccoli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-broccoli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jo Liss"
    },
    "bugs": {
        "url": "https://github.com/broccolijs/broccoli/issues"
    },
    "dependencies": {
        "broccoli-node-info": "1.1.0",
        "broccoli-slow-trees": "^2.0.0",
        "broccoli-source": "^1.1.0",
        "commander": "^2.5.0",
        "connect": "^3.3.3",
        "copy-dereference": "^1.0.0",
        "findup-sync": "^0.4.2",
        "handlebars": "^4.0.4",
        "heimdalljs-logger": "^0.1.7",
        "mime": "^1.2.11",
        "rimraf": "^2.4.3",
        "rsvp": "^3.0.17",
        "sane": "^1.4.1",
        "tmp": "0.0.28",
        "underscore.string": "^3.2.2"
    },
    "description": "Fast client-side asset builder",
    "devDependencies": {
        "chai": "^3.3.0",
        "chai-as-promised": "^5.1.0",
        "fixturify": "^0.2.0",
        "mocha": "^3.0.0",
        "mocha-jshint": "^2.2.5",
        "multidep": "^2.0.0",
        "semver": "^5.3.0",
        "sinon": "^1.17.1",
        "sinon-chai": "^2.8.0",
        "symlink-or-copy": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "0287e72994363777bdfd4e8c71805125337c2bf7",
        "tarball": "https://registry.npmjs.org/broccoli/-/broccoli-1.1.1.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "51917754fdb10bd1fc9a43012479928d41cbded2",
    "homepage": "https://github.com/broccolijs/broccoli",
    "keywords": [
        "builder",
        "build",
        "frontend",
        "browser",
        "asset",
        "pipeline"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "joliss"
        },
        {
            "name": "rwjblue"
        },
        {
            "name": "stefanpenner"
        }
    ],
    "name": "broccoli",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/broccolijs/broccoli.git"
    },
    "scripts": {
        "pretest": "multidep test/multidep.json",
        "test": "mocha"
    },
    "version": "1.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
