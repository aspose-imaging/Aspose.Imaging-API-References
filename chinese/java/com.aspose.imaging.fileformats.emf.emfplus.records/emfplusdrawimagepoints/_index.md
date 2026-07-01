---
title: "EmfPlusDrawImagePoints"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawImagePoints 记录指定在平行四边形内绘制缩放图像。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImagePoints extends EmfPlusDrawingRecordType
```

EmfPlusDrawImagePoints 记录指定在平行四边形内绘制缩放图像。

EmfPlusImage 可以指定位图或元文件。图像中的颜色可以在渲染过程中进行操作，包括校正、加暗、加亮以及移除。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawImagePoints(EmfPlusRecord source)](#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawImagePoints` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置指示 PointData 是否已压缩的值。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置指示 PointData 是否已压缩的值。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getApplyingAnEffect()](#getApplyingAnEffect--) | 获取或设置一个值，指示是否[应用效果]。 |
| [setApplyingAnEffect(boolean value)](#setApplyingAnEffect-boolean-) | 获取或设置一个值，指示是否[应用效果]。 |
| [getRelative()](#getRelative--) | 获取或设置一个值，指示此 `EmfPlusDrawImagePoints` 是否为相对的。 |
| [setRelative(boolean value)](#setRelative-boolean-) | 获取或设置一个值，指示此 `EmfPlusDrawImagePoints` 是否为相对的。 |
| [getImageAttributesId()](#getImageAttributesId--) | 获取或设置一个 32 位无符号整数，包含 EMF+ 对象表中可选 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。 |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | 获取或设置一个 32 位无符号整数，包含 EMF+ 对象表中可选 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。 |
| [getSrcUnit()](#getSrcUnit--) | 获取或设置一个 32 位有符号整数，定义 SrcRect 字段的单位。 |
| [setSrcUnit(int value)](#setSrcUnit-int-) | 获取或设置一个 32 位有符号整数，定义 SrcRect 字段的单位。 |
| [getSrcRect()](#getSrcRect--) | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象定义要渲染的图像部分。 |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | 获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象定义要渲染的图像部分。 |
| [getPointData()](#getPointData--) | 获取或设置一个包含 Count 点的数组，这些点指定平行四边形的三个点。 |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | 获取或设置一个包含 Count 点的数组，这些点指定平行四边形的三个点。 |
### EmfPlusDrawImagePoints(EmfPlusRecord source) {#EmfPlusDrawImagePoints-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImagePoints(EmfPlusRecord source)
```


初始化 `EmfPlusDrawImagePoints` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


获取或设置一个值，指示 PointData 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，则 PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果清除，则 PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 P 标志被设置，则此标志未定义，必须被忽略。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示 PointData 是否已压缩。此位指示 PointData 字段是否指定压缩数据。如果设置，则 PointData 使用 16 位整数坐标指定坐标空间中的绝对位置。如果清除，则 PointData 使用 32 位浮点坐标指定坐标空间中的绝对位置。注意：如果下面的 P 标志被设置，则此标志未定义，必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。该标识符是 EMF+ 对象表中 EmfPlusImage 对象（第 2.2.1.4 节）的索引，用于指定要渲染的图像。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。该标识符是 EMF+ 对象表中 EmfPlusImage 对象（第 2.2.1.4 节）的索引，用于指定要渲染的图像。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getApplyingAnEffect() {#getApplyingAnEffect--}
```
public boolean getApplyingAnEffect()
```


获取或设置一个值，指示是否[应用效果]。此位指示图像渲染包含应用效果。如果设置，则必须在之前的 EmfPlusSerializableObject 记录（第 2.3.5.2 节）中指定 Effect 类的对象。

值：如果[应用效果]则为 `true`；否则为 `false`。

**Returns:**
boolean
### setApplyingAnEffect(boolean value) {#setApplyingAnEffect-boolean-}
```
public void setApplyingAnEffect(boolean value)
```


获取或设置一个值，指示是否[应用效果]。此位指示图像渲染包含应用效果。如果设置，则必须在之前的 EmfPlusSerializableObject 记录（第 2.3.5.2 节）中指定 Effect 类的对象。

值：如果[应用效果]则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


获取或设置一个值，指示此 `EmfPlusDrawImagePoints` 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素所指定位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 C 标志未定义，必须被忽略。

值：`true` 表示相对；否则为 `false`。

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


获取或设置一个值，指示此 `EmfPlusDrawImagePoints` 是否为相对的。此位指示 PointData 字段是指定相对位置还是绝对位置。如果设置，则 PointData 中的每个元素指定相对于数组中前一个元素所指定位置的坐标空间位置。对于 PointData 的第一个元素，假定前一个位置为坐标 (0,0)。如果清除，则 PointData 根据 C 标志指定绝对位置。注意：如果此标志被设置，上面的 C 标志未定义，必须被忽略。

值：`true` 表示相对；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


获取或设置一个 32 位无符号整数，包含 EMF+ 对象表中可选 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。

值：图像属性标识符。

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


获取或设置一个 32 位无符号整数，包含 EMF+ 对象表中可选 EmfPlusImageAttributes 对象（第 2.2.1.5 节）的索引。

值：图像属性标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


获取或设置一个 32 位有符号整数，定义 SrcRect 字段的单位。它必须是 UnitType 枚举（第 2.1.1.33 节）中的 UnitPixel 值。

值：源单位。

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


获取或设置一个 32 位有符号整数，定义 SrcRect 字段的单位。它必须是 UnitType 枚举（第 2.1.1.33 节）中的 UnitPixel 值。

值：源单位。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象定义要渲染的图像部分。

值：源矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


获取或设置一个 EmfPlusRectF 对象（第 2.2.2.39 节），该对象定义要渲染的图像部分。

值：源矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


获取或设置一个包含 Count 点的数组，这些点指定平行四边形的三个点。该三个点分别代表平行四边形的左上、右上和左下角。第四个点由前三个点外推得到。SrcRect 字段指定的图像部分应在必要时应用缩放和剪切变换，以适应平行四边形内部。

值：点数据。

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


获取或设置一个包含 Count 点的数组，这些点指定平行四边形的三个点。该三个点分别代表平行四边形的左上、右上和左下角。第四个点由前三个点外推得到。SrcRect 字段指定的图像部分应在必要时应用缩放和剪切变换，以适应平行四边形内部。

值：点数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

