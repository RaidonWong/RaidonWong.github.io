---
title: "你好，世界"
date: 2026-08-17 12:00:00 +0800
categories:
  - 随笔
tags:
  - 开始
  - Jekyll
excerpt: "这是我的第一篇文章，也是这个个人网站的起点。"
---

欢迎来到我的个人主页。

这是网站的第一篇文章，也是一个新的开始。之后我会在这里持续记录学习笔记、项目经验和生活中的思考。

## 如何发布新文章

在 `_posts` 目录中新建 Markdown 文件，文件名采用 `年-月-日-英文标题.md` 格式，例如：

```text
_posts/2026-08-18-my-second-post.md
```

每篇文章顶部需要一段 Front Matter：

```yaml
---
title: "文章标题"
date: 2026-08-18 09:00:00 +0800
categories:
  - 笔记
tags:
  - Jekyll
---
```

提交并推送到 GitHub 后，部署工作流会自动更新网站。
