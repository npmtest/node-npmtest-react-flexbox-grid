# npmtest-react-flexbox-grid

#### basic test coverage for  [react-flexbox-grid (v1.0.2)](https://github.com/roylee0704/react-flexbox-grid)  [![npm package](https://img.shields.io/npm/v/npmtest-react-flexbox-grid.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-flexbox-grid) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-flexbox-grid.svg)](https://travis-ci.org/npmtest/node-npmtest-react-flexbox-grid)

#### A set of React components implementing flexboxgrid with the power of CSS Modules

[![NPM](https://nodei.co/npm/react-flexbox-grid.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-flexbox-grid)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-flexbox-grid/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-flexbox-grid/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-flexbox-grid/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/test-report.html](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-flexbox-grid/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-flexbox-grid/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-flexbox-grid/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-flexbox-grid/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-flexbox-grid/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-flexbox-grid",
    "description": "A set of React components implementing flexboxgrid with the power of CSS Modules",
    "homepage": "https://github.com/roylee0704/react-flexbox-grid",
    "version": "1.0.2",
    "main": "lib/index.js",
    "author": {
        "name": "Roy Lee"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/roylee0704/react-flexbox-grid.git"
    },
    "bugs": {
        "url": "https://github.com/roylee0704/react-flexbox-grid/issues"
    },
    "keywords": [
        "css modules",
        "flexbox",
        "grid",
        "react",
        "react-component"
    ],
    "dependencies": {
        "flexboxgrid": "^6.3.0"
    },
    "devDependencies": {
        "@types/react": "*",
        "autoprefixer": "^6.0.3",
        "babel-cli": "^6.4.0",
        "babel-core": "^6.4.0",
        "babel-eslint": "^5.0.0-beta6",
        "babel-loader": "^6.2.1",
        "babel-plugin-react-transform": "^2.0.0",
        "babel-polyfill": "^6.3.14",
        "babel-preset-es2015-loose": "^6.1.4",
        "babel-preset-react": "^6.3.13",
        "babel-preset-react-hmre": "^1.0.1",
        "babel-preset-stage-0": "^6.3.13",
        "cpx": "^1.2.1",
        "cross-env": "^1.0.4",
        "css-loader": "^0.21.0",
        "eslint": "^1.10.1",
        "eslint-config-airbnb": "^1.0.0",
        "eslint-plugin-react": "^3.10.0",
        "expect": "^1.13.0",
        "express": "^4.13.3",
        "extract-text-webpack-plugin": "^0.8.2",
        "flexboxgrid": "^6.3.0",
        "isparta": "^4.0.0",
        "jsdom": "^7.0.2",
        "karma": "^0.13.3",
        "karma-chrome-launcher": "^0.2.0",
        "karma-cli": "^0.1.0",
        "karma-mocha": "^0.2.0",
        "karma-phantomjs-launcher": "~0.2",
        "karma-webpack": "^1.7.0",
        "mocha": "^2.3.4",
        "node-sass": "^3.4.2",
        "phantomjs": "^1.9.19",
        "postcss-loader": "^0.7.0",
        "react": "^15.2.0",
        "react-addons-test-utils": "^15.2.0",
        "react-dom": "^15.2.0",
        "react-hot-loader": "^1.3.0",
        "redbox-react": "^1.1.1",
        "rimraf": "^2.4.4",
        "sass-loader": "^3.1.2",
        "style-loader": "^0.12.3",
        "webpack": "^1.12.9",
        "webpack-dev-middleware": "^1.4.0",
        "webpack-hot-middleware": "^2.4.1"
    },
    "scripts": {
        "build": "cross-env NODE_ENV=production npm run compile",
        "clean": "rimraf ./lib",
        "compile": "./node_modules/.bin/babel -d ./lib ./src",
        "lint": "eslint src test",
        "patch": "bumped release patch",
        "prebuild": "npm run clean",
        "prepublish": "npm run build",
        "release": "bumped release",
        "start": "cross-env NODE_ENV=development UV_THREADPOOL_SIZE=100 node ./server",
        "test": "cross-env NODE_ENV=test karma start",
        "test:watch": "cross-env NODE_ENV=test karma start --no-single-run"
    },
    "license": "MIT",
    "peerDependencies": {
        "react": "^0.14.3 || ^15.0.0"
    },
    "types": "react-flexbox-grid.d.ts",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
