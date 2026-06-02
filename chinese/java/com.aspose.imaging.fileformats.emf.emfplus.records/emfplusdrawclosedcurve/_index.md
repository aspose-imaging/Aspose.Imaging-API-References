---
title: "EmfPlusDrawClosedCurve"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusDrawClosedCurve 记录指定绘制闭合的基数样条。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawClosedCurve extends EmfPlusDrawingRecordType
```

EmfPlusDrawClosedCurve 记录指定绘制闭合的基数样条。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawClosedCurve(EmfPlusRecord source)](#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawClosedCurve` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。 |
| [getRelative()](#getRelative--) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对的。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对的。 |
| [getTension()](#getTension--) | 获取或设置张力，一个 32 位浮点数，指定样条在通过各点时的弯曲程度。 |
| [setTension(float value)](#setTension-float-) | 获取或设置张力，一个 32 位浮点数，指定样条在通过各点时的弯曲程度。 |
| [getPointData()](#getPointData--) | 获取或设置点数据，一个包含 Count 个点的数组，指定定义样条的线段的端点。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置点数据，一个包含 Count 个点的数组，指定定义样条的线段的端点。 |
### EmfPlusDrawClosedCurve(EmfPlusRecord source) {#EmfPlusDrawClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawClosedCurve(EmfPlusRecord source)
```


初始化 `EmfPlusDrawClosedCurve` 类的新实例。RecordType - 一个 16 位无符号整数，用于标识此记录类型为来自 RecordType 枚举的 EmfPlusDrawClosedCurve（第 1.1.1.1 节）。该值必须为 0x4017。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。用于在 EMF+ 对象表中绘制闭合曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。用于在 EMF+ 对象表中绘制闭合曲线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否被压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，则 PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。如果清除，则 PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略

值：如果已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否被压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，则 PointData 指定坐标空间中使用 16 位整数坐标的绝对位置。如果清除，则 PointData 指定坐标空间中使用 32 位浮点坐标的绝对位置。注意：如果下面的 Relative 标志被设置，则此标志未定义，必须被忽略

值：如果已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定坐标空间中相对于数组中前一个元素指定的位置的坐标。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 Compressed 标志未定义，必须被忽略

值：如果为相对则为 `true`；否则为 `false`。

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否为相对。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定坐标空间中相对于数组中前一个元素指定的位置的坐标。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 Compressed 标志未定义，必须被忽略

值：如果为相对则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTension() {#getTension--}
```
public float getTension()
```


获取或设置张力。一个 32 位浮点数，指定样条线在经过各点时的弯曲程度。值为 0 表示样条线是一系列直线。值越大，曲线越圆滑。更多信息，请参见 [SPLINE77] 和 [PETZOLD]。

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


获取或设置张力。一个 32 位浮点数，指定样条线在经过各点时的弯曲程度。值为 0 表示样条线是一系列直线。值越大，曲线越圆滑。更多信息，请参见 [SPLINE77] 和 [PETZOLD]。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置点数据。一个包含 Count 个点的数组，指定定义样条线的线段的端点。在闭合基数样条线中，曲线会通过 PointData 数组中的最后一个点并连接到数组中的第一个点。此数组中的数据类型由 Flags 字段指定，如下所示：数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节）如果 Flags 中设置了 P 标志，则点表示相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）如果 Flags 字段中同时设置了 P 和 C 位，则点表示绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）如果 Flags 字段中未设置 P 位且设置了 C 位，则点表示相对位置。

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置点数据。一个包含 Count 个点的数组，指定定义样条线的线段的端点。在闭合基数样条线中，曲线会通过 PointData 数组中的最后一个点并连接到数组中的第一个点。此数组中的数据类型由 Flags 字段指定，如下所示：数据类型 含义 EmfPlusPointR 对象（第 2.2.2.37 节）如果 Flags 中设置了 P 标志，则点表示相对位置。EmfPlusPointF 对象（第 2.2.2.36 节）如果 Flags 字段中同时设置了 P 和 C 位，则点表示绝对位置。EmfPlusPoint 对象（第 2.2.2.35 节）如果 Flags 字段中未设置 P 位且设置了 C 位，则点表示相对位置。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

