# webpack-setup
##Learning how to setup Webpack 

Webpack- Babel
At its core, webpack is a static module bundler for modern JavaScript applications
From <https://webpack.js.org/concepts/> 

npm install --save-dev @babel/core @babel/cli @babel/preset-env npm install --save @babel/polyfill

From <https://babeljs.io/docs/en/usage> 

Yarn add webpack webpack-cli
Add a new file in src called <webpack.config.js>
Add this file in to JSON package to scripts <
"build": "webpack --mode production">

Sort out the webpack.config.js and after install the babel bellow

Yarn add @babel/core @babel/preset-env @babel/preset-react babel-loader

npm install -D babel-loader @babel/core @babel/preset-env webpack

From <https://github.com/babel/babel-loader> 

yarn add style-loader css-loader
npm install --save-dev style-loader
From <https://github.com/webpack-contrib/style-loader#style-loader> 
npm install --save-dev css-loader
From <https://github.com/webpack-contrib/css-loader#css-loader> 

yarn add html-loader html-webpack-plugin
Or
npm install --save-dev html-webpack-plugin
From <https://webpack.js.org/plugins/html-webpack-plugin/#installation> 



