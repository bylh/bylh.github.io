---
title: git subtree
date: 2019-10-14 19:47:17
tags:
  - git
---

- add subtree

  ``` bash
  git subtree add --prefix=extra  https://github.com/bylh/extra.git master
  ```

- pull subtree

  ``` bash
  git subtree pull --prefix=extra  https://github.com/bylh/extra.git master
  ```

- push subtree

  ``` bash
   git subtree push --prefix=extra https://github.com/bylh/extra.git master
  ```

- remove subtree

  ``` bash
  git rm -rf extra
  ```

- 简化 subtree 名称
  
  ``` bash
  git remote add -f extra https://github.com/bylh/extra.git
  git subtree pull --prefix=extra extra master
  ```
  