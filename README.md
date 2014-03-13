用[Jingle](https://github.com/shixy/Jingle "https://github.com/shixy/Jingle")框架开发的Eoe新闻资讯webapp,开放源码供大家学习参考。

###WebApp地址###
[http://migrator.duapp.com/static/eoe](http://migrator.duapp.com/static/eoe "http://migrator.duapp.com/static/eoe")
#### 二维码 ####
![](assets/images/eoe-jingle.png)

###本地环境搭建###
因为涉及到跨域问题，需要服务端做一个代理。

我采用的是Nodejs,你可以根据自己的知识架构来做调整(Apache\Nginx等等)。

1. 安装nodejs插件(只有connect)
	
	> npm install;

2. 运行nodejs 
	
	> node server.js

3. 浏览器访问：http://localhost:3000

###截图欣赏###
![](screenshots/1.jpg) ![](screenshots/2.jpg) ![](screenshots/3.jpg)


**还有个功能稍微丰富的一点的版本，我已通过Phonegap打包成了APK**

源码传送门：[源码在此](https://github.com/shixy/eoeh5)