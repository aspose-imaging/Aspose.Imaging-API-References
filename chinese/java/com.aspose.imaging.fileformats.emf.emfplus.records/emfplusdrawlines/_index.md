---
title: "EmfPlusDrawLines"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawlLines 记录指定绘制一系列相连的直线。"
type: docs
weight: 24
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawLines extends EmfPlusDrawingRecordType
```

EmfPlusDrawlLines 记录指定绘制一系列相连的直线。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawLines(EmfPlusRecord source)](#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawLines` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。 |
| [getRelative()](#getRelative--) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对。 |
| [getClosedShape()](#getClosedShape--) | 获取或设置一个值，指示是否为[closed shape]。 |
| [setClosedShape(boolean value)](#setClosedShape-boolean-) | 获取或设置一个值，指示是否为[closed shape]。 |
| [getPointData()](#getPointData--) | 获取或设置点数据：一个 Count 点的数组，指定要绘制的线段的起点和终点。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置点数据：一个 Count 点的数组，指定要绘制的线段的起点和终点。 |
### EmfPlusDrawLines(EmfPlusRecord source) {#EmfPlusDrawLines-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawLines(EmfPlusRecord source)
```


初始化 `EmfPlusDrawLines` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。EMF+ 对象表中用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。EMF+ 对象表中用于绘制线条的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果清除，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。

值：`true` 表示已压缩；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果清除，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。

值：`true` 表示已压缩；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，PointData 根据 C 标志指定绝对位置。注意：如果设置此标志，上面的 Compressed 标志未定义，必须被忽略。

值：`true` 表示相对；否则为 `false`。

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，PointData 根据 C 标志指定绝对位置。注意：如果设置此标志，上面的 Compressed 标志未定义，必须被忽略。

值：`true` 表示相对；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getClosedShape() {#getClosedShape--}
```
public boolean getClosedShape()
```


获取或设置一个值，指示是否为[closed shape]。

值：`true` 表示[closed shape]；否则为 `false`。

**Returns:**
boolean
### setClosedShape(boolean value) {#setClosedShape-boolean-}
```
public void setClosedShape(boolean value)
```


获取或设置一个值，指示是否为[closed shape]。

值：`true` 表示[closed shape]；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置点数据：一个 Count 点的数组，指定要绘制的线段的起点和终点。

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置点数据：一个 Count 点的数组，指定要绘制的线段的起点和终点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

