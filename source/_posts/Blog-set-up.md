---
title: Hexo架站心得與筆記
date: 2023-01-18 22:33:37
tags:
categories: 
- [Blog]
---

 終於！弄好了一個屬於自己的網站٩(˃̶͈̀௰˂̶͈́)و

<!-- more -->

之前雖然已經嘗試過了好幾個主流的網誌平台，但因為編輯界面用起來不太習慣的關係，導致什麼都沒有的空白網誌無限增加（爆）

最後還是選擇了用Hexo這個網誌框架，套用了主題NexT後再用GitHub Pages來呈現內容。

簡單列一下目前使用下來的優缺點：

### 優點：
- 載入速度快
- 可以直接用Markdown撰寫文章
- 可以追加功能、個人化細節，自由度高
- Github查看歷史紀錄很方便，安全感滿滿
- 不用自己維護伺服器

### 缺點：
- 基本上只能從電腦操作
- 比較難有其他平台那樣的社交連結
- 一路上可能會遇到很多困難，都要自己動手解決ಥ_ಥ不太推薦給完全沒接觸過這一塊的人


在架設的過程中參考了很多網路上的教學文章，[這篇](https://hackmd.io/@Heidi-Liu/note-hexo-github)寫得很清楚，照著步驟順利地完成了環境設置和部署。

主題的部分則是直接照著[官方文件](https://theme-next.js.org/)的說明進行。比較需要注意的大概是版本資訊，因為有過大更新的關係，有些教學文章的內容已經不能照用了。

### 其他設置
- 站內搜尋 [Ref](https://theme-next.js.org/docs/third-party-services/search-services.html#Local-Search)
hexo-generator-searchdb 
- 隱藏文章 [Ref](https://www.0412.cyou/type/heyc.html)
hexo-hide-posts 
`hidden: true`
- 搜索框 [Ref](https://blog.zzbd.org/2015/04/22/custom-search-btn/)
- 評論 [Ref](https://uchuhimo.me/2017/04/11/genesis/#%E6%B7%BB%E5%8A%A0%E8%AF%84%E8%AE%BA%E7%B3%BB%E7%BB%9F)
- 文章上鎖 [Ref](https://github.com/D0n9X1n/hexo-blog-encrypt/blob/master/ReadMe.zh.md)
hexo-blog-encrypt
`password:xxxxx`
- 生成類別介面 [Ref](https://github.com/hexojs/hexo-generator-category)
hexo-generator-category

（陸續追加中）

以上！雖然過程比較麻煩但目前用起來很滿意，今後應該會常駐在這。
許願一下希望至少2023內不會中斷更新...😊（沒志氣