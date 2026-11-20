# newAgr-zju 班级网站

这是一个以 Markdown 为内容源的班级网站项目。页面由 MkDocs 构建，界面使用 Material for MkDocs，中文正文由 `mkdocs-heti-plugin` 在构建阶段处理，最终通过 GitHub Actions 发布到 GitHub Pages。

项目作者：newAgr-zju

## 技术组成

| 部分 | 用途 |
| --- | --- |
| MkDocs | 把 Markdown 构建为静态 HTML |
| Material for MkDocs | 页面框架、导航、搜索、深色模式和代码块 |
| `mkdocs-heti-plugin` | 构建时优化中西文间距和连续标点 |
| `WebsiteTemplate/main.html` | 主题入口，在 Material 公共布局上扩展站点元数据 |
| `docs/` | 全站 Markdown 与静态资源 |
| uv | 锁定依赖、创建虚拟环境和运行构建 |
| GitHub Actions | 构建并部署 GitHub Pages |

