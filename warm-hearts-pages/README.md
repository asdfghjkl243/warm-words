# 给此刻的你 · 发布到 GitHub Pages

这个文件夹就是可以直接发布的网站：**只有 `index.html` 一个文件**（`.nojekyll` 是可选的小开关，上传不了也没关系）。

## 三步发布（网页操作，约 2 分钟）

1. **建仓库**
   打开 https://github.com/new
   - Repository name：`warm-words`（名字随意，会成为网址的一部分）
   - 选 **Public**（免费版 Pages 需要公开仓库）
   - 点 **Create repository**

2. **上传文件**
   在新仓库页面点 **uploading an existing file**，把本文件夹里的 `index.html` 拖进去 → 点 **Commit changes**。

3. **开启 Pages**
   仓库 **Settings → Pages** →
   - Source 选 **Deploy from a branch**
   - Branch 选 **main**，目录选 **/ (root)** → **Save**

等 30 秒到 1 分钟，刷新该页面会显示网址：

```
https://你的用户名.github.io/warm-words/
```

（末尾的 `/` 要带上；把 `warm-words` 换成你起的仓库名）

## 想要更短的网址

把仓库名建成 `你的用户名.github.io`，网址就是 `https://你的用户名.github.io/`。

## 发到微信

- 电脑微信 → 文件传输助手 → 粘贴网址发过去 → 手机点开。
- 微信内置浏览器能直接看；页面没有任何外部依赖，加载很快。
- 想发给别人：直接把网址发给他即可。

## 如果微信里打开很慢或打不开

`github.io` 在国内部分网络下不稳定。可以换国内托管（页面是单文件，任何静态托管都能放）：

- 腾讯云 **EdgeOne Pages**（有免费额度，国内访问快）
- 阿里云 **OSS**（上传 `index.html`，开启静态网站托管，绑定域名）
- 腾讯云 **COS**（同上）

换托管时不用改任何代码，把 `index.html` 传上去即可。

## 备注

- 页面是单文件，无 JS 库、无图片、无网络请求，离线也能开。
- 手机上点屏幕会出现一圈细线涟漪并升起几颗小心；「抱抱」「换一句」可换文案。
- 文案共 12 句温柔的话 + 5 句抱抱回复，页面会自己轮播。