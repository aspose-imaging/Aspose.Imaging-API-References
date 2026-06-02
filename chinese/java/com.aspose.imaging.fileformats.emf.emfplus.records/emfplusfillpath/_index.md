---
title: "EmfPlusFillPath"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "填充路径记录 FLAGS：16 位无符号整数，提供有关如何执行操作以及记录结构的信息。"
type: docs
weight: 34
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

填充路径记录 FLAGS：16 位无符号整数，提供有关如何执行操作以及记录结构的信息。 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 位)：此位指示 BrushId 字段中数据的类型。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。 X (1 位)：保留，必须忽略。 ObjectId (1 字节)：EMF+ 对象表中要填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusFillPath` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isColor()](#isColor--) | 获取或设置一个值，指示此实例是否为颜色。 |
| [setColor(boolean value)](#setColor-boolean-) | 获取或设置一个值，指示此实例是否为颜色。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getBrushId()](#getBrushId--) | 获取或设置 Brush ID：一个 32 位无符号整数，定义画笔，其内容由 Flags 字段中的 S 位决定。 |
| [setBrushId(int value)](#setBrushId-int-) | 获取或设置 Brush ID：一个 32 位无符号整数，定义画笔，其内容由 Flags 字段中的 S 位决定。 |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


初始化 `EmfPlusFillPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### isColor() {#isColor--}
```
public boolean isColor()
```


获取或设置一个值，指示此实例是否为颜色。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

值：如果此实例为颜色，则为 `true`；否则为 `false`。

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


获取或设置一个值，指示此实例是否为颜色。如果设置，BrushId 指定为 EmfPlusARGB 对象（第 2.2.2.1 节）表示的颜色。如果未设置，BrushId 包含 EMF+ 对象表中 EmfPlusBrush 对象（第 2.2.1.1 节）的索引。

值：如果此实例为颜色，则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。EMF+ 对象表中要填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。EMF+ 对象表中要填充的 EmfPlusPath 对象（第 2.2.1.6 节）的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


获取或设置 Brush ID：一个 32 位无符号整数，定义画笔，其内容由 Flags 字段中的 S 位决定。

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


获取或设置 Brush ID：一个 32 位无符号整数，定义画笔，其内容由 Flags 字段中的 S 位决定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

