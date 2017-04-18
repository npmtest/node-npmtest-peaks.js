# npmtest-peaks.js

#### test coverage for  [peaks.js (v0.6.0)](https://github.com/bbc/peaks.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-peaks.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-peaks.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-peaks.js.svg)](https://travis-ci.org/npmtest/node-npmtest-peaks.js)

#### Frontend app for displaying audio waveforms

[![NPM](https://nodei.co/npm/peaks.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/peaks.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-peaks.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-peaks.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-peaks.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-peaks.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-peaks.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-peaks.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-peaks.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-peaks.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-peaks.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-peaks.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-peaks.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-peaks.js/build/test-report.html](https://npmtest.github.io/node-npmtest-peaks.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-peaks.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-peaks.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-peaks.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-peaks.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-peaks.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-peaks.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-peaks.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-peaks.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "EventEmitter": "eventemitter2",
        "peaks/player/player": "./src/main/player/player.js",
        "peaks/player/player.keyboard": "./src/main/player/player.keyboard.js",
        "peaks/waveform/waveform.axis": "./src/main/waveform/waveform.axis.js",
        "peaks/waveform/waveform.core": "./src/main/waveform/waveform.core.js",
        "peaks/waveform/waveform.mixins": "./src/main/waveform/waveform.mixins.js",
        "peaks/waveform/waveform.utils": "./src/main/waveform/waveform.utils.js",
        "peaks/views/waveform.overview": "./src/main/views/waveform.overview.js",
        "peaks/views/waveform.zoomview": "./src/main/views/waveform.zoomview.js",
        "peaks/views/helpers/mousedraghandler": "./src/main/views/helpers/mousedraghandler.js",
        "peaks/views/zooms/animated": "./src/main/views/zooms/animated.js",
        "peaks/views/zooms/static": "./src/main/views/zooms/static.js",
        "peaks/markers/waveform.points": "./src/main/markers/waveform.points.js",
        "peaks/markers/waveform.segments": "./src/main/markers/waveform.segments.js",
        "peaks/markers/shapes/base": "./src/main/markers/shapes/base.js",
        "peaks/markers/shapes/rect": "./src/main/markers/shapes/rect.js",
        "peaks/markers/shapes/wave": "./src/main/markers/shapes/wave.js"
    },
    "bugs": {
        "url": "https://github.com/bbc/peaks.js/issues"
    },
    "contributors": [
        {
            "name": "Chris Finch",
            "url": "https://github.com/chrisfinch"
        },
        {
            "name": "Thomas Parisot",
            "url": "https://github.com/oncletom"
        },
        {
            "name": "Chris Needham",
            "url": "https://github.com/chrisn"
        }
    ],
    "dependencies": {
        "eventemitter2": "~1.0.0",
        "konva": "~1.2.2",
        "waveform-data": "^2.0.0"
    },
    "description": "Frontend app for displaying audio waveforms",
    "devDependencies": {
        "browserify": "^13.0.0",
        "chai": "^3.0.0",
        "deamdify": "^0.2.0",
        "derequire": "^2.0.3",
        "eslint": "^3.2.2",
        "exorcist": "^0.4.0",
        "github-changes": "^1.0.0",
        "jsdoc": "~3.4.1",
        "karma": "^1.1.0",
        "karma-browserstack-launcher": "^1.0.0",
        "karma-chrome-launcher": "^1.0.0",
        "karma-firefox-launcher": "^1.0.0",
        "karma-html2js-preprocessor": "^1.0.0",
        "karma-ievms": "^0.1.0",
        "karma-mocha": "^1.0.0",
        "karma-safari-launcher": "^1.0.0",
        "karma-sinon-chai": "^1.0.0",
        "karma-spec-reporter": "~0.0.26",
        "mocha": "^2.5.0",
        "serve": "^1.4.0",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4e6e7124d125eec5f163c7fce2827004f2207a5e",
        "tarball": "https://registry.npmjs.org/peaks.js/-/peaks.js-0.6.0.tgz"
    },
    "gitHead": "c754d43737332cee96e992fe543d8be99b6609ff",
    "homepage": "https://github.com/bbc/peaks.js#readme",
    "keywords": [
        "audio",
        "visualisation",
        "bbc",
        "webaudio",
        "browser",
        "interactive",
        "waveform"
    ],
    "license": "LGPL-3.0",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "bbcrd"
        },
        {
            "name": "chrisneedham"
        },
        {
            "name": "oncletom"
        }
    ],
    "name": "peaks.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/bbc/peaks.js.git"
    },
    "scripts": {
        "build": "npm run build:main && npm run build:standalone",
        "build:main": "browserify -e ./src/main.js -t deamdify | derequire - > index.js",
        "build:standalone": "browserify -d -e ./src/main.js -t deamdify -s peaks | exorcist peaks.js.map | derequire - > peaks.js",
        "changelog": "github-changes -o bbc -r peaks.js -n ${npm_package_version} --only-pulls --use-commit-body --file CHANGELOG.${npm_package_version}.md",
        "doc": "jsdoc --private --destination docs --recurse src",
        "lint": "eslint src/**/*.js test/**/*.js",
        "prebuild": "npm run lint",
        "prepublish": "npm run build",
        "prestart": "npm run build",
        "pretest": "npm run build",
        "start": "serve --cors -p 9000",
        "test": "./node_modules/karma/bin/karma start",
        "test-watch": "npm test -- --auto-watch --no-single-run"
    },
    "version": "0.6.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
