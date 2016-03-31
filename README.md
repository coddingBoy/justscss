# justscss


## 目录

* [使用说明](#使用说明)
  * [安装](#安装)
  * [susy](#susy)
  	* [接口介绍](#接口介绍)


<a name="使用说明"></a>
## 使用说明

<a name="安装"></a>
### 安装

* 安装compass: <http://www.ruanyifeng.com/blog/2012/11/compass.html>

* 安装nodejs

* 安装webpack

	$
	
	$ npm install justscss --save-dev
	
								

	$ 编辑webpack.config.js
	
			loaders: [{
            test: /\.scss$/,
            loader: "style!css!sass?outputStyle=expanded&includePaths[]=" + path.resolve(__dirname, "./external_modules/justscss/src/compass") + "&includePaths[]=" + path.resolve(__dirname, "./external_modules/justscss/src")

        }			

	
<a name="susy"></a>
### susy

<a name="接口介绍"></a>
#### 接口介绍

使用案例
https://github.com/tanchongshi/webpack-compass-example


## 其他

未完待续



