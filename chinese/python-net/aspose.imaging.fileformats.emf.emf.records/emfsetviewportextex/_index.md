---
title: "EmfSetViewportExtEx 类"
type: docs
weight: 1330
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/
---

**Summary:** The EMR_SETVIEWPORTEXTEX record defines the viewport extent.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportExtEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetViewportExtEx()](#EmfSetViewportExtEx__1) | 初始化 [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) 类的新实例。 |
| [EmfSetViewportExtEx(source)](#EmfSetViewportExtEx_source_2) | 初始化 [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| extent | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | 获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），指定设备单位中的<br/>            水平和垂直范围。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetViewportExtEx() {#EmfSetViewportExtEx__1}


```
 EmfSetViewportExtEx() 
```

初始化 [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) 类的新实例。

### Constructor: EmfSetViewportExtEx(source) {#EmfSetViewportExtEx_source_2}


```
 EmfSetViewportExtEx(source) 
```

初始化 [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) 类的新实例。

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


