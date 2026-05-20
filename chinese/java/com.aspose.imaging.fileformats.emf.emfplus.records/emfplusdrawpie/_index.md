---
title: "EmfPlusDrawPie"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusDrawPie 记录指定绘制椭圆内部的一个扇形区域。"
type: docs
weight: 26
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPie extends EmfPlusDrawingRecordType
```

EmfPlusDrawPie 记录指定绘制椭圆内部的一个扇形区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawPie(EmfPlusRecord source)](#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawPie` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置一个值，指示 PointData 是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示 PointData 是否已压缩。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getStartAngle()](#getStartAngle--) | 获取或设置起始角度。一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。 |
| [setStartAngle(float value)](#setStartAngle-float-) | 获取或设置起始角度。一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。 |
| [getSweepAngle()](#getSweepAngle--) | 获取或设置扫掠角度。一个 32 位浮点值，指定绘制饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。 |
| [setSweepAngle(float value)](#setSweepAngle-float-) | 获取或设置扫掠角度。一个 32 位浮点值，指定绘制饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。 |
| [getRectData()](#getRectData--) | 获取或设置矩形数据。可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | 获取或设置矩形数据。可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
### EmfPlusDrawPie(EmfPlusRecord source) {#EmfPlusDrawPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPie(EmfPlusRecord source)
```


初始化 `EmfPlusDrawPie` 类的新实例。

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


获取或设置对象标识符。用于绘制饼形的 EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。用于绘制饼形的 EMF+ 对象表中 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


获取或设置起始角度。一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。接受任意值，但必须对 360 取模，使用的结果应在 0.0（含）到 360.0（不含）之间。

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


获取或设置起始角度。一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。接受任意值，但必须对 360 取模，使用的结果应在 0.0（含）到 360.0（不含）之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


获取或设置扫掠角度。一个 32 位浮点值，指定绘制饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。接受任意值，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


获取或设置扫掠角度。一个 32 位浮点值，指定绘制饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。接受任意值，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


获取或设置矩形数据。可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义了饼块的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


获取或设置矩形数据。可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义了饼块的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

