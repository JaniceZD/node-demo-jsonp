# node-demo-jsonp


## 启动应用

`node server.js 8888`

或者

`node server 8888`

## 添加路由

1. 编辑 server.js 文件，添加 if else
2. 重新运行 node server.js 8888


## 添加jsonp跨域访问
1. 需在本地设置host文件 
   127.0.0.1 frank.com
   127.0.0.1 jack.com
2. 运行 node server.js 8001
   运行 noed server.js 8002


## 后台启动应用

`node server.js 8888 >! log 2>&1 &`
