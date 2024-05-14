## 使用说明 :id=index
- 全局安装：docsify-cli 工具，可以方便地创建及在本地预览生成的文档。
```bash
npm i docsify-cli -g
```
- 初始化
```bash
docsify init docs
```
- 启动
```bash
docsify serve docs
```
- 预览
```bash
http://localhost:3000
```
- 部署到 GitHub Pages  
Settings->Pages->Source(GitHub Actions)->Static HTML(Configure)->右上角绿色Commit changes...即开始部署项目->点击导航Actions可查看部署进度，部署完成可以到 （Settings->Pages->查看部署后的链接，如：https://yilua.github.io/docs/ 可以配置自定义域名， Custom domain -> [git.youhao123.cn](https://git.youhao123.cn) 腾讯云解析：CNAME 值为 yilua.github.io 注：等一段时间就可以完成 DNS check successful
- [参考文档](https://docsify.js.org/#/zh-cn/)

## 目录大纲
```
│  favicon.ico     logo
│  index.html      入口文件
│  README.md       会做为主页内容渲染
│  _coverpage.md   封面
│  _navbar.md      导航
│  _sidebar.md     侧边栏
│
├─img
│      logo.png
│
└─note
        note-01.md
        note-02.md
        note-03.md
```

## [谷歌分析用户行为](https://analytics.google.com/analytics/web)
- 将一下代码紧跟在`<head>`标签后
```js
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-D5RESVR81N"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-D5RESVR81N');
</script>
```