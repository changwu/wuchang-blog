# 阿昌De博客 · 静态重建版

原站是 Tumblr 上的个人博客（域名 `wuchang.me`，2012–2013）。
2026 年 11 月从 [互联网档案馆](https://web.archive.org/web/*/wuchang.me) 取回内容，
重建为纯静态站点，托管在 GitHub Pages。

当前保留 9 篇。

## 目录结构

```
.
├── index.html          首页（文章时间流）
├── archive.html        归档
├── about.html          关于
├── 404.html            自定义 404
├── p/                  文章永久页
├── post/<id>/          旧 Tumblr 链接跳转页
├── images/             头像、照片、视频封面
├── assets/style.css    样式
├── CNAME               自定义域名
└── .nojekyll           关闭 Jekyll 处理
```

## 本地预览

```bash
python -m http.server 8000
# 打开 http://localhost:8000
```

## 内容说明

- 保留文章：标题、日期、正文、标签保持原样。
- 照片：原图从 Tumblr 取回（1280px），已入库，不依赖外链。
- 两篇视频：Tumblr 视频文件已失效，保留封面画面并加注说明。
- 版式：全新设计，未沿用原 Tumblr 主题。
