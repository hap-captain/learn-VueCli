# VueCli
>学习VueCLi的demo

*****
## 创建项目
1. 新建一个空的文件夹learn-VueCli

2. 项目初始化
在learn-VueCli文件夹下打开终端输入（需要安装node环境）
```javascript
npm install vue-cli -g
```
然后终端中输入下面命令，如果安装好则显示版本号
```javascript
vue -V
```
注：-V是大写

3. 创建项目(通过webpack构建)
```javascript
vue init webpack learn-vuecli
```
注：learn-vuecli是自己对项目的命名,命名不能包含大写字母*、
4. 按照终端提示输入命令
```javascript
cd learn-vuecli
npm install  //不成功使用 yarn install
npm run dev
```


## 项目目录

### build
与项目构建有关的文件
* build.js *生产环境构建代码*
* check-versions.js *检查 node,npm 版本*
* utils.js *构建工具相关*
* webpack.conf.js *webpack 环境配置*
* webpack.base.conf.js  *webpack 基础配置*
* webpack.dev.conf.js *webpack 开发环境配置*
* webpack.prod.conf.js *webpack 生产环境配置*

### config
项目开发环境配置
* dev.env.js *开发环境变量*
* index.js *项目一些配置变量*
* pro.env.js *生产环境变量*
* test.env.js *测试环境变量*

### node_modules
包括各种各样的资源包，类似.net code中package一样
### src
源码目录，开发写的代码放在里面
* components *vue公共组件*
* assets *放置静态资源，如公共的css，js等等文件*
* router *放置路由设置文件，指定路由对应的组件*
* App.vue *页面入口文件*
* main.js *程序入口文件，加载各种公共组件*

### static
静态文件目录，如图片等放在里面，此文件夹不会编译

### test
测试文件夹
* e2e *e2e测试*
* unit *单元测试*

### .babelrc
ES6语法编译配置

### .editorconfig
定义代码格式
### .elintignore
ESlint 文件，检查需要忽略的文件
### .eslintrc.js
ESlint文件，若修改规则可在此文件修改
### .gitignore
git上传需要忽略的文件格式
### .postcssrc.js
postcss 配置
### index.html
入口页面
### package.json
项目基本信息
### README.md
项目说明文件
