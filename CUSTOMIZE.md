# 个性化清单

网站已经可以部署。发布前建议修改下面几项。

## 1. 基本信息

编辑 `_config.yml`：

- `title`、`name`、`author.name`：你的显示名称
- `description`：网站简介
- `author.bio`：侧栏个人简介
- `author.location`：所在地
- `url`：当前为 `https://raidonwong.github.io`
- `repository`：当前为 `RaidonWong/RaidonWong.github.io`

添加社交链接的示例：

```yaml
author:
  links:
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      url: "https://github.com/RaidonWong"
    - label: "Email"
      icon: "fas fa-fw fa-envelope"
      url: "mailto:你的邮箱"
```

## 2. 首页和关于页

- 首页：`index.md`
- 关于页：`_pages/about.md`
- 头像：替换 `assets/images/avatar.svg`，并保持文件名不变；也可以在 `_config.yml` 中改为新的文件路径

## 3. 发布文章

把 Markdown 文章放入 `_posts`，文件名必须使用 `YYYY-MM-DD-title.md` 格式。

## 4. 部署到 GitHub Pages

1. Fork `mmistakes/minimal-mistakes`。
2. 把 Fork 后的仓库改名为 `你的用户名.github.io`。
3. 将本项目推送到该仓库。
4. 打开仓库的 **Settings → Pages**，在 **Build and deployment → Source** 中选择 **GitHub Actions**。
5. 等待 Actions 中的 `Deploy site to GitHub Pages` 运行成功。

访问地址为 `https://你的用户名.github.io/`。
