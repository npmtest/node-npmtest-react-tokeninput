# npmtest-react-tokeninput

#### basic test coverage for  [react-tokeninput (v2.3.0)](https://github.com/instructure/react-tokeninput)  [![npm package](https://img.shields.io/npm/v/npmtest-react-tokeninput.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-tokeninput) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-tokeninput.svg)](https://travis-ci.org/npmtest/node-npmtest-react-tokeninput)

#### Tokeninput component for React

[![NPM](https://nodei.co/npm/react-tokeninput.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-tokeninput)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-tokeninput/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tokeninput/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-tokeninput/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-tokeninput/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-tokeninput/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-tokeninput/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-tokeninput/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-tokeninput/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-tokeninput/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tokeninput/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-tokeninput/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-tokeninput/build/test-report.html](https://npmtest.github.io/node-npmtest-react-tokeninput/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-tokeninput/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-tokeninput/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-tokeninput/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-tokeninput/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-tokeninput/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-tokeninput/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-tokeninput/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-tokeninput/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-tokeninput",
    "version": "2.3.0",
    "description": "Tokeninput component for React",
    "main": "lib/index.js",
    "scripts": {
        "prepublish": "babel src -d lib && npm run build",
        "build": "NODE_ENV=production webpack --config webpack.dist.config.js",
        "test": "node_modules/.bin/karma start",
        "dev": "webpack --watch --config example/webpack.config.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/instructure/react-tokeninput.git"
    },
    "author": "Aaron Shafovaloff <ashafovaloff@instructure.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/instructure/react-tokeninput/issues"
    },
    "homepage": "https://github.com/instructure/react-tokeninput",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-core": "^6.9.0",
        "babel-eslint": "^4.1.5",
        "babel-loader": "^6.2.4",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "chai": "^1.10.0",
        "eslint": "^1.10.1",
        "jsx-loader": "^0.13.2",
        "karma": "^0.13.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^0.2.1",
        "karma-cli": "0.0.4",
        "karma-firefox-launcher": "^0.1.6",
        "karma-jasmine": "^0.2.3",
        "karma-mocha": "^0.2.0",
        "karma-webpack": "^1.3.1",
        "lodash-node": "^2.4.1",
        "mocha": "^2.0.1",
        "react": "^0.14.0",
        "react-addons-test-utils": "^0.14.6",
        "react-dom": "^0.14.0",
        "webpack": "^1.12.2",
        "webpack-dev-server": "^1.12.0"
    },
    "dependencies": {
        "classnames": "^2.2.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
