---
title: "EmfSetTextColor 类"
type: docs
weight: 1310
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/
---

**Summary:** The EMR_SETTEXTCOLOR record defines the current text color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextColor

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetTextColor()](#EmfSetTextColor__1) | 初始化一个新的 [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) 类实例。 |
| [EmfSetTextColor(source)](#EmfSetTextColor_source_2) | 初始化一个新的 [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | 获取或设置一个 WMF ColorRef 对象（[MS-WMF] 第 2.2.2.8 节），该对象指定文本颜色值。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetTextColor() {#EmfSetTextColor__1}


```
 EmfSetTextColor() 
```

初始化一个新的 [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) 类实例。

### Constructor: EmfSetTextColor(source) {#EmfSetTextColor_source_2}


```
 EmfSetTextColor(source) 
```

初始化一个新的 [EmfSetTextColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextcolor/) 类实例。

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


