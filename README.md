# output-webpack-plugin
output plugin for webpack

## Installation
npm
``` shell
$ npm install @arted/output-webpack-plugin
```

or yarn
``` shell
$ yarn add @arted/output-webpack-plugin
```

## Usage
``` javascript
const OutputWebpackPlugin = require('@arted/output-webpack-plugin');

// webpack.config.js
module.exports = {
	...
    plugins: [
        ...
        new OutputWebpackPlugin({ data: settings.app })
    ]
};
```
