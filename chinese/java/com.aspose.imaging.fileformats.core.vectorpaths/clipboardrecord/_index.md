---
title: "ClipboardRecord"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "剪贴板记录类"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.core.vectorpaths/clipboardrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class ClipboardRecord extends VectorPathRecord
```

剪贴板记录类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ClipboardRecord()](#ClipboardRecord--) | 初始化 [ClipboardRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/clipboardrecord) 类的新实例。 |
| [ClipboardRecord(byte[] data)](#ClipboardRecord-byte---) | 初始化 [ClipboardRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/clipboardrecord) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBoundingRect()](#getBoundingRect--) | 获取边界矩形。 |
| [setBoundingRect(RectangleF value)](#setBoundingRect-com.aspose.imaging.RectangleF-) | 设置边界矩形。 |
| [getResolution()](#getResolution--) | 获取分辨率。 |
| [setResolution(float value)](#setResolution-float-) | 设置分辨率。 |
| [getType()](#getType--) | 获取类型。 |
### ClipboardRecord() {#ClipboardRecord--}
```
public ClipboardRecord()
```


初始化 [ClipboardRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/clipboardrecord) 类的新实例。

### ClipboardRecord(byte[] data) {#ClipboardRecord-byte---}
```
public ClipboardRecord(byte[] data)
```


初始化 [ClipboardRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/clipboardrecord) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数据 | byte[] | 记录数据。 |

### getBoundingRect() {#getBoundingRect--}
```
public final RectangleF getBoundingRect()
```


获取边界矩形。

值：边界矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding rect.
### setBoundingRect(RectangleF value) {#setBoundingRect-com.aspose.imaging.RectangleF-}
```
public final void setBoundingRect(RectangleF value)
```


设置边界矩形。

值：边界矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | 边界矩形。 |

### getResolution() {#getResolution--}
```
public final float getResolution()
```


获取分辨率。

值：分辨率。

**Returns:**
float - 分辨率。
### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


设置分辨率。

值：分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 分辨率。 |

### getType() {#getType--}
```
public short getType()
```


获取类型。

值：类型。

**Returns:**
short - 类型。
