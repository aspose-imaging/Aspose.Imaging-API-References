---
title: "EmfSetViewportOrgEx 类"
type: docs
weight: 1340
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---

**Summary:** The EMR_SETVIEWPORTORGEX record defines the viewport origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx__1) | 初始化 [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) 类的新实例。 |
| [EmfSetViewportOrgEx(source)](#EmfSetViewportOrgEx_source_2) | 初始化 [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置一个 64 位 WMF PointL 对象（[MS-WMF] 第 2.2.2.15 节），该对象指定<br/>            窗口在设备单位中的水平和垂直原点。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetViewportOrgEx() {#EmfSetViewportOrgEx__1}


```
 EmfSetViewportOrgEx() 
```

初始化 [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) 类的新实例。

### Constructor: EmfSetViewportOrgEx(source) {#EmfSetViewportOrgEx_source_2}


```
 EmfSetViewportOrgEx(source) 
```

初始化 [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) 类的新实例。

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


