# npmdoc-swagger-editor

#### basic api documentation for  [swagger-editor (v3.0.7)](https://github.com/swagger-api/swagger-editor#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-swagger-editor.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-swagger-editor) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-swagger-editor.svg)](https://travis-ci.org/npmdoc/node-npmdoc-swagger-editor)

#### Swagger Editor

[![NPM](https://nodei.co/npm/swagger-editor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-editor)

- [https://npmdoc.github.io/node-npmdoc-swagger-editor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-editor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-editor/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-swagger-editor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-swagger-editor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browserslist": [
        "> 1%",
        "last 2 versions",
        "IE 10"
    ],
    "bugs": {
        "url": "https://github.com/swagger-api/swagger-editor/issues"
    },
    "config": {
        "deps_check_dir": ".deps_check"
    },
    "contributors": [
        {
            "url": "in alphabetical order"
        },
        {
            "name": "Anna Bodnia"
        },
        {
            "name": "Buu Nguyen"
        },
        {
            "name": "Josh Ponelat"
        },
        {
            "name": "Kyle Shockey"
        },
        {
            "name": "Robert Barnwell"
        },
        {
            "name": "Sahar Jafari"
        }
    ],
    "dependencies": {
        "boron": "^0.2.3",
        "immutable": "^3.x.x",
        "js-yaml": "^3.5.5",
        "json-beautify": "^1.0.1",
        "jsonschema": "^1.1.0",
        "react": "^15.x",
        "react-addons-css-transition-group": "^15.4.2",
        "react-dd-menu": "^2.0.0",
        "react-dom": "^15.x",
        "react-file-download": "^0.3.2",
        "react-redux": "^4.x.x",
        "redux": "^3.x.x",
        "swagger-ui": "^3.0.7",
        "webpack-dev-server": "1.14.0"
    },
    "description": "Swagger Editor",
    "devDependencies": {
        "autoprefixer": "6.6.1",
        "babel-core": "^6.23.1",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.3.2",
        "babel-plugin-module-alias": "^1.6.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-es2015-ie": "^6.6.2",
        "babel-preset-react": "^6.23.0",
        "babel-preset-stage-0": "^6.22.0",
        "babel-runtime": "^6.23.0",
        "brace": "^0.10.0",
        "css-loader": "0.22.0",
        "deep-extend": "^0.4.1",
        "deepmerge": "^1.3.2",
        "eslint": "^2.13.1",
        "eslint-plugin-react": "^4.3.0",
        "extract-text-webpack-plugin": "0.8.2",
        "file-loader": "0.8.4",
        "html-webpack-plugin": "^2.28.0",
        "http-server": "^0.9.0",
        "imports-loader": "0.6.5",
        "json-loader": "0.5.3",
        "karma": "^0.13.22",
        "karma-chrome-launcher": "^0.2.3",
        "karma-mocha": "^0.2.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "1.8.0",
        "less": "2.5.3",
        "less-loader": "2.2.1",
        "license-checker": "^8.0.4",
        "lodash": "^4.17.4",
        "matcher": "^0.1.2",
        "mocha": "^3.2.0",
        "npm-run-all": "3.1.1",
        "null-loader": "0.1.1",
        "open": "0.0.5",
        "postcss-loader": "0.7.0",
        "promise-worker": "^1.1.1",
        "raw-loader": "0.5.1",
        "react-ace": "^4.1.6",
        "react-hot-loader": "^1.3.1",
        "react-immutable-proptypes": "^2.1.0",
        "reselect": "^2.5.4",
        "rimraf": "^2.6.0",
        "standard": "^8.6.0",
        "standard-loader": "^5.0.0",
        "style-loader": "0.13.0",
        "url-loader": "0.5.6",
        "webpack": "^1.14.0",
        "webpack-bundle-size-analyzer": "^2.5.0",
        "worker-loader": "^0.7.1",
        "yaml-js": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "c8722a99b4293bb7b860531e2795f101dd8d4293",
        "tarball": "https://registry.npmjs.org/swagger-editor/-/swagger-editor-3.0.7.tgz"
    },
    "gitHead": "67bf5a2c0f0c09ad01380eee7790f01608b114cb",
    "homepage": "https://github.com/swagger-api/swagger-editor#readme",
    "license": "Apache-2.0",
    "main": "dist/swagger-editor.js",
    "maintainers": [
        {
            "name": "mohsen"
        },
        {
            "name": "swagger"
        },
        {
            "name": "swagger-api"
        }
    ],
    "name": "swagger-editor",
    "optionalDependencies": {
        "webpack-dev-server": "1.14.0"
    },
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/swagger-api/swagger-editor.git"
    },
    "scripts": {
        "build": "npm run build-core && npm run build-bundle",
        "build-bundle": "webpack --config webpack-dist-bundle.config.js --colors",
        "build-core": "webpack --config webpack-dist.config.js --colors",
        "deps-check": "npm run deps-license && npm run deps-size",
        "deps-license": "license-checker --production --csv --out $npm_package_config_deps_check_dir/licenses.csv && license-checker --development --csv --out $npm_package_config_deps_check_dir/licenses-dev.csv",
        "deps-size": "webpack -p --config webpack.check.js --json | webpack-bundle-size-analyzer >| $npm_package_config_deps_check_dir/sizes.txt",
        "dev": "npm-run-all --parallel hot-server open-dev watch",
        "hot-server": "webpack-dev-server --host 0.0.0.0 --config webpack-hot-dev-server.config.js --inline --hot --progress",
        "just-test": "karma start --config karma.conf.js",
        "just-test-in-node": "mocha --recursive --compilers js:babel-core/register test/plugins",
        "lint": "eslint --cache --ext '.js,.jsx' src test",
        "lint-errors": "eslint --cache --quiet --ext '.js,.jsx' src test",
        "lint-fix": "eslint --cache --ext '.js,.jsx' src test --fix",
        "open-dev": "sleep 3 && node -e 'require(\"open\")(\"http://localhost:3200\")'",
        "open-static": "node -e 'require(\"open\")(\"http://localhost:3001\")'",
        "predev": "npm install",
        "prestart": "npm install",
        "serve-static": "http-server -i -a 0.0.0.0 -p 3001",
        "start": "npm-run-all --parallel serve-static open-static",
        "test": "npm run lint-errors && npm run just-test-in-node",
        "test-in-node": "npm run lint-errors && npm run just-test-in-node",
        "watch": "webpack --config webpack.config.js --watch --progress"
    },
    "version": "3.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
