# npmtest-apsl-react-native-button

#### basic test coverage for  [apsl-react-native-button (v3.0.2)](https://github.com/APSL/react-native-button#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-apsl-react-native-button.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-apsl-react-native-button) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-apsl-react-native-button.svg)](https://travis-ci.org/npmtest/node-npmtest-apsl-react-native-button)

#### React Native button component with rounded corners.

[![NPM](https://nodei.co/npm/apsl-react-native-button.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/apsl-react-native-button)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-apsl-react-native-button/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-apsl-react-native-button/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-apsl-react-native-button/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-apsl-react-native-button/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/test-report.html](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-apsl-react-native-button/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-apsl-react-native-button/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-apsl-react-native-button/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-apsl-react-native-button/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-apsl-react-native-button/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "apsl-react-native-button",
    "version": "3.0.2",
    "description": "React Native button component with rounded corners.",
    "main": "Button.js",
    "scripts": {
        "lint": "eslint Button.js",
        "test": "npm run lint && jest --verbose"
    },
    "jest": {
        "preset": "jest-react-native",
        "modulePathIgnorePatterns": [
            "Example",
            "node_modules/react-native/node_modules/"
        ],
        "preprocessorIgnorePatterns": [
            "node_modules/(?!react-native|tcomb-form-native|react-native-localization|@exponent/react-native-action-sheet|rnrf-relay-renderer|redux-action-api-utils|frisbee)"
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/APSL/react-native-button.git"
    },
    "keywords": [
        "react-native",
        "ios",
        "android",
        "react-component",
        "react",
        "button"
    ],
    "author": "Alvaro Medina Ballester <me@alvaromb.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/APSL/react-native-button/issues"
    },
    "homepage": "https://github.com/APSL/react-native-button#readme",
    "dependencies": {
        "lodash.isequal": "^4.1.4"
    },
    "devDependencies": {
        "babel-eslint": "^6.0.5",
        "babel-jest": "^15.0.0",
        "babel-plugin-transform-flow-strip-types": "^6.14.0",
        "babel-preset-react-native": "^1.9.0",
        "es6-promise": "^3.3.1",
        "eslint": "^2.13.1",
        "eslint-plugin-react": "^5.2.2",
        "eslint-plugin-react-native": "^1.1.0-beta",
        "jest": "^15.1.1",
        "jest-react-native": "^15.0.0",
        "react": "^15.3.2",
        "react-native": "^0.34.0",
        "react-test-renderer": "^15.3.2",
        "whatwg-fetch": "^1.0.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
