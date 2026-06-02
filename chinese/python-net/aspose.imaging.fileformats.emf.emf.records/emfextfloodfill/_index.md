---
title: "EmfExtFloodFill 类"
type: docs
weight: 450
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/
---

**Summary:** The EMR_EXTFLOODFILL record fills an area of the display surface with the current brush

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtFloodFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfExtFloodFill(source)](#EmfExtFloodFill_source_1) | 初始化 [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | 获取或设置 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象与 <br/>            FloodFillMode 一起用于确定要填充的区域。 |
| flood_fill_mode | [EmfFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emffloodfill/) | r/w | 获取或设置一个 32 位无符号整数，指定如何使用 Color 值 <br/>            来确定洪水填充操作的区域。该值必须位于 FloodFill <br/>            枚举（第 2.1.13 节）中。 |
| size | int | r/w | 获取或设置记录的大小 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定 <br/>            填充开始的坐标（逻辑单位）。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfExtFloodFill(source) {#EmfExtFloodFill_source_1}


```
 EmfExtFloodFill(source) 
```

初始化 [EmfExtFloodFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextfloodfill/) 类的新实例。

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


