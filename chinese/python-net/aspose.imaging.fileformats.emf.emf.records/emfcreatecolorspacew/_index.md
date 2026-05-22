---
title: "EmfCreateColorSpaceW 类"
type: docs
weight: 280
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---

**Summary:** The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with<br/>            a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpaceW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfCreateColorSpaceW(source)](#EmfCreateColorSpaceW_source_1) | 初始化 [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| cb_data | int | r/w | 获取或设置一个 32 位无符号整数，指定 Data 字段的大小（以字节为单位）。 |
| 数据 | System.Byte | r/w | 获取或设置一个可选的字节数组，指定颜色配置文件数据。 |
| dw_flags | int | r/w | 获取或设置一个 32 位无符号整数，提供此记录中数据的信息。 |
| ih_cs | int | r/w | 获取或设置一个 32 位无符号整数，指定逻辑颜色空间<br/>            对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便该对象<br/>            可以被重新使用或修改。 |
| lcs | [WmfLogColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) | r/w | 获取或设置一个 WMF LogColorSpaceW 对象（[MS-WMF] 第 2.2.2.12 节），它可以指定<br/>            以 Unicode UTF16-LE 字符表示的颜色配置文件名称。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfCreateColorSpaceW(source) {#EmfCreateColorSpaceW_source_1}


```
 EmfCreateColorSpaceW(source) 
```

初始化 [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) 类的新实例。

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


