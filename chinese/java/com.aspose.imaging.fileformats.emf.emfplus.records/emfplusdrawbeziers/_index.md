---
title: "EmfPlusDrawBeziers"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusDrawBeziers 记录指定绘制一系列相连的贝塞尔曲线。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

EmfPlusDrawBeziers 记录指定绘制一系列相连的贝塞尔曲线。贝塞尔数据点的顺序为起点、控制点 1、控制点 2 和终点。更多信息请参见 [MSDN-DrawBeziers]。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawBeziers` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示 PointData 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示 PointData 是否已压缩。 |
| [getRelative()](#getRelative--) | 获取或设置一个值，指示 PointData 是否为相对。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 获取或设置一个值，指示 PointData 是否为相对。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getPointData()](#getPointData--) | 获取或设置点数据，一个包含 Count 个点的数组，这些点指定贝塞尔曲线的起点、终点和控制点。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置点数据，一个包含 Count 个点的数组，这些点指定贝塞尔曲线的起点、终点和控制点。 |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


初始化 `EmfPlusDrawBeziers` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示 PointData 是否已压缩。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。

值：如果已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示 PointData 是否已压缩。如果设置，PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略。

值：如果已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


获取或设置一个值，指示 PointData 是否为相对。如果设置，PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，PointData 根据 C 标志指定绝对位置。注意：如果设置了此标志，上面的 C 标志未定义，必须被忽略。

值：如果为相对则为 `true`；否则为 `false`。

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


获取或设置一个值，指示 PointData 是否为相对。如果设置，PointData 中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，PointData 根据 C 标志指定绝对位置。注意：如果设置了此标志，上面的 C 标志未定义，必须被忽略。

值：如果为相对则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。EMF+ 对象表中用于绘制贝塞尔曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。EMF+ 对象表中用于绘制贝塞尔曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置点数据 一个包含 Count 个点的数组，这些点指定贝塞尔曲线的起点、终点和控制点。一个贝塞尔曲线的结束坐标是下一个贝塞尔曲线的起始坐标。控制点用于产生贝塞尔效果。此数组中的数据类型由 Flags 字段指定，如下：数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节）如果 Flags 中设置了 P 标志，则点指定相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）如果 Flags 字段中 P 和 C 位均未设置，则点指定绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）如果 Flags 字段中 P 位未设置且 C 位已设置，则点指定相对位置。贝塞尔曲线不会经过其控制点。控制点的作用是

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置点数据 一个包含 Count 个点的数组，这些点指定贝塞尔曲线的起点、终点和控制点。一个贝塞尔曲线的结束坐标是下一个贝塞尔曲线的起始坐标。控制点用于产生贝塞尔效果。此数组中的数据类型由 Flags 字段指定，如下：数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节）如果 Flags 中设置了 P 标志，则点指定相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）如果 Flags 字段中 P 和 C 位均未设置，则点指定绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）如果 Flags 字段中 P 位未设置且 C 位已设置，则点指定相对位置。贝塞尔曲线不会经过其控制点。控制点的作用是

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

