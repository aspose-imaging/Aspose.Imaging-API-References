---
title: "EmfExtCreateFontIndirectW 类"
type: docs
weight: 420
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---

**Summary:** The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreateFontIndirectW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW__1) | 初始化 [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) 类的新实例。 |
| [EmfExtCreateFontIndirectW(source)](#EmfExtCreateFontIndirectW_source_2) | 初始化 [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| elw | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | r/w | 获取或设置一个 LogFontExDv 对象（第 2.2.15 节），该对象指定逻辑字体。<br/>            可能会出现 LogFont 对象 2.2.13 作为替代。[90]下面描述了确定此字段中对象类型的过程。 |
| ih_fonts | int | r/w | 获取或设置一个 32 位无符号整数，指定逻辑字体对象在 EMF 对象表（第 3.1.1.1 节）中的索引。<br/>            必须保存此索引，以便能够重新使用或修改该对象。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW__1}


```
 EmfExtCreateFontIndirectW() 
```

初始化 [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) 类的新实例。

### Constructor: EmfExtCreateFontIndirectW(source) {#EmfExtCreateFontIndirectW_source_2}


```
 EmfExtCreateFontIndirectW(source) 
```

初始化 [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) 类的新实例。

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


