---
title: "EmfRecord"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMF 记录的基类 所有 EMF 记录的长度必须是 4 字节的整数倍。"
type: docs
weight: 106
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

EMF 记录的基类。所有 EMF 记录的长度必须是 4 字节的整数倍。这在前述 EMF 记录类型的通用结构中通过在适当位置的结构末尾包含 AlignmentPadding 字段来体现。AlignmentPadding 字段的内容必须始终被忽略。为简洁起见，这些字段未在每个单独的 EMF 记录定义中显示。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | 初始化 `EmfRecord` 类的新实例。 |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfRecord` 类的新实例。 |
| [EmfRecord(int type)](#EmfRecord-int-) | 初始化 `EmfRecord` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取类型。 |
| [setType(int value)](#setType-int-) | 设置类型。 |
| [getSize()](#getSize--) | 获取记录的大小 |
| [setSize(int value)](#setSize-int-) | 设置记录的大小 |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


初始化 `EmfRecord` 类的新实例。

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


初始化 `EmfRecord` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


初始化 `EmfRecord` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 类型 | int | 记录类型。 |

### getType() {#getType--}
```
public int getType()
```


获取类型。

**Returns:**
int - 类型。
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


设置类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 类型。 |

### getSize() {#getSize--}
```
public int getSize()
```


获取记录的大小

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


设置记录的大小

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

