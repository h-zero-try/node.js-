

## 项目目录

```
| app.js              后端入口
| index.html          入口页面
| .babelrc            babel配置
| .gitignore          git配置
| package.json
| webpack.config.js   webpack配置
|
|-dist                vue打包生成的文件
|
|-node_modules        模块
|
|-server              后端
    | check.js
    | db.js           数据库
 __ | router.js       路由
|
|-src               前端
    |-assets        静态资源
    |-components    组件
    | App.vue
    | main.js
```

开始
``` bash
# clone projext
git clone https://github.com/chaohangz/blog.git

# 安装依赖
cd blog
npm install

# 启动数据库
mongod

# 启动服务器
node app

# 启动前端开发者模式
npm run dev
```
