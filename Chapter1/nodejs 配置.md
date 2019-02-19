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

2. taobao 镜像
   * 命令行
    ```
    npm config set --registry='https:\\registry.npm.taobao.org'
    ```