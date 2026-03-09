---
title: "线刷过程中出现'no such partition'的解决办法"
date: 2026-03-09T15:34:30-04:00
categories:
  - blog
tags:
  - Android
---

  在给 Redmi Pad Pro更新系统时，采用小米官方提供的刷机包刷机失败。运行脚本flash_all.bat后检查记录，发现报错 `no such partition`。

  经过分析给出以下办法：修改脚本跳过报错分区即可。