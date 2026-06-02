---
title: "EmfPolygon 类"
type: docs
weight: 900
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---

**Summary:** The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPolygon()](#EmfPolygon__1) | 初始化 [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) 类的新实例。 |
| [EmfPolygon(source)](#EmfPolygon_source_2) | 初始化 [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置 WMF PointL 对象数组（[MS-WMF] 第 2.2.2.15 节），指定以逻辑单位表示的点数据。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfPolygon() {#EmfPolygon__1}


```
 EmfPolygon() 
```

初始化 [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) 类的新实例。

### Constructor: EmfPolygon(source) {#EmfPolygon_source_2}


```
 EmfPolygon(source) 
```

初始化 [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) 类的新实例。

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


