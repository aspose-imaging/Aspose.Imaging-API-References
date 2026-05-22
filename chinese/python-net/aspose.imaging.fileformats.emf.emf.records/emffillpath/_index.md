---
title: "EmfFillPath 类"
type: docs
weight: 490
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/
---

**Summary:** The EMR_FILLPATH record closes any open figures in the current path and fills the path's interior by <br/>            using the current brush and polygon-filling mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfFillPath()](#EmfFillPath__1) | 初始化一个新的 [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/) 类实例。 |
| [EmfFillPath(source)](#EmfFillPath_source_2) | 初始化一个新的 [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 128 位 WMF RectL 对象，定义于 [MS-WMF] 第 2.2.2.19 节，<br/>            用于指定以设备单位表示的边界矩形。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfFillPath() {#EmfFillPath__1}


```
 EmfFillPath() 
```

初始化一个新的 [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/) 类实例。

### Constructor: EmfFillPath(source) {#EmfFillPath_source_2}


```
 EmfFillPath(source) 
```

初始化一个新的 [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/) 类实例。

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


