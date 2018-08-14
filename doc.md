# 初始化webpack
  1、首先安装npm 设置淘宝镜像(npm config set registry http://registry.npm.taobao.org/)
  
  2、到指定文件夹下面执行: npm init。然后根据提示填写内容，也可一直回车就可以看到当前文件生成一个package.js文件。
  
  3、安装webpack(我安装的是webpack2.2.0版本)
    a、可以用npm view 查看安装包的信息
      例如：npm view webpack versions json => 查看npm上所有webpack的版本的信息
    b、使用命令: npm i -D webpack@2.2.0 在开发环境安装webpakc，安装成功后会出现node_modules目录和package-lock.json文件
    
  4、安装path: npm d -D path  由于各系统之前读取路径的方式不一样用path模块获取绝对路径 
        文档链接=>http://nodejs.cn/api/path.html#path_path_resolve_paths
        
  5、创建webpack配置文件: touch webpack.config.js  =>  当前目录webpack.config.js文件
  
  6、安装html-webpack-plugin： npm i -D html-webpack-plugin 
  
  7、安装babel： npm i -D babel-loader babel-core babel-preset-es2015 babel-preset-react babel-preset-stage-1 webpack （安装最新稳定版即可）
  
  8、安装react：npm i -D react react-dom
  
  9、安装webpack-dev-server: npm i -D webpack-dev-server@2.9.7(注意有版本兼容问题)