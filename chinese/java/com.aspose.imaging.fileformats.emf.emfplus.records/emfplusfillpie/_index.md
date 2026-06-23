---
title: "EmfPlusFillPie"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusFillPie 记录指定填充椭圆内部的一个扇形区域。"
type: docs
weight: 35
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPie extends EmfPlusDrawingRecordType
```

EmfPlusFillPie 记录指定填充椭圆内部的一个扇形区域。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFillPie(EmfPlusRecord source)](#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusFillPie` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置指示 PointData 是否已压缩的值。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置指示 PointData 是否已压缩的值。 |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [getStartAngle()](#getStartAngle--) | 获取或设置起始角度，一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。 |
| [setStartAngle(float value)](#setStartAngle-float-) | 获取或设置起始角度，一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。 |
| [getSweepAngle()](#getSweepAngle--) | 获取或设置扫掠角度，一个 32 位浮点值，指定定义要绘制的饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。 |
| [setSweepAngle(float value)](#setSweepAngle-float-) | 获取或设置扫掠角度，一个 32 位浮点值，指定定义要绘制的饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。 |
| [getRectData()](#getRectData--) | 获取或设置矩形数据：可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | 获取或设置矩形数据：可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
| [getBrushId()](#getBrushId--) | 获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。 |
### EmfPlusFillPie(EmfPlusRecord source) {#EmfPlusFillPie-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPie(EmfPlusRecord source)
```


初始化 `EmfPlusFillPie` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置指示 PointData 是否已压缩的值。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：`true` 表示已压缩；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置指示 PointData 是否已压缩的值。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：`true` 表示已压缩；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（section 2.2.2.1）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（section 2.2.1.1）的索引。

值：如果此实例为颜色则为 `true`；否则为 `false`。

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 以 EmfPlusARGB 对象（section 2.2.2.1）指定颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（section 2.2.1.1）的索引。

值：如果此实例为颜色则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


获取或设置起始角度，一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。接受任何值，但必须对 360 取模，使用的结果应在 0.0（含）到 360.0（不含）之间。

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


获取或设置起始角度，一个 32 位非负浮点值，指定 x 轴与饼块起始点之间的角度。接受任何值，但必须对 360 取模，使用的结果应在 0.0（含）到 360.0（不含）之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


获取或设置扫掠角度，一个 32 位浮点值，指定定义要绘制的饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。接受任何值，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


获取或设置扫掠角度，一个 32 位浮点值，指定定义要绘制的饼块的弧段范围，以度数表示，测量自 StartAngle 值定义的起始点。接受任何值，但必须限制在 -360.0 到 360.0（含）之间。正值表示扫掠方向为顺时针，负值表示为逆时针。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


获取或设置矩形数据：可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义饼块的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


获取或设置矩形数据：可以是定义包含饼块的椭圆的边界框的 EmfPlusRect 或 EmfPlusRectF 对象。此矩形定义饼块的位置、大小和形状。该字段中对象的类型由 Flags 字段的值指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置画笔标识符——一个定义画笔的 32 位无符号整数，其内容由 Flags 字段中的 S 位决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

