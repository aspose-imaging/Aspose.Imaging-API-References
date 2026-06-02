---
title: "EmfSetWindowOrgEx 类"
type: docs
weight: 1360
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/
---

**Summary:** The EMR_SETWINDOWORGEX record defines the window origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWindowOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetWindowOrgEx()](#EmfSetWindowOrgEx__1) | 初始化一个新的 [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) 类实例。 |
| [EmfSetWindowOrgEx(source)](#EmfSetWindowOrgEx_source_2) | 初始化一个新的 [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定<br/>            窗口的水平和垂直原点（以逻辑单位计）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetWindowOrgEx() {#EmfSetWindowOrgEx__1}


```
 EmfSetWindowOrgEx() 
```

初始化一个新的 [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) 类实例。

### Constructor: EmfSetWindowOrgEx(source) {#EmfSetWindowOrgEx_source_2}


```
 EmfSetWindowOrgEx(source) 
```

初始化一个新的 [EmfSetWindowOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetwindoworgex/) 类实例。

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


