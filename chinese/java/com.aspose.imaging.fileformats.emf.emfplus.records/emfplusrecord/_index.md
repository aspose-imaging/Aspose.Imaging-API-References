---
title: "EmfPlusRecord"
second_title: "Aspose.Imaging for Java API 参考"
description: "Emf 基础记录类型。"
type: docs
weight: 46
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Emf+ 基础记录类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | 初始化 `EmfPlusRecord` 类的新实例。 |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusRecord` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 获取一个标识记录类型的 16 位无符号整数。 |
| [getFlags()](#getFlags--) | 获取一个 16 位无符号整数，其中包含某些记录的操作执行方式及记录结构的信息。 |
| [setFlags(short value)](#setFlags-short-) | 设置一个 16 位无符号整数，其中包含某些记录的操作执行方式及记录结构的信息。 |
| [getSize()](#getSize--) | 获取一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [setSize(int value)](#setSize-int-) | 设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。 |
| [getDataSize()](#getDataSize--) | 获取一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位\u2013对齐字节数。 |
| [setDataSize(int value)](#setDataSize-int-) | 设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位\u2013对齐字节数。 |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


初始化 `EmfPlusRecord` 类的新实例。

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


初始化 `EmfPlusRecord` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getType() {#getType--}
```
public short getType()
```


获取一个标识记录类型的 16 位无符号整数。

**Returns:**
短
### getFlags() {#getFlags--}
```
public short getFlags()
```


获取一个 16 位无符号整数，其中包含某些记录的操作执行方式及记录结构的信息。

**Returns:**
short - 标志。
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


设置一个 16 位无符号整数，其中包含某些记录的操作执行方式及记录结构的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 短 | 标志。 |

### getSize() {#getSize--}
```
public int getSize()
```


获取一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。

**Returns:**
int - 大小。
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


设置一个 32 位无符号整数，指定整个记录的 32 位对齐字节数，包括 12 字节的记录头和记录特定数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 大小。 |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


获取一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位\u2013对齐字节数。此数字不包括 12 字节的记录头。

**Returns:**
int - 数据的大小。
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


设置一个 32 位无符号整数，必须定义后续 RecordData 字段中数据的 32 位\u2013对齐字节数。此数字不包括 12 字节的记录头。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 数据的大小。 |

