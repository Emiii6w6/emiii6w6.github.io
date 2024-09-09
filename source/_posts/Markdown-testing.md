---
title: Markdown筆記
date: 2023-01-19 12:14:56
tags: [blog, hexo]
categories: 
- Blog
---

參照了[這個網站](https://www.markdownguide.org/basic-syntax/)來測試Markdown的展示效果。

<!-- more -->

# 標題

```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
// #後要空格、標題後要換行
```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5

# 粗體

```
**Bold text**
__Bold text__
// 可以併用
```
**Bold text**
__Bold text__

# 斜體

```
*Italic text*
_Italic text_
```
*Italic text*
_Italic text_

# 刪除線

```
~~刪除~~
```
~~刪除~~

# 引用

```
> 你好，再見
// 可以引用再引用
// 引用的內文也可以套用其他語法
```
> 你好，再見

# 有序列表

```
1. First item
2. Second item
3. Third item
```
1. First item
2. Second item
3. Third item

# 無序列表

```
- First item
- Second item
- Third item
    - Indented item
    - Indented item

* First item
* Second item
* Third item

+ First item
+ Second item
+ Third item
```
- First item
- Second item
- Third item
    - Indented item
    - Indented item

* First item
* Second item
* Third item

+ First item
+ Second item
+ Third item

# 連結

```
Markdown的參考網站是[這個](<https://www.markdownguide.org>)。
<https://www.markdownguide.org>
```
Markdown的參考網站是[這個](<https://www.markdownguide.org>)。
<https://www.markdownguide.org>

# 圖片

```
- 使用Local Files新增圖片
![acnhss](source/images/acnh001.jpeg)
- 使用URL新增圖片
![acnhss](https://images.plurk.com/R5Kxh0rvyKOAQHzuK3LHA.jpg "動森截圖")
- 在圖片上增加連結
[![acnhss](https://images.plurk.com/R5Kxh0rvyKOAQHzuK3LHA.jpg "動森截圖")](https://www.nintendo.co.jp/switch/acbaa/index.html)
```
- 使用Local Files新增圖片
![acnhss](source/images/acnh001.jpeg)
- 使用URL新增圖片
![acnhss](https://images.plurk.com/R5Kxh0rvyKOAQHzuK3LHA.jpg "動森截圖")
- 在圖片上增加連結
[![acnhss](https://images.plurk.com/R5Kxh0rvyKOAQHzuK3LHA.jpg "動森截圖")](https://www.nintendo.co.jp/switch/acbaa/index.html)

# 程式碼

```
`Code`
```

# 參考文獻

```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

# 表格

```
| 標題1 | 標題2 | 標題3 |
| :------ | :------: | ------: |
| 置左 | 置中 | 置右 |
| 這是測試文字 |  這是測試文字 | 這是測試文字 |
```
| 標題1 | 標題2 | 標題3 |
| :------ | :------: | ------: |
| 置左 | 置中 | 置右 |
| 這是測試文字 |  這是測試文字 | 這是測試文字 |

