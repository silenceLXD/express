# express
express demo 本demo是用Express应用生成器快速创建的一个应用骨架

通过如下命令安装：

$ npm install express-generator -g

然后安装所有依赖包：

$ cd myapp $ npm install

启动这个应用（MacOS 或 Linux 平台）：

$ DEBUG=myapp npm start

然后在浏览器中打开 http://localhost:3000/ 网址就可以看到这个应用了。

通过 Express 应用生成器创建的应用一般都有如下目录结构：

├── app.js 
├── bin 
│ └	── www 
├── package.json 
├── public 
│ 	├── images 
│ 	├── javascripts 
│ 	└── stylesheets 
│ 	└── style.css 
├── routes 
│ 	├── index.js 
│ 	└── users.js 
└── views 
	├── error.jade 
	├── index.jade 
	└── layout.jade

7 directories, 9 files
