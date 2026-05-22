---
title: "EmfStrokeAndFillPath 类"
type: docs
weight: 1420
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/
---

**Summary:** The EMR_STROKEANDFILLPATH record closes any open figures in a path, strokes the outline of the<br/>            path by using the current pen, and fills its interior by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfStrokeAndFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfStrokeAndFillPath()](#EmfStrokeAndFillPath__1) | 初始化 [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) 类的新实例。 |
| [EmfStrokeAndFillPath(source)](#EmfStrokeAndFillPath_source_2) | 初始化 [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 128 位 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），<br/>            指定以设备单位表示的边界矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfStrokeAndFillPath() {#EmfStrokeAndFillPath__1}


```
 EmfStrokeAndFillPath() 
```

初始化 [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) 类的新实例。

### Constructor: EmfStrokeAndFillPath(source) {#EmfStrokeAndFillPath_source_2}


```
 EmfStrokeAndFillPath(source) 
```

初始化 [EmfStrokeAndFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfstrokeandfillpath/) 类的新实例。

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


