# npmtest-eslint-plugin-html

#### basic test coverage for  [eslint-plugin-html (v2.0.1)](https://github.com/BenoitZugmeyer/eslint-plugin-html)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-html.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-html) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-html.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-html)

#### An ESLint plugin to extract and lint scripts from HTML files.

[![NPM](https://nodei.co/npm/eslint-plugin-html.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-html)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-html/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-eslint-plugin-html/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-html/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-html/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-html/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-html/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-html/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-html/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-html/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "eslint-plugin-html",
    "version": "2.0.1",
    "description": "An ESLint plugin to extract and lint scripts from HTML files.",
    "license": "ISC",
    "repository": {
        "type": "git",
        "url": "https://github.com/BenoitZugmeyer/eslint-plugin-html"
    },
    "homepage": "https://github.com/BenoitZugmeyer/eslint-plugin-html",
    "bugs": "https://github.com/BenoitZugmeyer/eslint-plugin-html/issues",
    "keywords": [
        "eslint-plugin",
        "eslintplugin",
        "eslint",
        "html"
    ],
    "main": "src/index.js",
    "dependencies": {
        "htmlparser2": "^3.8.2"
    },
    "devDependencies": {
        "eslint": "^3.2.2",
        "jest": "^18.1.0"
    },
    "scripts": {
        "test": "jest",
        "lint": "eslint ."
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
