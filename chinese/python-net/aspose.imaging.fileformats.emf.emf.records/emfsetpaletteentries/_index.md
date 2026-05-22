---
title: "EmfSetPaletteEntries 类"
type: docs
weight: 1250
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---

**Summary:** The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing<br/>            LogPalette (section 2.2.17) object.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPaletteEntries

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetPaletteEntries(source)](#EmfSetPaletteEntries_source_1) | 初始化 [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_pal_entries | int[] | r/w | 获取或设置一个 LogPaletteEntry (section 2.2.18) 对象数组，的<br/>            NumberOfEntries 长度，指定调色板条目数据。Values 成员不包含任何值。 |
| ih_pal | int | r/w | 获取或设置一个 32 位无符号整数，指定调色板 EMF 对象表索引。 |
| numberof_entries | int | r/w | 获取或设置一个 32 位无符号整数，指定条目数量。 |
| size | int | r/w | 获取或设置记录的大小 |
| 起始 | int | r/w | 获取或设置一个 32 位无符号整数，指定要设置的第一个条目的索引。 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetPaletteEntries(source) {#EmfSetPaletteEntries_source_1}


```
 EmfSetPaletteEntries(source) 
```

初始化 [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) 类的新实例。

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


