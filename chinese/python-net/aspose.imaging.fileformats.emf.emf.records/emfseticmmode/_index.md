---
title: "EmfSetIcmMode 类"
type: docs
weight: 1160
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---

**Summary:** The EMR_SETICMMODE record specifies the mode of Image Color Management (ICM) for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetIcmMode(source)](#EmfSetIcmMode_source_1) | 初始化一个新的 [EmfSetIcmMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| icm_mode | [EmfIcmMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emficmmode/) | r/w | 获取或设置一个 32 位无符号整数，指定是启用还是禁用 ICM，<br/>            来自 ICMMode 枚举（第 2.1.18 节）。此值是回放设备上下文状态的一部分。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetIcmMode(source) {#EmfSetIcmMode_source_1}


```
 EmfSetIcmMode(source) 
```

初始化一个新的 [EmfSetIcmMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/) 类实例。

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


