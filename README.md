# justscss

## 目录

* [使用说明](#使用说明)
  * [安装](#安装)
  * [例子](#例子)
  	* [链接地址](#链接地址)
* [其他](#其他)


<a name="使用说明"></a>
## 使用说明

<a name="安装"></a>
### 安装

* 安装compass: <http://www.ruanyifeng.com/blog/2012/11/compass.html>

* 安装nodejs

* 安装webpack

	
	$ npm install justscss --save-dev
	
								

	$ 编辑webpack.config.js
	
			loaders: [{
            test: /\.scss$/,
            loader: "style!css!sass?outputStyle=expanded&includePaths[]=" + path.resolve(__dirname, "./external_modules/justscss/src/compass") + "&includePaths[]=" + path.resolve(__dirname, "./external_modules/justscss/src")

        }			

	
<a name="例子"></a>
### 例子

<a name="链接地址"></a>
#### 链接地址

使用案例
https://github.com/tanchongshi/webpack-compass-example

<a name="其他"></a>
## 其他

具体使用说明
https://github.com/tanchongshi/justscss/wiki



