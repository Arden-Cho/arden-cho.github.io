---
title: "GCC on Windows 環境設定"
description: "在 Windows 上使用 GCC 編譯 C / C++ 原始碼"
date: 2026-02-12T13:37:01Z
image: false
math: false
license: true
comments: false
draft: false
categories:
    - tutorials
build:
    list: always
slug: gcc-on-windows
---

## 下載檔案

前往 [WinLibs](https://winlibs.com/#download-release) 網站，下載檔案。

![下載檔案](arrow-pointing-to-link-to-download.png)

## 解壓縮檔案

將檔案解壓縮至 `C:\` 中。

![解壓縮全部](image.png)

![解壓縮至 `C:\`](image-2.png)

## 設定環境變數 PATH

按下 `Win + R` ，開啟執行視窗，輸入

```cmd
sysdm.cpl ,3
```

並按下 Enter。

![執行](image-1.png)

![修改環境變數](image-3.png)

![選擇 Path，編輯](image-4.png)

複製

```cmd
C:\mingw64\bin
```

![選擇新增，貼上，OK](image-6.png)

## 完成

![確認安裝](image-7.png)
