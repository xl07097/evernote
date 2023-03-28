# 第3节：nodejs 配置

---

#### 1. 全局包安装位置与缓存包位置
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

#### 2. taobao 镜像
   * 命令行

    ```
    npm config set registry 'https://registry.npmmirror.com'
    ```

    ```.npmrc
      cache=D:\nodejs\node_cache
      prefix=D:\nodejs\node_global
      proxy=null
      registry=https://registry.npmmirror.com
      phantomjs_cdnurl=https://npmmirror.com/downloads
      sass_binary_site=https://npmmirror.com/mirrors/node-sass/
      disturl=https://registry.npmmirror.com/dist
      puppeteer_download_host=https://npmmirror.com/mirrors
      ELECTRON_MIRROR=https://npmmirror.com/mirrors/electron/
      canvas=https://npmmirror.com/mirrors/canvas/
      SQLITE3_BINARY_SITE=https://npmmirror.com/mirrors/sqlite3
    ```
