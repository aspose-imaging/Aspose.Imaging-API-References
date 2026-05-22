---
title: "EmfChord 类"
type: docs
weight: 110
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | 初始化 [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) 类的新实例。 |
| [EmfChord(source)](#EmfChord_source_2) | 初始化 [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置 128 位 WMF RectL 对象，在 [MS-WMF] 第 2.2.2.19 节中指定，<br/>            指定包含-包含的边界矩形。 |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个64位 WMF PointL 对象，指定径向的逻辑坐标，<br/>            该径向定义和弦的结束端点。 |
| size | int | r/w | 获取或设置记录的大小 |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个64位 WMF PointL 对象，指定于 [MS-WMF] 第 2.2.2.15 节，<br/>            指定径向的逻辑坐标，定义和弦的起始端点。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

初始化 [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) 类的新实例。

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

初始化 [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) 类的新实例。

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


