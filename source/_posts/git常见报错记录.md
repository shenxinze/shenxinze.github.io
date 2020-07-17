---
title: git常见报错记录
categories: [web前端]
tags: [git]
---

## 1.git pull 报错 fatal: refusing to merge unrelated histories
---

### 问题产生原因
> git merge command拒绝合并不共享同一祖先的历史记录。通常是直接把本地项目上传到远程仓库，从远程克隆下来的项目不会存在这个问题

### 解决方法
```
$ git pull origin master –allow-unrelated-histories
```

<!--more-->