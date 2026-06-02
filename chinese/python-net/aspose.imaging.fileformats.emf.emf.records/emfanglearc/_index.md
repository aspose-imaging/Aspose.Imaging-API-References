---
title: "EmfAngleArc 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---

**Summary:** The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the <br/>            current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the <br/>            given radius and center. The length of the arc is defined by the given start and sweep angles

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAngleArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfAngleArc()](#EmfAngleArc__1) | 初始化 [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) 类的一个新实例。 |
| [EmfAngleArc(source)](#EmfAngleArc_source_2) | 初始化 [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) 类的一个新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| center | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个 64 位 WMF PointL 对象，在 [MS-WMF] 第 2.2.2.15 节中指定，<br/>            用于指定圆心的逻辑坐标。 |
| 半径 | int | r/w | 获取或设置一个 32 位无符号整数，指定圆的半径（逻辑单位）。 |
| size | int | r/w | 获取或设置记录的大小 |
| start_angle | float | r/w | 获取或设置一个 32 位浮点数，指定弧的起始角度（度）。 |
| sweep_angle | float | r/w | 获取或设置一个 32 位浮点数，指定弧的扫过角度（度）。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfAngleArc() {#EmfAngleArc__1}


```
 EmfAngleArc() 
```

初始化 [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) 类的一个新实例。

### Constructor: EmfAngleArc(source) {#EmfAngleArc_source_2}


```
 EmfAngleArc(source) 
```

初始化 [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/) 类的一个新实例。

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


