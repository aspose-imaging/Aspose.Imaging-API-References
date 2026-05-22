---
title: "EmfGlsRecord 类"
type: docs
weight: 550
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---

**Summary:** The EMR_GLSRECORD record specifies an OpenGL function.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfGlsRecord(source)](#EmfGlsRecord_source_1) | 初始化一个新的 [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| cb_data | int | r/w | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（字节）。<br/>            如果该值为零，则此记录不附加任何数据。 |
| 数据 | System.Byte | r/w | 获取或设置一个可选的字节数组，长度为 cbData，用于指定 OpenGL 函数的数据。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfGlsRecord(source) {#EmfGlsRecord_source_1}


```
 EmfGlsRecord(source) 
```

初始化一个新的 [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/) 类实例。

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


