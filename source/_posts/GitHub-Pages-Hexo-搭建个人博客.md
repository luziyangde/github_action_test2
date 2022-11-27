---
title: GitHub Pages & Hexo 搭建个人博客
date: 2022-11-18 14:59:56
tags: 
  - hexo 
  - GitHub Pages
---

## GitHub Pages

[GitHub Pages 快速入门 - GitHub Docs](https://docs.github.com/cn/pages/quickstart)


## Hexo

[One-Command Deployment | Hexo](https://hexo.io/docs/one-command-deployment)

### 基本操作

```sh
# 生成/public 文件夹，里面是网站
hexo g

# 把这个网站文件夹推送到服务器
hexo d

# 删除网站文件夹
hexo clean

# 本地查看效果
hexo s
```

### 写文章 & 页面

```shell
# 写新文章
hexo new "article name"

# 创建新页面（ 在source/about 里面产生新文件）
hexo new page about
```

