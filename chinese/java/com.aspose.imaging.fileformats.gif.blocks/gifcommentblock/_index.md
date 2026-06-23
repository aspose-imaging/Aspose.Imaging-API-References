---
title: "GifCommentBlock"
second_title: "Aspose.Imaging for Java API 参考"
description: "Gif 注释块。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.gif.blocks/gifcommentblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifCommentBlock extends GifBlock
```

Gif 注释块。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifCommentBlock()](#GifCommentBlock--) | 初始化 `GifCommentBlock` 类的新实例。 |
| [GifCommentBlock(String comment)](#GifCommentBlock-java.lang.String-) | 初始化 `GifCommentBlock` 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Gif 注释块扩展标签。 |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | 定义块头部大小。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getComment()](#getComment--) | 获取或设置注释。 |
| [setComment(String value)](#setComment-java.lang.String-) | 获取或设置注释。 |
### GifCommentBlock() {#GifCommentBlock--}
```
public GifCommentBlock()
```


初始化 `GifCommentBlock` 类的新实例。

### GifCommentBlock(String comment) {#GifCommentBlock-java.lang.String-}
```
public GifCommentBlock(String comment)
```


初始化 `GifCommentBlock` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| comment | java.lang.String | 注释。 |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Gif 注释块扩展标签。

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


定义块头部大小。

### getComment() {#getComment--}
```
public String getComment()
```


获取或设置注释。注意，注释必须使用 ASCII 编码并将相应存储。

值：注释。

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


获取或设置注释。注意，注释必须使用 ASCII 编码并将相应存储。

值：注释。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

