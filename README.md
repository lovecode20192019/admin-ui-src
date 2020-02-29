**演示** https://lovecode20192019.github.io/admin-ui

## 编译步骤

# 下载项目源码
git clone https://github.com/lovecode20192019/admin-ui-src.git

# 进入项目目录
cd admin-ui-src

# 安装依赖，注意：请先安装node.js,因为所有的依赖包都需通过npm自动下载，
# 下载完成后会在项目的根目录下生成一个node_modules的文件下，为了加速下载，这里用的taobao上的包仓库
npm install --registry=https://registry.npm.taobao.org

# 因为项目是基于VUE的，所以编译、发布项目的时候需要VUE CLI这个组件，请通过下面命令安装：
npm install -g @vue/cli

# 上面包安装好后，通过vue ui来编译项目，cd切换到项目的文件夹下，运行如下命令启动一个可视化的界面来编译、发布项目
vue ui
这个ui界面是vue官方提供，从这里可以看到项目的一些基本情况，你还以可以直接通过这个ui界面创建基于vue的新项目
# 项目pubish后，会在项目文件夹下生成一个dist的文件夹，这个文件夹的内容就是我们最终需要部署到web站点的一些静态文件，如css，js，html

# 修改代码只需要关注src这个文件夹下的内容

## 下面是参考项目，有些成熟的组件可以直接拿来用

- [element ui组件库](https://element.eleme.cn/#/zh-CN)

## Browsers support

Modern browsers and Internet Explorer 10+.

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari |
| --------- | --------- | --------- | --------- |
| IE10, IE11, Edge| last 2 versions| last 2 versions| last 2 versions

## License

[MIT] license.


