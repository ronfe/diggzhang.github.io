---
layout: post
title:  "(Linux) ncat tool"
date:   2015-07-14 07:39:16
categories: linux tool 
---

ncat做端口扫描:
* -v view process
* -z tcp scan
* -w out of time
```
   $ ncat -v -z -w2 10.8.8.8 1-100
```
