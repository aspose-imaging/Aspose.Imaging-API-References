---
title: "EmfPlusDrawArc"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawArc 记录指定绘制椭圆的弧线。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawArc extends EmfPlusDrawingRecordType
```

EmfPlusDrawArc 记录指定绘制椭圆的弧线。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawArc(EmfPlusRecord source)](#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawArc` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDataSize()](#getDataSize--) | 获取数据的大小。 |
| [setDataSize(int value)](#setDataSize-int-) | 设置数据的大小。 |
| [getRectFloat()](#getRectFloat--) | 获取一个值，指示数据是否包含 EmfPlusRectF 或 EmfPlusRect 记录。此位指示 RectData 字段中的数据是否已压缩。 |
| [setRectFloat(boolean value)](#setRectFloat-boolean-) | 设置一个值，指示数据是否包含 EmfPlusRectF 或 EmfPlusRect 记录。此位指示 RectData 字段中的数据是否已压缩。 |
| [getObjectId()](#getObjectId--) | 获取对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 设置对象标识符。 |
| [getSize()](#getSize--) | 获取大小。 |
| [setSize(int value)](#setSize-int-) | 设置大小。 |
| [getStartAngle()](#getStartAngle--) | 获取起始角度，一个 32 位非负浮点值，指定 x 轴与弧线起始点之间的角度。 |
| [setStartAngle(float value)](#setStartAngle-float-) | 设置起始角度，一个 32 位非负浮点值，指定 x 轴与弧线起始点之间的角度。 |
| [getSweepAngle()](#getSweepAngle--) | 获取扫掠角度，一个 32 位浮点值，指定要绘制的弧线的范围，以度为单位的角度，测量自 StartAngle 值定义的起始点。 |
| [setSweepAngle(float value)](#setSweepAngle-float-) | 设置扫掠角度，一个 32 位浮点值，指定要绘制的弧线的范围，以度为单位的角度，测量自 StartAngle 值定义的起始点。 |
| [getRectangleData()](#getRectangleData--) | 获取矩形数据， 可以是 EmfPlusRect 或 EmfPlusRectF 对象，定义与弧线共线的椭圆的边界框。 |
| [setRectangleData(RectangleF value)](#setRectangleData-com.aspose.imaging.RectangleF-) | 设置矩形数据， 可以是 EmfPlusRect 或 EmfPlusRectF 对象，定义与弧线共线的椭圆的边界框。 |
### EmfPlusDrawArc(EmfPlusRecord source) {#EmfPlusDrawArc-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawArc(EmfPlusRecord source)
```


初始化 `EmfPlusDrawArc` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


获取数据的大小。一个 32 位无符号整数，指定随后记录特定数据的 32 位对齐字节数。对于此记录类型，值必须是以下之一：0x00000010（如果 Flags 字段中的 C 位被设置），0x00000018（如果 C 位未设置）。

**Returns:**
int - 数据的大小。
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


设置数据的大小。一个 32 位无符号整数，指定随后记录特定数据的 32 位对齐字节数。对于此记录类型，值必须是以下之一：0x00000010（如果 Flags 字段中的 C 位被设置），0x00000018（如果 C 位未设置）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 数据的大小。 |

### getRectFloat() {#getRectFloat--}
```
public boolean getRectFloat()
```


获取一个值，指示数据是包含 EmfPlusRectF 还是 EmfPlusRect 记录。此位指示 RectData 字段中的数据是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

**Returns:**
布尔值 - `true` 表示浮点；否则为 `false`。
### setRectFloat(boolean value) {#setRectFloat-boolean-}
```
public void setRectFloat(boolean value)
```


设置一个值，指示数据是包含 EmfPlusRectF 还是 EmfPlusRect 记录。此位指示 RectData 字段中的数据是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | `true` 表示浮点；否则为 `false`。 |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取对象标识符。EMF+ 对象表中用于绘制弧线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

**Returns:**
byte - 对象标识符。
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


设置对象标识符。EMF+ 对象表中用于绘制弧线的 EmfPlusPen 对象（第 2.2.1.7 节）的索引。该值必须在 0 到 63（含）之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | 对象标识符。 |

### getSize() {#getSize--}
```
public int getSize()
```


获取大小。一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。对于此记录类型，值必须是以下之一：0x0000001C（如果 Flags 字段中的 C 位被设置），0x00000024（如果 C 位未设置）。

**Returns:**
int - 大小。
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


设置大小。一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。对于此记录类型，值必须是以下之一：0x0000001C（如果 Flags 字段中的 C 位被设置），0x00000024（如果 C 位未设置）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 大小。 |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


获取起始角度，一个 32 位非负浮点值，指定 x 轴与弧线起始点之间的角度。任何值均可接受，但必须对 360 取模，使用的结果范围为 0.0（含）到 360.0（不含）。

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


设置起始角度，一个 32 位非负浮点值，指定 x 轴与弧线起始点之间的角度。任何值均可接受，但必须对 360 取模，使用的结果范围为 0.0（含）到 360.0（不含）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


获取扫掠角度，一个 32 位浮点值，指定要绘制的弧线的范围，以度为单位的角度，测量自 StartAngle 值定义的起始点。任何值均可接受，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


设置扫掠角度，一个 32 位浮点值，指定要绘制的弧线的范围，以度为单位的角度，测量自 StartAngle 值定义的起始点。任何值均可接受，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getRectangleData() {#getRectangleData--}
```
public RectangleF getRectangleData()
```


获取矩形数据，可以是 EmfPlusRect 或 EmfPlusRectF 对象，定义与弧线共线的椭圆的边界框。此矩形定义弧线的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectangleData(RectangleF value) {#setRectangleData-com.aspose.imaging.RectangleF-}
```
public void setRectangleData(RectangleF value)
```


设置矩形数据，可以是 EmfPlusRect 或 EmfPlusRectF 对象，定义与弧线共线的椭圆的边界框。此矩形定义弧线的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

