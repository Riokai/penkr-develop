# 朋客商户端前端说明文档

### 开发
```javascript
grunt dev:admin
```
![运行截图](./images/1.png)


#### 启动的任务

* cssmin:admin将使用到的CSS文件打包成一个单独的vendor.css，便于节省页面打开时间
![打包CSS](./images/2.png)

* replace:dev替换`index.html`文件中的代码进入开发模式（启动livereload，JS文件无缓存）


* sass

将`sass`文件编译打包成单独的文件`main.css`


autoprefixer 

添加浏览器厂商前缀


connect:livereload

修改文件后立即刷新


watch

监听文件变化
![watch](./images/3.png)


### 打包
```javascript
grunt build:admin
```

