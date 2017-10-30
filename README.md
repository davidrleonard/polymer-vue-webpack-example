# Polymer + Vue + Webpack

Simple example that shows how Polymer v1 and Vue v2 can be loaded/bundled together by Webpack to create an app.

The following are used in this project:

* [polymer-webpack-loader](https://github.com/webpack-contrib/polymer-webpack-loader) - Used to load HTML imported files in JavaScript (in .js or .vue files). See webpack.config.js for the configuration, index.html for the required bundle loading process, and App.vue for an example of importing the px-toggle component.
* [vue-cli](https://github.com/vuejs/vue-cli) + [webpack-simple template](https://github.com/vuejs-templates/webpack-simple) - The template used to start this project. I opted for the webpack-simple variant vs. the complex webpack variant because the complex one does a lot of magic that makes it hard to know what's going on. This simpler version shows only the parts of the configuration/loading/import/bundling process that are specific to loading Polymer component over HTML imports. It's up to you to figure out how to integrate it into more complex webpack build pipelines.

## Setup

``` bash
# install dependencies
npm install
bower install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
