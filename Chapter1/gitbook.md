# 第5节：gitbook 简单使用

---
* 1.  首先安装 `Node.js`
* 2.  使用 `npm` 命令安装 `gitbook-cli`
* 3.  新建文件夹，使用 `gitbook init` 命令初始化
* 4. 使用 `gitbook serve(gitbook serve --port 3333)` 编译预览，默认端口 `4000`
* 5. 使用 `gitbook build [书籍路径] [输出路径]` 生成文件
   * `gitbook pdf ./ ./mybook.pdf ` pdf 格式
   * `gitbook epub ./ ./mybook.epub` epub 格式电子书
   * `gitbook mobi ./ ./mybook.mobi` mobi 格式电子书