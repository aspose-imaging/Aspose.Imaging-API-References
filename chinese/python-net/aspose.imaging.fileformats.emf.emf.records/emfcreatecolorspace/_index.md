---
title: "EmfCreateColorSpace 类"
type: docs
weight: 270
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---

**Summary:** The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a<br/>            name consisting of ASCII characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpace

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfCreateColorSpace(source)](#EmfCreateColorSpace_source_1) | 初始化一个新的 [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| ih_cs | int | r/w | 获取或设置一个 32 位无符号整数，指定逻辑颜色空间<br/>            对象在 EMF 对象表（第 3.1.1.1 节）中的索引。必须保存此索引，以便该对象<br/>            可以被重新使用或修改。 |
| lcs | [WmfLogColorSpace](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) | r/w | 获取或设置一个 WMF LogColorSpace 对象（[MS-WMF] 第 2.2.2.11 节），它可以指定<br/>            以 ASCII 字符表示的颜色配置文件名称。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfCreateColorSpace(source) {#EmfCreateColorSpace_source_1}


```
 EmfCreateColorSpace(source) 
```

初始化一个新的 [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/) 类的实例。

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


