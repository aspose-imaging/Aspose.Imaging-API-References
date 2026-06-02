---
title: "EmfSetWindowExtEx 类"
type: docs
weight: 1350
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/
---

**Summary:** The EMR_SETWINDOWEXTEX record defines the window extent.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowExtEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetWindowExtEx()](#EmfSetWindowExtEx__1) | 初始化 [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/) 类的新实例。 |
| [EmfSetWindowExtEx(source)](#EmfSetWindowExtEx_source_2) | 初始化 [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| extent | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | 获取或设置一个 64 位 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），该对象指定<br/>            逻辑单位下的水平和垂直范围。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetWindowExtEx() {#EmfSetWindowExtEx__1}


```
 EmfSetWindowExtEx() 
```

初始化 [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/) 类的新实例。

### Constructor: EmfSetWindowExtEx(source) {#EmfSetWindowExtEx_source_2}


```
 EmfSetWindowExtEx(source) 
```

初始化 [EmfSetWindowExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindowextex/) 类的新实例。

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


