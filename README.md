# webpack-asset-file-plugin

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/webpack-asset-file-plugin.svg?style=flat-square
[npm-url]: https://npmjs.org/package/webpack-asset-file-plugin
[travis-image]: https://img.shields.io/travis/hubcarl/webpack-asset-file-plugin.svg?style=flat-square
[travis-url]: https://travis-ci.org/hubcarl/webpack-asset-file-plugin
[codecov-image]: https://img.shields.io/codecov/c/github/hubcarl/webpack-asset-file-plugin.svg?style=flat-square
[codecov-url]: https://codecov.io/github/hubcarl/webpack-asset-file-plugin?branch=master
[david-image]: https://img.shields.io/david/hubcarl/webpack-asset-file-plugin.svg?style=flat-square
[david-url]: https://david-dm.org/hubcarl/webpack-asset-file-plugin
[snyk-image]: https://snyk.io/test/npm/webpack-asset-file-plugin/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/webpack-asset-file-plugin
[download-image]: https://img.shields.io/npm/dm/webpack-asset-file-plugin.svg?style=flat-square
[download-url]: https://npmjs.org/package/webpack-asset-file-plugin

webpack asset file plugin

## Install

npm install webpack-asset-file-plugin --save-dev

## Usage

```js
const WebpackAssetFilePlugin = require('webpack-asset-file-plugin');
module.exports = {
  plugins:[
    new WebpackAssetFilePlugin({
      assets:[
        {
          outputName: 'vendor.js',
          filepath: '/public/js/vendor.js'
        }
      ]
    })
  ]
}
```

## License

[MIT](LICENSE)
