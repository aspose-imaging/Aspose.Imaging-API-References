---
title: "EmfFillRgn 类"
type: docs
weight: 500
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---

**Summary:** The EMR_FILLRGN record fills the specified region by using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfFillRgn()](#EmfFillRgn__1) | 初始化 [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) 类的新实例。 |
| [EmfFillRgn(source)](#EmfFillRgn_source_2) | 初始化 [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 128 位 WMF RectL 对象，在 [MS-WMF] 第 2.2.2.19 节中指定，<br/>            该对象指定边界矩形。 |
| ih_brush | int | r/w | 获取或设置一个 32 位无符号整数，指定用于填充区域的画笔 EMF 对象表索引 <br/>            。 |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | 获取或设置一个长度为 RgnDataSize 的字节数组，包含一个 RegionData（section 2.2.24）对象。 |
| rgn_data_size | int | r/w | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfFillRgn() {#EmfFillRgn__1}


```
 EmfFillRgn() 
```

初始化 [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) 类的新实例。

### Constructor: EmfFillRgn(source) {#EmfFillRgn_source_2}


```
 EmfFillRgn(source) 
```

初始化 [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) 类的新实例。

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


