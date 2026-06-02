---
title: "EmfOffsetClipRgn 类"
type: docs
weight: 690
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/
---

**Summary:** The EMR_OFFSETCLIPRGN record moves the current clipping region in the playback device context <br/>            by the specified offsets.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfOffsetClipRgn

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfOffsetClipRgn()](#EmfOffsetClipRgn__1) | 初始化一个新的 [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) 类实例。 |
| [EmfOffsetClipRgn(source)](#EmfOffsetClipRgn_source_2) | 初始化一个新的 [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定<br/>            逻辑单位中的水平和垂直偏移。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfOffsetClipRgn() {#EmfOffsetClipRgn__1}


```
 EmfOffsetClipRgn() 
```

初始化一个新的 [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) 类实例。

### Constructor: EmfOffsetClipRgn(source) {#EmfOffsetClipRgn_source_2}


```
 EmfOffsetClipRgn(source) 
```

初始化一个新的 [EmfOffsetClipRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfoffsetcliprgn/) 类实例。

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


