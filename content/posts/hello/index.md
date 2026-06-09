---
title: "博客搭建完成 🎉"
date: 2026-06-09
description: "使用 Obsidian + Hugo + LoveIt 搭建个人技术博客"
tags: ["博客", "Hugo", "Obsidian"]
categories: ["博客"]
weight: 1
---

## 博客架构

本博客基于以下技术栈搭建：

- **Obsidian** — 笔记编辑与管理
- **GitHub Sync** — 全量备份到 GitHub
- **Enveloppe** — 选择性发布笔记到博客
- **Hugo** + **LoveIt 主题** — 静态站点生成
- **GitHub Pages** — 自动部署与托管

## 发布流程

1. 在 Obsidian 中写好笔记
2. frontmatter 添加 `share: true`
3. 右键 → Enveloppe → Share this file
4. GitHub Actions 自动构建部署

## 后续计划

- 配置评论系统（giscus）
- 自定义域名
- 持续优化主题样式
