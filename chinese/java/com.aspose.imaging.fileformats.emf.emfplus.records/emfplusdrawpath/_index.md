---
title: "EmfPlusDrawPath"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusDrawPath 记录指定绘制图形路径。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

EmfPlusDrawPath 记录指定绘制图形路径。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusDrawPath` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getPenId()](#getPenId--) | 获取或设置笔标识符，指定用于绘制 EmfPlusPath 的 EmfPlusPen 对象（第 2.2.1.7 节）在 EMF+ 对象表中的 32 位无符号整数索引。 |
| [setPenId(int value)](#setPenId-int-) | 获取或设置笔标识符，指定用于绘制 EmfPlusPath 的 EmfPlusPen 对象（第 2.2.1.7 节）在 EMF+ 对象表中的 32 位无符号整数索引。 |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


初始化 `EmfPlusDrawPath` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。要绘制的 EmfPlusPath 对象（第 2.2.1.6 节）在 EMF+ 对象表中的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。要绘制的 EmfPlusPath 对象（第 2.2.1.6 节）在 EMF+ 对象表中的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


获取或设置笔标识符，指定用于绘制 EmfPlusPath 的 EmfPlusPen 对象（第 2.2.1.7 节）在 EMF+ 对象表中的 32 位无符号整数索引。该值必须在 0 到 63（含）之间。

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


获取或设置笔标识符，指定用于绘制 EmfPlusPath 的 EmfPlusPen 对象（第 2.2.1.7 节）在 EMF+ 对象表中的 32 位无符号整数索引。该值必须在 0 到 63（含）之间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

