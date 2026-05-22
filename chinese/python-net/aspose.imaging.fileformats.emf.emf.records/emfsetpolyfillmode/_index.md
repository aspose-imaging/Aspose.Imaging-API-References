---
title: "EmfSetPolyFillMode 类"
type: docs
weight: 1270
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---

**Summary:** The EMR_SETPOLYFILLMODE record defines polygon fill mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPolyFillMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode__1) | 初始化 [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) 类的新实例。 |
| [EmfSetPolyFillMode(source)](#EmfSetPolyFillMode_source_2) | 初始化 [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| polygon_fill_mode | [EmfPolygonFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpolygonfillmode/) | r/w | 获取或设置一个 32 位无符号整数，指定多边形填充模式，并且<br/>            必须位于 PolygonFillMode（第 2.1.27 节）枚举中。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetPolyFillMode() {#EmfSetPolyFillMode__1}


```
 EmfSetPolyFillMode() 
```

初始化 [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) 类的新实例。

### Constructor: EmfSetPolyFillMode(source) {#EmfSetPolyFillMode_source_2}


```
 EmfSetPolyFillMode(source) 
```

初始化 [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) 类的新实例。

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


