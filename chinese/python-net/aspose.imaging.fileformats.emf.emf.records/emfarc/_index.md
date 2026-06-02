---
title: "EmfArc 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | 初始化 [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) 类的新实例。 |
| [EmfArc(source)](#EmfArc_source_2) | 初始化 [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置 128 位 WMF RectL 对象，在 [MS-WMF] 第 2.2.2.19 节中指定，<br/>            指定包含-包含的边界矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置 64 位 WMF PointL 对象，指定以逻辑单位表示的坐标，<br/>            用于定义弧线结束点的径向线的结束点。 |
| size | int | r/w | 获取或设置记录的大小 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置 64 位 WMF PointL 对象，在 [MS-WMF] 第 2.2.2.15 节中指定，<br/>            指定以逻辑单位表示的坐标，表示定义弧线起始点的径向线的结束点。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

初始化 [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) 类的新实例。

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

初始化 [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) 类的新实例。

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


