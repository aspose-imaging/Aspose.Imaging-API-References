---
title: "EmfColorCorrectPalette"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EMR_COLORCORRECTPALETTE 记录指定如何使用 WCS 1.0 值校正逻辑调色板对象的条目。"
type: docs
weight: 23
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectManipulationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectmanipulationrecordtype)
```
public final class EmfColorCorrectPalette extends EmfObjectManipulationRecordType
```

EMR\_COLORCORRECTPALETTE 记录指定如何使用 WCS 1.0 值校正逻辑调色板对象的条目。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfColorCorrectPalette(EmfRecord source)](#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfColorCorrectPalette` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIhPalette()](#getIhPalette--) | 获取一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象（第 2.2.17 节）的索引。 |
| [setIhPalette(int value)](#setIhPalette-int-) | 设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象（第 2.2.17 节）的索引。 |
| [getNFirstEntry()](#getNFirstEntry--) | 获取一个 32 位无符号整数，指定要校正的第一个条目的索引。 |
| [setNFirstEntry(int value)](#setNFirstEntry-int-) | 设置一个 32 位无符号整数，指定要校正的第一个条目的索引。 |
| [getNPalEntries()](#getNPalEntries--) | 获取一个 32 位无符号整数，指定要校正的调色板条目数量。 |
| [setNPalEntries(int value)](#setNPalEntries-int-) | 设置一个 32 位无符号整数，指定要校正的调色板条目数量。 |
### EmfColorCorrectPalette(EmfRecord source) {#EmfColorCorrectPalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorCorrectPalette(EmfRecord source)
```


初始化 `EmfColorCorrectPalette` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 源。 |

### getIhPalette() {#getIhPalette--}
```
public int getIhPalette()
```


获取一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象（第 2.2.17 节）的索引。

**Returns:**
int
### setIhPalette(int value) {#setIhPalette-int-}
```
public void setIhPalette(int value)
```


设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中逻辑调色板对象（第 2.2.17 节）的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getNFirstEntry() {#getNFirstEntry--}
```
public int getNFirstEntry()
```


获取一个 32 位无符号整数，指定要校正的第一个条目的索引。

**Returns:**
int
### setNFirstEntry(int value) {#setNFirstEntry-int-}
```
public void setNFirstEntry(int value)
```


设置一个 32 位无符号整数，指定要校正的第一个条目的索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


获取一个 32 位无符号整数，指定要校正的调色板条目数量。

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


设置一个 32 位无符号整数，指定要校正的调色板条目数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

