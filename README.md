# Totality Universe 

The renderer engine for Totality.

### Features:

Features developed into, and inherited from the starter project:

* ES6 support via [babel-loader](https://github.com/babel/babel-loader)
* CSS support via [style-loader](https://github.com/webpack-contrib/style-loader)
and [css-loader](https://github.com/webpack-contrib/css-loader)
* SASS support via [sass-loader](https://github.com/jtangelder/sass-loader)
* ES6 linting via [eslint](https://www.npmjs.com/package/eslint) and
[eslint-config-airbnb](https://www.npmjs.com/package/eslint-config-airbnb) or [prettier](https://github.com/prettier/prettier)
* SASS linting via [sass-lint](https://www.npmjs.com/package/sass-lint)
* Controls via [orbit-controls-es6](https://www.npmjs.com/package/orbit-controls-es6)
* GUI via [dat.GUI](https://github.com/dataarts/dat.gui)
* GLSL shaders support via [webpack-glsl-loader](https://www.npmjs.com/package/webpack-glsl-loader)
* Webpack configuration with:
  - [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin)
  - [HtmlWebpackPlugin](https://github.com/jantimon/html-webpack-plugin)
  - [BundleAnalyzerPlugin](https://github.com/th0r/webpack-bundle-analyzer)
  - [CompressionPlugin](https://github.com/webpack-contrib/compression-webpack-plugin)
  - [CleanWebpackPlugin](https://github.com/johnagan/clean-webpack-plugin)

### Installation

```
git clone <this repo> 
cd totality-<fixme>

yarn install
```

### Usage

Generate all js/css bundles

```
yarn run build
```

Run `webpack-dev-server` (all bundles will be served from memory)

```
yarn run dev
```

If you have issues with old dependencies you can try to fix them by running:

```
yarn update:packages
```

Go to `localhost:8080` to have a good (or bad) time.

Go to `localhost:8888` to analyze the webpack bundles with the `BundleAnalyzerPlugin`


### Credits

This project was initialised from https://github.com/jackdbd/threejs-es6-webpack-starter to minimise PITA.

### Developer/s

Marlon B van der Linde <mages-guild@pm.me>


