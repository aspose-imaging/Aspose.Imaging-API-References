---
title: "EmfPlusDrawRects"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusDrawRects 记录指定绘制一系列矩形。"
type: docs
weight: 27
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawRects extends EmfPlusDrawingRecordType
```

EmfPlusDrawRects 记录指定绘制一系列矩形。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawRects(EmfPlusRecord source)](#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawRects` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示 PointData 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示 PointData 是否已压缩。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getRectData()](#getRectData--) | 获取或设置矩形数据。一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。 |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | 获取或设置矩形数据。一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。 |
### EmfPlusDrawRects(EmfPlusRecord source) {#EmfPlusDrawRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawRects(EmfPlusRecord source)
```


初始化 `EmfPlusDrawRects` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示 PointData 是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：如果已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示 PointData 是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：如果已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。EMF+ 对象表中用于绘制矩形的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。EMF+ 对象表中用于绘制矩形的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getRectData() {#getRectData--}
```
public RectangleF[] getRectData()
```


获取或设置矩形数据。一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。

**Returns:**
com.aspose.imaging.RectangleF[]
### setRectData(RectangleF[] value) {#setRectData-com.aspose.imaging.RectangleF---}
```
public void setRectData(RectangleF[] value)
```


获取或设置矩形数据。一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF\[\]](../../com.aspose.imaging/rectanglef) |  |

