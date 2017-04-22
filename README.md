# npmtest-vueify

#### basic test coverage for  [vueify (v9.4.1)](https://github.com/vuejs/vueify)  [![npm package](https://img.shields.io/npm/v/npmtest-vueify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vueify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vueify.svg)](https://travis-ci.org/npmtest/node-npmtest-vueify)

#### Vue component transform for Browserify

[![NPM](https://nodei.co/npm/vueify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vueify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vueify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vueify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vueify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vueify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vueify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vueify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vueify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vueify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vueify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vueify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vueify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vueify/build/test-report.html](https://npmtest.github.io/node-npmtest-vueify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vueify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vueify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vueify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vueify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vueify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vueify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vueify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vueify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan You"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vueify/issues"
    },
    "dependencies": {
        "chalk": "^1.1.1",
        "convert-source-map": "^1.2.0",
        "cssnano": "^3.3.2",
        "hash-sum": "^1.0.2",
        "json5": "^0.5.1",
        "lru-cache": "^4.0.0",
        "object-assign": "^4.0.1",
        "postcss": "^5.0.10",
        "postcss-selector-parser": "^2.0.0",
        "source-map": "^0.5.6",
        "through": "^2.3.6",
        "vue-hot-reload-api": "^2.0.1",
        "vue-template-compiler": "^2.0.0-alpha.8",
        "vue-template-es2015-compiler": "^1.2.2"
    },
    "description": "Vue component transform for Browserify",
    "devDependencies": {
        "babel-core": "^6.0.0",
        "babel-plugin-transform-runtime": "^6.0.0",
        "babel-preset-es2015": "^6.0.0",
        "babel-runtime": "^6.0.0",
        "browserify": "^13.0.1",
        "chai": "^3.5.0",
        "coffee-script": "^1.10.0",
        "eslint": "^2.13.0",
        "eslint-config-vue": "^1.0.3",
        "eslint-plugin-html": "^1.5.3",
        "jade": "^1.11.0",
        "jsdom": "^9.2.1",
        "less": "^2.5.1",
        "mkdirp": "^0.5.1",
        "mocha": "^2.3.3",
        "node-sass": "^3.3.3",
        "pug": "^2.0.0-alpha6",
        "rimraf": "^2.5.2",
        "stylus": "^0.52.4"
    },
    "directories": {},
    "dist": {
        "shasum": "d29a9775a33c4b8a8601e186a85da2ab800ca0d6",
        "tarball": "https://registry.npmjs.org/vueify/-/vueify-9.4.1.tgz"
    },
    "gitHead": "8d3159ff7d41bfaf1662056436a4252ea07219aa",
    "homepage": "https://github.com/vuejs/vueify",
    "keywords": [
        "vue",
        "browserify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "yyx990803"
        }
    ],
    "name": "vueify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vueify.git"
    },
    "scripts": {
        "test": "eslint index.js lib && mocha test/test.js --slow=5000 --timeout=10000"
    },
    "version": "9.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
