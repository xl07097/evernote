# 第3节：nodejs 配置

---

1. 全局包安装位置与缓存包位置
   * npmrc 配置文件
  
    ```
    cache=d:\node_cache
    prefix=d:\node_global
    ```

   * 命令行

   ```

    npm config set cache 'd:\node_cache'
    npm config set prdfix 'd:\node_global'
   ```

   ps: 自定义全局文件夹时，需要添加到环境变量

2. taobao 镜像
   * 命令行
    ```
    npm config set registry 'https:\\registry.npm.taobao.org'
    ```

    ```

    cache=D:\Program Files\nodejs\node_cache
    prefix=D:\Program Files\nodejs\node_global
    proxy=null
    //registry.npmjs.org/:_authToken=be826149-dfed-4e04-9df6-f507ab2ee08b
    registry=https://registry.npm.taobao.org
    phantomjs_cdnurl=http://cnpmjs.org/downloads
    sass_binary_site=https://npm.taobao.org/mirrors/node-sass/
    ```