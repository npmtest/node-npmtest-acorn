# test coverage for  [acorn (v5.0.3)](https://github.com/ternjs/acorn)  [![npm package](https://img.shields.io/npm/v/npmtest-acorn.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-acorn) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-acorn.svg)](https://travis-ci.org/npmtest/node-npmtest-acorn)
#### ECMAScript parser

[![NPM](https://nodei.co/npm/acorn.png?downloads=true)](https://www.npmjs.com/package/acorn)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-acorn/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-acorn/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-acorn/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-acorn/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-acorn/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-acorn/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-acorn/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-acorn/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-acorn/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-acorn/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-acorn%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-acorn/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-acorn/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-acorn%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-acorn/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-acorn/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-acorn/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "acorn": "./bin/acorn"
    },
    "bugs": {
        "url": "https://github.com/ternjs/acorn/issues"
    },
    "contributors": [
        {
            "name": "List of Acorn contributors. Updated before every release."
        },
        {
            "name": "Adrian Rakovsky"
        },
        {
            "name": "Alistair Braidwood"
        },
        {
            "name": "Amila Welihinda"
        },
        {
            "name": "Andres Suarez"
        },
        {
            "name": "Angelo"
        },
        {
            "name": "Aparajita Fishman"
        },
        {
            "name": "Arian Stolwijk"
        },
        {
            "name": "Artem Govorov"
        },
        {
            "name": "Brandon Mills"
        },
        {
            "name": "Charles Hughes"
        },
        {
            "name": "Conrad Irwin"
        },
        {
            "name": "Daniel Tschinder"
        },
        {
            "name": "David Bonnet"
        },
        {
            "name": "Domenico Matteo"
        },
        {
            "name": "Forbes Lindesay"
        },
        {
            "name": "Gilad Peleg"
        },
        {
            "name": "impinball"
        },
        {
            "name": "Ingvar Stepanyan"
        },
        {
            "name": "Jackson Ray Hamilton"
        },
        {
            "name": "Jesse McCarthy"
        },
        {
            "name": "Jiaxing Wang"
        },
        {
            "name": "Joel Kemp"
        },
        {
            "name": "Johannes Herr"
        },
        {
            "name": "John-David Dalton"
        },
        {
            "name": "Jordan Klassen"
        },
        {
            "name": "Jürg Lehni"
        },
        {
            "name": "Kai Cataldo"
        },
        {
            "name": "keeyipchan"
        },
        {
            "name": "Keheliya Gallaba"
        },
        {
            "name": "Kevin Irish"
        },
        {
            "name": "Kevin Kwok"
        },
        {
            "name": "krator"
        },
        {
            "name": "Marijn Haverbeke"
        },
        {
            "name": "Martin Carlberg"
        },
        {
            "name": "Mat Garcia"
        },
        {
            "name": "Mathias Bynens"
        },
        {
            "name": "Mathieu 'p01' Henri"
        },
        {
            "name": "Matthew Bastien"
        },
        {
            "name": "Max Schaefer"
        },
        {
            "name": "Max Zerzouri"
        },
        {
            "name": "Mihai Bazon"
        },
        {
            "name": "Mike Rennie"
        },
        {
            "name": "naoh"
        },
        {
            "name": "Nicholas C. Zakas"
        },
        {
            "name": "Nick Fitzgerald"
        },
        {
            "name": "Olivier Thomann"
        },
        {
            "name": "Oskar Schöldström"
        },
        {
            "name": "Paul Harper"
        },
        {
            "name": "Peter Rust"
        },
        {
            "name": "PlNG"
        },
        {
            "name": "Prayag Verma"
        },
        {
            "name": "ReadmeCritic"
        },
        {
            "name": "r-e-d"
        },
        {
            "name": "Richard Gibson"
        },
        {
            "name": "Rich Harris"
        },
        {
            "name": "Sebastian McKenzie"
        },
        {
            "name": "Simen Bekkhus"
        },
        {
            "name": "Teddy Katz"
        },
        {
            "name": "Timothy Gu"
        },
        {
            "name": "Toru Nagashima"
        },
        {
            "name": "Wexpo Lyu"
        },
        {
            "name": "zsjforcn"
        }
    ],
    "dependencies": {},
    "description": "ECMAScript parser",
    "devDependencies": {
        "eslint": "^3.18.0",
        "eslint-config-standard": "^7.1.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-promise": "^3.5.0",
        "eslint-plugin-standard": "^2.1.1",
        "rollup": "^0.34.1",
        "rollup-plugin-buble": "^0.11.0",
        "unicode-9.0.0": "^0.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c460df08491463f028ccb82eab3730bf01087b3d",
        "tarball": "https://registry.npmjs.org/acorn/-/acorn-5.0.3.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "dc2a033831e0813496bdb558c70b9fdf4720f048",
    "homepage": "https://github.com/ternjs/acorn",
    "jsnext:main": "dist/acorn.es.js",
    "license": "MIT",
    "main": "dist/acorn.js",
    "maintainers": [
        {
            "name": "marijn",
            "email": "marijnh@gmail.com"
        }
    ],
    "name": "acorn",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ternjs/acorn.git"
    },
    "scripts": {
        "build": "npm run build:main && npm run build:walk && npm run build:loose && npm run build:bin",
        "build:bin": "rollup -c rollup/config.bin.js",
        "build:loose": "rollup -c rollup/config.loose.js",
        "build:main": "rollup -c rollup/config.main.js",
        "build:walk": "rollup -c rollup/config.walk.js",
        "lint": "eslint src/",
        "prepublish": "npm test",
        "pretest": "npm run build",
        "test": "node test/run.js && node test/lint.js"
    },
    "version": "5.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
