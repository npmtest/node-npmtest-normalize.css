# npmtest-normalize.css

#### basic test coverage for  [normalize.css (v6.0.0)](https://necolas.github.io/normalize.css)  [![npm package](https://img.shields.io/npm/v/npmtest-normalize.css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-normalize.css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-normalize.css.svg)](https://travis-ci.org/npmtest/node-npmtest-normalize.css)

#### A modern alternative to CSS resets

[![NPM](https://nodei.co/npm/normalize.css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/normalize.css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-normalize.css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-normalize.css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-normalize.css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-normalize.css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-normalize.css/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-normalize.css/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-normalize.css/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-normalize.css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-normalize.css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-normalize.css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-normalize.css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-normalize.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-normalize.css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-normalize.css/build/test-report.html](https://npmtest.github.io/node-npmtest-normalize.css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-normalize.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-normalize.css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-normalize.css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-normalize.css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-normalize.css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-normalize.css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-normalize.css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-normalize.css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/necolas/normalize.css/issues"
    },
    "contributors": [
        {
            "name": "Jonathan Neal",
            "url": "http://jonathantneal.com/"
        },
        {
            "name": "Nicolas Gallagher",
            "url": "http://nicolasgallagher.com/"
        }
    ],
    "dependencies": {},
    "description": "A modern alternative to CSS resets",
    "devDependencies": {
        "stylelint": "^7.9.0",
        "stylelint-config-standard": "^16.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "22188c2707c911fb3ad3c1aac0677ff68661bea8",
        "tarball": "https://registry.npmjs.org/normalize.css/-/normalize.css-6.0.0.tgz"
    },
    "files": [
        "LICENSE.md",
        "normalize.css"
    ],
    "gitHead": "91f668be643185dd7b08f122ccee0df711d237c0",
    "homepage": "https://necolas.github.io/normalize.css",
    "license": "MIT",
    "main": "normalize.css",
    "maintainers": [
        {
            "name": "jonathantneal"
        },
        {
            "name": "necolas"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "normalize.css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/necolas/normalize.css.git"
    },
    "scripts": {
        "test": "stylelint normalize.css"
    },
    "style": "normalize.css",
    "stylelint": {
        "extends": "stylelint-config-standard",
        "rules": {
            "font-family-no-duplicate-names": [
                true,
                {
                    "ignoreFontFamilyNames": [
                        "monospace"
                    ]
                }
            ]
        }
    },
    "version": "6.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
