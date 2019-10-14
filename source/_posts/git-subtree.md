---
title: git subtree
date: 2019-10-14 19:47:17
tags:
- git
---


add subtree
git subtree add --prefix=extra  https://github.com/bylh/extra.git master

pull subtree
git subtree pull --prefix=extra  https://github.com/bylh/extra.git master

push subtree
git subtree push --prefix=extra  https://github.com/bylh/extra.git master

remove subtree
git rm -rf extra


简化subtree名称
git remote add -f extra https://github.com/bylh/extra.git

git subtree pull --prefix=extra  extra master
