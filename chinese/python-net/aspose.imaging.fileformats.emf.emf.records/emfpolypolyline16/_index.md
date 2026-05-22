---
title: "EmfPolyPolyline16 类"
type: docs
weight: 860
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/
---

**Summary:** The EMR_POLYPOLYLINE16 record specifies multiple series of connected line segments.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolyline16

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPolyPolyline16()](#EmfPolyPolyline16__1) | 初始化一个新的 [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) 类实例。 |
| [EmfPolyPolyline16(source)](#EmfPolyPolyline16_source_2) | 初始化一个新的 [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | 获取或设置 WMF PointS 对象的数组，在 [MS-WMF] <br/>            第 2.2.2.16 节中指定，指定点的数组。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定设备单位中的边界矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfPolyPolyline16() {#EmfPolyPolyline16__1}


```
 EmfPolyPolyline16() 
```

初始化一个新的 [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) 类实例。

### Constructor: EmfPolyPolyline16(source) {#EmfPolyPolyline16_source_2}


```
 EmfPolyPolyline16(source) 
```

初始化一个新的 [EmfPolyPolyline16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline16/) 类实例。

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


