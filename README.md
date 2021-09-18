# vite-test
了解一下vite（最佳开发体验？？？？）

vite是编译工具，使用rollup打包

开发环境中：
webpack是每次都要先打包到内存中，然后浏览器从内存中进行一个加载。要打包的原因是使用es6语法浏览器不支持，以及代码的合并。
现在浏览器对es6模块化语法也支持，vite开发环境不打包，用哪个加载哪个。
支持相对地址，像vue第三方模块会进行一个预打包
vite服务器将Vue文件解析成js文件

生产环境与webpack都是treeshaking,这个有待继续学习？？？？？

vite里的@符不支持

启动报错：https://www.jianshu.com/p/dc85066fe1fe


vite原理：