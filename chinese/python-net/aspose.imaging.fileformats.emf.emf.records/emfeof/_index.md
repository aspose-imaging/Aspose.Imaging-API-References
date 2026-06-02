---
title: "EmfEof 类"
type: docs
weight: 390
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---

**Summary:** The EMR_EOF record indicates the end of the metafile and specifies a palette.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfEof

**Inheritance:** EmfControlRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfEof()](#EmfEof__1) | 初始化 [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) 类的一个新实例。 |
| [EmfEof(record)](#EmfEof_record_2) | 初始化 [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) 类的一个新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| palette_argb_32_entries | int[] | r/w | 获取或设置一个可选缓冲区，包含调色板数据，该缓冲区不需要与 EMR_EOF <br/>            记录的固定部分连续。因此，此缓冲区中标记为 <br/>            "UndefinedSpace" 的字段是可选的，必须被忽略。<br/>            此字段的大小必须是 4 字节的倍数。 |
| size | int | r/w | 获取或设置记录的大小 |
| size_last | int | r/w | 获取或设置一个 32 位无符号整数，该整数必须与 Size 相同，并且必须是记录的最后 <br/>            一个字段，从而也是元文件的最后字段。如果存在 LogPaletteEntry 对象，<br/>            必须位于此字段之前。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfEof() {#EmfEof__1}


```
 EmfEof() 
```

初始化 [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) 类的一个新实例。

### Constructor: EmfEof(record) {#EmfEof_record_2}


```
 EmfEof(record) 
```

初始化 [EmfEof](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfeof/) 类的一个新实例。

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


