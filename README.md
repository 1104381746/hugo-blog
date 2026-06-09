# Luhong's Blog

基于 [Hugo](https://gohugo.io/) 构建的个人技术博客，使用 [LoveIt](https://github.com/dillonzq/LoveIt) 主题。

线上地址：https://blog.luhg.cn/

## 内容分类

- AI 知识 — 大语言模型原理、Transformer、Prompt Engineering 等
- AI 工具 — CC Switch、Claude Code、Codex CLI、Codex Desktop、MCP
- 数据库 / Redis / JVM / 服务器 / 系统 — 后端技术笔记

## 技术栈

- Hugo 0.163.0（Extended）
- LoveIt 主题（Git Submodule）
- GitHub Actions 自动部署至 GitHub Pages

## 本地开发

```bash
# 克隆（含子模块）
git clone --recursive https://github.com/1104381746/hugo-blog.git
cd hugo-blog

# 启动开发服务器
hugo server -D
```

## 部署

推送到 `main` 分支后，GitHub Actions 自动执行 `hugo --minify` 并部署到 GitHub Pages。

## 项目结构

```
content/posts/   — 博客文章（按分类目录组织）
data/            — 分类层级等数据文件
layouts/         — 自定义模板覆盖
static/          — 静态资源（图片等）
themes/LoveIt/   — 主题（子模块）
```

## License

MIT
