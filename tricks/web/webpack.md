# Webpack

## Tips
* [webpack](https://webpack.js.org/)
  * webpack is a module bundler for modern JavaScript applications


## Configuration
* [configuration](https://webpack.js.org/configuration/)


## Concepts
* [Concepts](https://webpack.js.org/concepts/)
* Entry
  * 入口
  * 应用的第一个文件
```js
module.exports = {
  entry: './src/main.js'
}
```
* Output
  * 输出
* Loaders
  * 将文件转换为模块作为依赖添加到依赖图中
  * 标识哪些文件应该处理, `test`
  * 将那些文件做转换, `use`
```js
module.exports = {
  module: [ rulles: [ {test: /\.txt$/, use: 'raw-loader'} ] ]
}
```
* Plugins
  * 在编译和分块(chunk)时,实现自定义功能
```js
module.exports = {
  plugins: [
    new webpack.optimize.UglifyJsPlugin(),
    new HtmlWebpackPlugin({template: './src/index.html'})
  ]
}
```
