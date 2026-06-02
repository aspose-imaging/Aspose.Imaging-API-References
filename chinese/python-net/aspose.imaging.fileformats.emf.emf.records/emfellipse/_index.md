---
title: "EmfEllipse 类"
type: docs
weight: 370
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/
---

**Summary:** The EMR_ELLIPSE record specifies an ellipse. The center of the ellipse is the center of the specified <br/>            bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEllipse

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfEllipse()](#EmfEllipse__1) | 初始化 [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) 类的新实例。 |
| [EmfEllipse(source)](#EmfEllipse_source_2) | 初始化 [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 128 位 (WMF) RectL 对象，在 [MS-WMF] 第 2.2.2.19 节中指定，<br/>            指定包含式的边界矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfEllipse() {#EmfEllipse__1}


```
 EmfEllipse() 
```

初始化 [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) 类的新实例。

### Constructor: EmfEllipse(source) {#EmfEllipse_source_2}


```
 EmfEllipse(source) 
```

初始化 [EmfEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfellipse/) 类的新实例。

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


