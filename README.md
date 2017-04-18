# npmtest-sails-swagger

#### test coverage for  [sails-swagger (v0.5.1)](https://github.com/tjwebb/sails-swagger)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-swagger.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-swagger) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-swagger.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-swagger)

#### swagger.io integration for sails.js

[![NPM](https://nodei.co/npm/sails-swagger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-swagger)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-swagger/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-swagger/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-swagger/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-swagger/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-swagger/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-swagger/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-swagger/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-swagger/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-swagger/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-swagger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-swagger/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-swagger/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-swagger/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-swagger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-swagger/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-swagger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-swagger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-swagger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-swagger/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-swagger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-swagger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Travis Webb"
    },
    "bugs": {
        "url": "https://github.com/tjwebb/sails-swagger/issues"
    },
    "dependencies": {
        "hoek": "^2.14.0",
        "lodash": "^3.10.1",
        "marlinspike": "^0.12.10"
    },
    "description": "swagger.io integration for sails.js",
    "devDependencies": {
        "babel": "^5.8.21",
        "gulp": "^3.9.0",
        "gulp-babel": "^5.2.1",
        "mocha": "^2.2.5",
        "sails": "github:balderdashy/sails",
        "sails-disk": "^0.10.8"
    },
    "directories": {},
    "dist": {
        "shasum": "1ee8bec6495e1ed3e79fc588f3630a70e2ff1278",
        "tarball": "https://registry.npmjs.org/sails-swagger/-/sails-swagger-0.5.1.tgz"
    },
    "gitHead": "ed632733ba37fe13d2d3f710a433f8eea9ba0f12",
    "homepage": "https://github.com/tjwebb/sails-swagger",
    "keywords": [
        "sails",
        "sailsjs",
        "swagger",
        "swagger.io",
        "api",
        "sdk",
        "documentation"
    ],
    "license": "MIT",
    "main": "dist/api/hooks/swagger/index.js",
    "maintainers": [
        {
            "name": "tjwebb"
        },
        {
            "name": "balderdash"
        },
        {
            "name": "sailsjs"
        }
    ],
    "name": "sails-swagger",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tjwebb/sails-swagger.git"
    },
    "sails": {
        "isHook": true,
        "hookName": "swagger"
    },
    "scripts": {
        "prepublish": "gulp",
        "test": "gulp && mocha --reporter spec --compilers js:babel/register"
    },
    "version": "0.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
