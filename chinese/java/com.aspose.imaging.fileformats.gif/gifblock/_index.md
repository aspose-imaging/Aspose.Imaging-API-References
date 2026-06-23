---
title: "GifBlock"
second_title: "Aspose.Imaging for Java API 参考"
description: "默认的 gif 块实现。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

默认的 gif 块实现。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | 扩展引入符。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isChanged()](#isChanged--) | 获取或设置一个值，指示块是否已更改且需要保存。 |
| [setChanged(boolean value)](#setChanged-boolean-) | 获取或设置一个值，指示块是否已更改且需要保存。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将块保存到指定的流。 |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


扩展引入符。

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


获取或设置一个值，指示块是否已更改且需要保存。

值：如果块已更改则为 `true`；否则为 `false`。

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


获取或设置一个值，指示块是否已更改且需要保存。

值：如果块已更改则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


将块保存到指定的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 用于保存数据的流。 |

