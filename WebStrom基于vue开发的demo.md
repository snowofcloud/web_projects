### 首先安装配置node.js(前端开发必须的)

### 开发环境：

```
WebStrom2018.2，node.js，vue2.5.2;
```

### 基于vue构建一个工程：

```
1./安装好node.js，
2./打开webstrom,安装插件vue.js或vue-for-idea,
3./找一个文件用来放自动生成的web工程，进入该文件，按住shift，进入黑窗口，执行如下命令：
	npm install -g vue-cli  	--->安装全局的vue
	vue init webpack my-project --->生成my-project工程
	生成my-project工程过程中，Use ESLint to lint your code?(Y/N) 选N，暂时关闭代码检查规范，如遇选择Y了，在打开的工程中也可关闭，如下图：
```

如下图：![46335410371](C:\Users\sony\AppData\Local\Temp\1546335410371.png)







![1546335542202](C:\Users\sony\AppData\Local\Temp\1546335542202.png)





vue init webpack my-project --->生成my-project工程过程，如下图：

![1546335598760](C:\Users\sony\AppData\Local\Temp\1546335598760.png)



### 启动你的新工程：

	

```
用webStromopen打开新建立的工程：
	第一步：npm install 
	第二步：打开package.json，点击dev绿色小图标起动即可或者terminal输入命令：npm dev即可。
```

### 继续编写前端程序

```
	继续编写前端程序，按启动工程方式即可，连接后台服务在工程的根目录下新建一个vue.config.js文件，在devServer/proxy/target下面配置上后台ip地址，ok! 如下图红箭头处配置。
```

![1546336199665](C:\Users\sony\AppData\Local\Temp\1546336199665.png)











	