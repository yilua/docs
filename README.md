# 使用说明  <span id="index"></span>

- 初始化：`docsify init docs`
- 启动：`docsify serve docs` 访问：`http://localhost:3000`
- 部署到 Github Actions: Settings->Pages->Source(GitHub Actions)->Static HTML(Configure)->右上角绿色Commit changes...即开始部署项目->点击导航Actions可查看部署进度，部署完成可以到 （Settings->Pages->查看部署后的链接，如：https://yilua.github.io/docs/ 可以配置自定义域名， Custom domain -> git.youhao123.cn 腾讯云解析：CNAME 值为 yilua.github.io 注：等一段时间就可以完成 DNS check successful
- 参考文档：https://docsify.js.org/#/zh-cn/

# Google Analytics(用户访问分析)
- G-D5RESVR81N
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