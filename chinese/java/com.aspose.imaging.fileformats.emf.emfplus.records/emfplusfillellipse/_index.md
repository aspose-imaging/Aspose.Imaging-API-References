---
title: "EmfPlusFillEllipse"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusFillEllipse 记录指定填充椭圆的内部。"
type: docs
weight: 33
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

EmfPlusFillEllipse 记录指定填充椭圆的内部。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusFillEllipse` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [isCompressed()](#isCompressed--) | 获取或设置一个值，指示此实例是否已压缩。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 获取或设置一个值，指示此实例是否已压缩。 |
| [getBrushId()](#getBrushId--) | 获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。 |
| [getRectData()](#getRectData--) | 获取或设置矩形数据， 可以是定义椭圆边界框的 EmfPlusRect 或 EmfPlusRectF 对象 |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | 获取或设置矩形数据， 可以是定义椭圆边界框的 EmfPlusRect 或 EmfPlusRectF 对象 |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


初始化 `EmfPlusFillEllipse` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

值：如果此实例为颜色，则为 `true`；否则为 `false`。

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


获取或设置一个值，指示此实例是否为颜色。如果设置，则 BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，则 BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

值：如果此实例为颜色，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


获取或设置一个值，指示此实例是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：如果此实例已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


获取或设置一个值，指示此实例是否已压缩。如果设置，则 RectData 包含 EmfPlusRect 对象（第 2.2.2.38 节）。如果未设置，则 RectData 包含 EmfPlusRectF 对象（第 2.2.2.39 节）。

值：如果此实例已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。此定义用于填充椭圆的内部。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。此定义用于填充椭圆的内部。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


获取或设置矩形数据， 可以是定义椭圆边界框的 EmfPlusRect 或 EmfPlusRectF 对象

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


获取或设置矩形数据， 可以是定义椭圆边界框的 EmfPlusRect 或 EmfPlusRectF 对象

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

