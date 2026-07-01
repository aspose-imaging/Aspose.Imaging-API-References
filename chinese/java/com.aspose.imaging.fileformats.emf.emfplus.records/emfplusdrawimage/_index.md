---
title: "EmfPlusDrawImage"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawImage 记录指定绘制缩放图像。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawImage extends EmfPlusDrawingRecordType
```

EmfPlusDrawImage 记录指定绘制缩放图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawImage(EmfPlusRecord source)](#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawImage` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 获取或设置指示 PointData 是否已压缩的值。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置指示 PointData 是否已压缩的值。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getImageAttributesId()](#getImageAttributesId--) | 获取或设置图像属性标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusImageAttributes 对象（章节 2.2.1.5）的索引。 |
| [setImageAttributesId(int value)](#setImageAttributesId-int-) | 获取或设置图像属性标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusImageAttributes 对象（章节 2.2.1.5）的索引。 |
| [getRectData()](#getRectData--) | 获取或设置矩形数据，指定定义图像边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | 获取或设置矩形数据，指定定义图像边界框的 EmfPlusRect 或 EmfPlusRectF 对象。 |
| [getSrcRect()](#getSrcRect--) | 获取或设置源矩形，指定要渲染的图像部分的 EmfPlusRectF 对象。 |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | 获取或设置源矩形，指定要渲染的图像部分的 EmfPlusRectF 对象。 |
| [getSrcUnit()](#getSrcUnit--) | 获取或设置源单位，指定 SrcRect 字段单位的 32 位有符号整数。 |
| [setSrcUnit(int value)](#setSrcUnit-int-) | 获取或设置源单位，指定 SrcRect 字段单位的 32 位有符号整数。 |
### EmfPlusDrawImage(EmfPlusRecord source) {#EmfPlusDrawImage-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawImage(EmfPlusRecord source)
```


初始化 `EmfPlusDrawImage` 类的新实例。

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

### getImageAttributesId() {#getImageAttributesId--}
```
public int getImageAttributesId()
```


获取或设置图像属性标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusImageAttributes 对象（章节 2.2.1.5）的索引。

**Returns:**
int
### setImageAttributesId(int value) {#setImageAttributesId-int-}
```
public void setImageAttributesId(int value)
```


获取或设置图像属性标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选的 EmfPlusImageAttributes 对象（章节 2.2.1.5）的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


获取或设置矩形数据，指定定义图像边界框的 EmfPlusRect 或 EmfPlusRectF 对象。由 SrcRect 字段指定的图像部分将按比例缩放以适应此矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


获取或设置矩形数据，指定定义图像边界框的 EmfPlusRect 或 EmfPlusRectF 对象。由 SrcRect 字段指定的图像部分将按比例缩放以适应此矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


获取或设置源矩形，指定要渲染的图像部分的 EmfPlusRectF 对象。该矩形指定的图像部分将按比例缩放以适应 RectData 字段指定的目标矩形。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


获取或设置源矩形，指定要渲染的图像部分的 EmfPlusRectF 对象。该矩形指定的图像部分将按比例缩放以适应 RectData 字段指定的目标矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcUnit() {#getSrcUnit--}
```
public int getSrcUnit()
```


获取或设置源单位，指定 SrcRect 字段单位的 32 位有符号整数。它必须是 UnitType 枚举 (第 2.1.1.33 节) 中的 UnitTypePixel 成员。

**Returns:**
int
### setSrcUnit(int value) {#setSrcUnit-int-}
```
public void setSrcUnit(int value)
```


获取或设置源单位，指定 SrcRect 字段单位的 32 位有符号整数。它必须是 UnitType 枚举 (第 2.1.1.33 节) 中的 UnitTypePixel 成员。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

