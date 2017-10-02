# Aurelia Electron Forge

Basic template for an Electron App using Aurelia and Electron Forge.

Project is based on Electron Forge Vanilla ES6/7 template and Aurelia Skeleton Navigation template, also has SCSS styles.

*Current standing questions*:

 * Can [babel-plugin-transform-decorators-legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) be replaced with [babel-plugin-transform-decorators](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-decorators)
 * Should [babel-plugin-transform-es2015-classes](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-es2015-classes) be added
 * Is [babel-plugin-transform-async-to-generator](https://github.com/babel/babel/tree/master/packages/babel-plugin-transform-async-to-generator) needed
 * Review **.compilerc** Babel configuration
 	* Any missing plugins needed for a typical Aurelia project
 * Review **package.json**
 	* Any missing/incorrect *aurelia-** packages
