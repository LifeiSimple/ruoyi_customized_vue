# 若依 - 脚手架 后台前端页面

基于若依vue版本（v3.8.9）修改

## 相关版本
nodejs v16.20.2

### dayjs
```bash
安装
npm install dayjs

使用 dayjs
this.dayjs
```

## 开发
```bash
# 克隆项目
git clone https://gitee.com/y_project/RuoYi-Vue

# 进入项目目录
cd ruoyi-ui

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npmmirror.com

# 启动服务
npm run dev
```

浏览器访问 http://localhost:80

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```