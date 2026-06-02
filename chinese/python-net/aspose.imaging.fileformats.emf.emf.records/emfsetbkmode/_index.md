---
title: "EmfSetBkMode 类"
type: docs
weight: 1110
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---

**Summary:** The EMR_SETBKMODE record specifies the background mix mode of the playback device context.<br/>            The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetBkMode()](#EmfSetBkMode__1) | 初始化一个新的 [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) 类的实例。 |
| [EmfSetBkMode(source)](#EmfSetBkMode_source_2) | 初始化一个新的 [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | 获取或设置一个 32 位无符号整数，指定背景模式<br/>            并且必须位于 BackgroundMode（第 2.1.4 节）枚举中。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetBkMode() {#EmfSetBkMode__1}


```
 EmfSetBkMode() 
```

初始化一个新的 [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) 类的实例。

### Constructor: EmfSetBkMode(source) {#EmfSetBkMode_source_2}


```
 EmfSetBkMode(source) 
```

初始化一个新的 [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/) 类的实例。

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


