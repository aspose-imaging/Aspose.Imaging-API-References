---
title: "EmfPlusFillRects"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusFillRects 记录指定填充一系列矩形的内部。"
type: docs
weight: 37
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRects extends EmfPlusDrawingRecordType
```

EmfPlusFillRects 记录指定填充一系列矩形的内部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFillRects(EmfPlusRecord source)](#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusFillRects` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示此 `EmfPlusFillRects` 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此 `EmfPlusFillRects` 是否已压缩。 |
| [getBrushId()](#getBrushId--) | 获取或设置画笔标识符，一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置画笔标识符，一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。 |
| [getRectData()](#getRectData--) | 获取或设置矩形数据。一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。 |
| [setRectData(RectangleF[] value)](#setRectData-com.aspose.imaging.RectangleF---) | 获取或设置矩形数据。一个长度为 Count 的数组，包含 EmfPlusRect 或 EmfPlusRectF 对象，用于定义矩形数据。 |
### EmfPlusFillRects(EmfPlusRecord source) {#EmfPlusFillRects-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRects(EmfPlusRecord source)
```


初始化 `EmfPlusFillRects` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，指示此实例是否为颜色。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

值：如果此实例为颜色，则为 `true`；否则为 `false`。

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


获取或设置一个值，指示此实例是否为颜色。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

值：如果此实例为颜色，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示此 `EmfPlusFillRects` 是否已压缩。如果设置，则 RectData 包含一个 EmfPlusRect 对象（第 2.2.2.38 节）。如果清除，则 RectData 包含一个 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：如果已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示此 `EmfPlusFillRects` 是否已压缩。如果设置，则 RectData 包含一个 EmfPlusRect 对象（第 2.2.2.38 节）。如果清除，则 RectData 包含一个 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：如果已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置画笔标识符，一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置画笔标识符，一个 32 位无符号整数，用于定义画笔，其内容由 Flags 字段中的 S 位决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

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

