---
title: 重新开启hexo
tags: 代码
---
再次在github上布署 hexo，反正每次都有很多坑。

**主要步骤**

1. 安装node.js

2.  安装git

3.  ssh-keygen -t rsa -b 4096 -C "*your email*"

   记得把 SSH keys 添加到github上  Personal settings ->SSH keys->Add SSH keys

   先测试一下

   ssh -T git@github.com

   Hi Xuser! You've successfully authenticated ......

   **进入~/.ssh 文件夹**

4. npm install hero-cli -g

5. hero init blog

6. cd blog

7. nam install 

8. hexo s

   出现error:deployer not found:git

9. **npm install hero-deployer-git**



