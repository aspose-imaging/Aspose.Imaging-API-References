---
title: "EmfFrameRgn 类"
type: docs
weight: 530
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---

**Summary:** The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFrameRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfFrameRgn()](#EmfFrameRgn__1) | 初始化一个新的 [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) 类实例。 |
| [EmfFrameRgn(source)](#EmfFrameRgn_source_2) | 初始化一个新的 [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置 128 位 WMF RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，用于<br/>            指定边界矩形。 |
| height | int | r/w | 获取或设置一个指定水平画笔 <br/>            笔画高度的 32 位有符号整数，单位为逻辑单位。 |
| ih_brush | int | r/w | 获取或设置一个指定画笔 EMF 对象表索引的 32 位无符号整数。 |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | 获取或设置一个 RgnDataSize 长度的字节数组，用于指定 RegionData 对象，<br/>            单位为逻辑单位 |
| rgn_data_size | int | r/w | 获取或设置一个 32 位无符号整数，指定区域数据的大小（以字节为单位）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| width | int | r/w | 获取或设置一个指定垂直画笔笔画宽度的 32 位有符号整数，单位为逻辑单位。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfFrameRgn() {#EmfFrameRgn__1}


```
 EmfFrameRgn() 
```

初始化一个新的 [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) 类实例。

### Constructor: EmfFrameRgn(source) {#EmfFrameRgn_source_2}


```
 EmfFrameRgn(source) 
```

初始化一个新的 [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/) 类实例。

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


