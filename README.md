# 昆城广场官网升级演示部署包

这个目录是可直接上传的纯静态网站。

## 默认入口

- `index.html`：PC 端提案总览，适合发给对方在电脑上看
- `wechat-pack.html`：微信沟通图页面，适合手机打开
- `wechat-01-cover.png` 到 `wechat-04-growth.png`：可直接发微信的四张图

## 推荐免费部署方式

首选：腾讯云 EdgeOne Pages 免费静态托管。

原因：

- 国内访问体验通常比 GitHub Pages、Vercel、Netlify 更稳
- 支持静态 HTML
- 可绑定自定义域名
- 免费额度适合临时提案演示

上传方式：

1. 登录腾讯云 EdgeOne Pages
2. 新建静态站点
3. 上传本目录内所有文件
4. 发布后得到一个公网 URL
5. 发给客户 `index.html` 对应的默认访问地址

如果有公司服务器，也可以直接把本目录上传到：

`https://你的域名/kunshan-proposal/`

对方访问：

`https://你的域名/kunshan-proposal/`

