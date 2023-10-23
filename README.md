# vue-admin-template-liyangit


> 这是一个极简的 vue admin 管理后台。基于 [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template),只是以下修改，并没有更改源任何代码逻辑。

* 登录、左侧菜单栏样式修改
* PWA应用支持


[在线预览](https://liyang-it.github.io/vue-admin-template-liyangit/#/login?redirect=%2Fdashboard)

[vue-admin-template在线预览](https://panjiachen.gitee.io/vue-admin-template)


## Build Setup

```bash
# 克隆项目
git clone https://github.com/liyang-it/vue-admin-template-liyangit.git

# 进入项目目录
cd vue-admin-template-liyangit

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装以来，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```

