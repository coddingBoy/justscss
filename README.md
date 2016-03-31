# justscss

![Shurnim icon](http://cocoscript.com/miofront/images/me.png)

## 目录

* [使用说明](#使用说明)
  * [安装](#安装)
  * [susy](#susy)
  	* [接口介绍](#接口介绍)


<a name="使用说明"></a>
## 使用说明

<a name="安装"></a>
### 安装

* 安装compass: <https://gitcafe.com/onecoder/shurnim-storage-for-UPYUN>

* 安装nodejs

* 安装webpack

	
	$ npm install justscss --save-dev
	
								

	2. 编辑webpack.config.js
	
			<script>
			        loaders: [{
            test: /\.scss$/,
            //loader: "style!css!sass?outputStyle=expanded&includePaths[]=" + path.resolve(__dirname, "./node_modules/compass-mixins/lib") + "&includePaths[]=" + path.resolve(__dirname, "./node_modules/susy/sass") + "&includePaths[]=" + path.resolve(__dirname, "./external_modules/Sassy-Buttons/stylesheets") + "&includePaths[]=" + path.resolve(__dirname, "./node_modules/sassy-inputs/sass")
            loader: "style!css!sass?outputStyle=expanded&includePaths[]=" + path.resolve(__dirname, "./external_modules/justscss/src/compass") + "&includePaths[]=" + path.resolve(__dirname, "./external_modules/justscss/src")

        }
			</script>

	
<a name="sussy"></a>
### susy

<a name="接口介绍"></a>
#### 接口介绍

**ShurnimStorage**接口是*shurinm-storage*框架全局的也是唯一的接口，目前定义如

## 其他

未完待续



