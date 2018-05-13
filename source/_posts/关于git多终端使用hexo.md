---
title: 关于git多终端使用hexo
date: 2018-05-05 22:53:42
tags: git
---

在github上建立branch分支blog，存放源代码。

切换并建立分支命令：git checkout -b blog

加入远程仓库连接：git remote add blog git@github.com:XXX/XXX.git

删除远程仓库命令：git push origin --delete XXX

git add .

git commit -m '2018'

git push -f blog blog

提交远程仓库

在其他终端使用 git pull blog blog即可同步源代码。