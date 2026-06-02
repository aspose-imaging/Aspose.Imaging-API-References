---
title: "EmfSelectClipPath 类"
type: docs
weight: 1060
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---

**Summary:** The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback <br/>            device context, combining the new region with any existing clipping region using the specified mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectClipPath

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSelectClipPath()](#EmfSelectClipPath__1) | 初始化 [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) 类的新实例。 |
| [EmfSelectClipPath(source)](#EmfSelectClipPath_source_2) | 初始化 [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | 获取或设置一个 32 位无符号整数，用于指定路径的使用方式。该 <br/>            值必须位于 RegionMode 枚举中（第 2.1.29 节）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSelectClipPath() {#EmfSelectClipPath__1}


```
 EmfSelectClipPath() 
```

初始化 [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) 类的新实例。

### Constructor: EmfSelectClipPath(source) {#EmfSelectClipPath_source_2}


```
 EmfSelectClipPath(source) 
```

初始化 [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) 类的新实例。

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


