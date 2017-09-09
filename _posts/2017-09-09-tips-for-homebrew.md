---
layout:     post
title:      Some tips for Homebrew
date:       2017-09-09
summary:    brew tips, e.g. mirrors
categories: shell
---

```bash
$ echo 'export HOMEBREW_BOTTLE_DOMAIN=https://mirrors.tuna.tsinghua.edu.cn/homebrew-bottles' >> ~/.bash_profile

$ source ~/.bash_profile
 
$ brew update

$ brew upgrade

$ brew --cache 

$ brew info {formula}
```