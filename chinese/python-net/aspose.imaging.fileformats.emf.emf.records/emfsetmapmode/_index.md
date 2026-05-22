---
title: "EmfSetMapMode 类"
type: docs
weight: 1210
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/
---

**Summary:** The EMR_SETMAPMODE record specifies the mapping mode of the playback device context. <br/>            The mapping mode specifies the unit of measure used to transform page space units <br/>            into device space units, and also specifies the orientation of the device's x-axis and y-axis.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetMapMode

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetMapMode()](#EmfSetMapMode__1) | 初始化一个新的 [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) 类的实例。 |
| [EmfSetMapMode(record)](#EmfSetMapMode_record_2) | 初始化一个新的 [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| map_mode | [EmfMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/) | r/w | 获取或设置映射模式。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetMapMode() {#EmfSetMapMode__1}


```
 EmfSetMapMode() 
```

初始化一个新的 [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) 类的实例。

### Constructor: EmfSetMapMode(record) {#EmfSetMapMode_record_2}


```
 EmfSetMapMode(record) 
```

初始化一个新的 [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) 类的实例。

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


