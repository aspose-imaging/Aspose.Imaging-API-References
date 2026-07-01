---
title: "EmfPlusDrawCurve"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawCurve 记录指定绘制基数样条。注意 ObjectID 1 字节：在 EMF 对象表中用于绘制曲线的 EmfPlusPen 对象（章节 2.2.1.7）的索引。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawCurve extends EmfPlusDrawingRecordType
```

EmfPlusDrawCurve 记录指定绘制基数样条。注意：ObjectID（1 字节）：在 EMF+ 对象表中用于绘制曲线的 EmfPlusPen 对象（章节 2.2.1.7）的索引。该值必须在 0 到 63（含）之间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawCurve(EmfPlusRecord source)](#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawCurve` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此 `EmfPlusDrawClosedCurve` 是否已压缩。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getTension()](#getTension--) | 获取或设置张力，一个 32 位浮点数，指定样条在通过各点时的弯曲程度。 |
| [setTension(float value)](#setTension-float-) | 获取或设置张力，一个 32 位浮点数，指定样条在通过各点时的弯曲程度。 |
| [getNumSegments()](#getNumSegments--) | 获取或设置段计数，一个 32 位无符号整数，指定构成样条的线段数量。 |
| [setNumSegments(int value)](#setNumSegments-int-) | 获取或设置段计数，一个 32 位无符号整数，指定构成样条的线段数量。 |
| [getPointData()](#getPointData--) | 获取或设置一个数组，长度为 Count，数组元素可以是 32 位有符号整数或 32 位浮点数，定义要描边的线段端点的坐标值。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置一个数组，长度为 Count，数组元素可以是 32 位有符号整数或 32 位浮点数，定义要描边的线段端点的坐标值。 |
### EmfPlusDrawCurve(EmfPlusRecord source) {#EmfPlusDrawCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawCurve(EmfPlusRecord source)
```


初始化 `EmfPlusDrawCurve` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。用于绘制曲线的 EmfPlusPen 对象（章节 2.2.1.7）在 EMF+ 对象表中的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。用于绘制曲线的 EmfPlusPen 对象（章节 2.2.1.7）在 EMF+ 对象表中的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getTension() {#getTension--}
```
public float getTension()
```


获取或设置张力，一个 32 位浮点数，指定样条在通过各点时的弯曲程度。值为 0 表示样条是一系列直线。值增大时，曲线变得更圆滑。欲了解更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


获取或设置张力，一个 32 位浮点数，指定样条在通过各点时的弯曲程度。值为 0 表示样条是一系列直线。值增大时，曲线变得更圆滑。欲了解更多信息，请参阅 [SPLINE77] 和 [PETZOLD]。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getNumSegments() {#getNumSegments--}
```
public int getNumSegments()
```


获取或设置段计数，一个 32 位无符号整数，指定构成样条的线段数量。

**Returns:**
int
### setNumSegments(int value) {#setNumSegments-int-}
```
public void setNumSegments(int value)
```


获取或设置段计数，一个 32 位无符号整数，指定构成样条的线段数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置一个数组，长度为 Count，数组元素可以是 32 位有符号整数或 32 位浮点数，定义要描边的线段端点的坐标值。

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置一个数组，长度为 Count，数组元素可以是 32 位有符号整数或 32 位浮点数，定义要描边的线段端点的坐标值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

