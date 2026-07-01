---
title: "EmfPlusDrawString"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawString 记录指定带字符串格式化的文本输出。"
type: docs
weight: 28
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

EmfPlusDrawString 记录指定带字符串格式化的文本输出。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawString` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getBrushId()](#getBrushId--) | 获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。 |
| [getFormatId()](#getFormatId--) | 获取或设置格式标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选 EmfPlusStringFormat 对象（section 2.2.1.9）的索引。 |
| [setFormatId(int value)](#setFormatId-int-) | 获取或设置格式标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选 EmfPlusStringFormat 对象（section 2.2.1.9）的索引。 |
| [getLength()](#getLength--) | 获取或设置长度，一个 32 位无符号整数，指定字符串中的字符数。 |
| [setLength(int value)](#setLength-int-) | 获取或设置长度，一个 32 位无符号整数，指定字符串中的字符数。 |
| [getLayoutRect()](#getLayoutRect--) | 获取或设置布局矩形，一个 EmfPlusRectF 对象（section 2.2.2.39），定义将接收字符串的目标的边界区域。 |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | 获取或设置布局矩形，一个 EmfPlusRectF 对象（section 2.2.2.39），定义将接收字符串的目标的边界区域。 |
| [getStringData()](#getStringData--) | 获取或设置字符串数据，一个 16 位 Unicode 字符数组，指定要绘制的字符串。 |
| [setStringData(String value)](#setStringData-java.lang.String-) | 获取或设置字符串数据，一个 16 位 Unicode 字符数组，指定要绘制的字符串。 |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


初始化 `EmfPlusDrawString` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。EMF+ 对象表中用于呈现文本的 EmfPlusFont 对象（section 2.2.1.3）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。EMF+ 对象表中用于呈现文本的 EmfPlusFont 对象（section 2.2.1.3）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。此定义用于绘制前景文本颜色；即仅绘制字形本身。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置画笔标识符，一个 32 位无符号整数，指定画笔，其内容由 Flags 字段中的 S 位决定。此定义用于绘制前景文本颜色；即仅绘制字形本身。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


获取或设置格式标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选 EmfPlusStringFormat 对象（section 2.2.1.9）的索引。此对象指定要应用于字符串的文本布局信息和显示操作。

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


获取或设置格式标识符，一个 32 位无符号整数，指定 EMF+ 对象表中可选 EmfPlusStringFormat 对象（section 2.2.1.9）的索引。此对象指定要应用于字符串的文本布局信息和显示操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


获取或设置长度，一个 32 位无符号整数，指定字符串中的字符数。

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


获取或设置长度，一个 32 位无符号整数，指定字符串中的字符数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


获取或设置布局矩形，一个 EmfPlusRectF 对象（section 2.2.2.39），定义将接收字符串的目标的边界区域。

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


获取或设置布局矩形，一个 EmfPlusRectF 对象（section 2.2.2.39），定义将接收字符串的目标的边界区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


获取或设置字符串数据，一个 16 位 Unicode 字符数组，指定要绘制的字符串。

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


获取或设置字符串数据，一个 16 位 Unicode 字符数组，指定要绘制的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

