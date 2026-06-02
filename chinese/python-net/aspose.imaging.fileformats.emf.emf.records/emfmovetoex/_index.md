---
title: "EmfMoveToEx 类"
type: docs
weight: 650
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/
---

**Summary:** The EMR_MOVETOEX record specifies coordinates of the new current position, in logical units.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMoveToEx

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfMoveToEx()](#EmfMoveToEx__1) | 初始化一个新的 [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/) 类实例。 |
| [EmfMoveToEx(record)](#EmfMoveToEx_record_2) | 初始化一个新的 [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| offset | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个 64 位 WMF PointL 对象，指定于 [MS-WMF] 第 2.2.2.15 节，<br/>            用于指定新当前位置信息的逻辑坐标。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfMoveToEx() {#EmfMoveToEx__1}


```
 EmfMoveToEx() 
```

初始化一个新的 [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/) 类实例。

### Constructor: EmfMoveToEx(record) {#EmfMoveToEx_record_2}


```
 EmfMoveToEx(record) 
```

初始化一个新的 [EmfMoveToEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmovetoex/) 类实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 该记录。 |

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


