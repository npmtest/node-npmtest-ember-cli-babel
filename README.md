# npmtest-ember-cli-babel

#### basic test coverage for  ember-cli-babel (v5.2.4)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-cli-babel.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-cli-babel) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-cli-babel.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-cli-babel)

#### Ember CLI addon for Babel

[![NPM](https://nodei.co/npm/ember-cli-babel.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-cli-babel)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-cli-babel/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-cli-babel/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-cli-babel/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-cli-babel/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-cli-babel/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-cli-babel/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-cli-babel/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-cli-babel/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-cli-babel/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-cli-babel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-cli-babel",
    "version": "5.2.4",
    "description": "Ember CLI addon for Babel",
    "keywords": [
        "ember-addon",
        "babel",
        "ember",
        "ember-cli",
        "transpile",
        "transpiler"
    ],
    "bugs": {
        "url": "https://github.com/babel/ember-cli-babel/issues"
    },
    "license": "MIT",
    "author": "Gordon Kristan",
    "files": [
        "index.js"
    ],
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/babel/ember-cli-babel.git"
    },
    "scripts": {
        "build": "ember build",
        "jshint": "jshint",
        "start": "ember server",
        "test": "mocha node-tests && ember test"
    },
    "dependencies": {
        "broccoli-babel-transpiler": "^5.6.2",
        "broccoli-funnel": "^1.0.0",
        "clone": "^2.0.0",
        "ember-cli-version-checker": "^1.0.2",
        "resolve": "^1.1.2"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "console-ui": "^1.0.2",
        "core-object": "^2.0.6",
        "ember-cli": "^2.6.2",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.8",
        "ember-cli-htmlbars-inline-precompile": "^0.3.2",
        "ember-cli-inject-live-reload": "^1.3.1",
        "ember-cli-qunit": "^3.0.2",
        "ember-export-application-global": "^1.0.3",
        "ember-load-initializers": "0.5.1",
        "ember-resolver": "^2.1.0",
        "loader.js": "4.0.11",
        "mocha": "^3.2.0"
    },
    "engines": {
        "node": ">= 0.12"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
