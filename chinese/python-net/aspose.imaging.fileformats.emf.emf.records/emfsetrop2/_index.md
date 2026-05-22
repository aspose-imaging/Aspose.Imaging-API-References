---
title: "EmfSetRop2 类"
type: docs
weight: 1280
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---

**Summary:** The EMR_SETROP2 record defines a binary raster operation mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetRop2

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetRop2()](#EmfSetRop2__1) | 初始化 [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) 类的新实例。 |
| [EmfSetRop2(source)](#EmfSetRop2_source_2) | 初始化 [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| rop_2_mode | [WmfBinaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/) | r/w | 获取或设置一个 32 位无符号整数，指定光栅操作模式，并且<br/>            必须位于 WMF 二进制光栅操作枚举 ([MS-WMF] 第 2.1.1.2 节) 中。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetRop2() {#EmfSetRop2__1}


```
 EmfSetRop2() 
```

初始化 [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) 类的新实例。

### Constructor: EmfSetRop2(source) {#EmfSetRop2_source_2}


```
 EmfSetRop2(source) 
```

初始化 [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | 记录类型。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


