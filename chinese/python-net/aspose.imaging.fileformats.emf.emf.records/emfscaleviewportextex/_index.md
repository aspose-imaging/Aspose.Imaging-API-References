---
title: "EmfScaleViewportExtex 类"
type: docs
weight: 1040
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---

**Summary:** The EMR_SCALEVIEWPORTEXTEX record respecifies the viewport for a device context by using the<br/>            ratios formed by the specified multiplicands and divisors.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfScaleViewportExtex

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex__1) | 初始化 [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) 类的新实例。 |
| [EmfScaleViewportExtex(source)](#EmfScaleViewportExtex_source_2) | 初始化 [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| x_denom | int | r/w | 获取或设置指定水平除数的 32 位有符号整数。不能为零。 |
| x_num | int | r/w | 获取或设置指定水平乘数的 32 位有符号整数。不能为零。 |
| y_denom | int | r/w | 获取或设置指定垂直除数的 32 位有符号整数。不能为零。 |
| y_num | int | r/w | 获取或设置指定垂直乘数的 32 位有符号整数。不能为零。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfScaleViewportExtex() {#EmfScaleViewportExtex__1}


```
 EmfScaleViewportExtex() 
```

初始化 [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) 类的新实例。

### Constructor: EmfScaleViewportExtex(source) {#EmfScaleViewportExtex_source_2}


```
 EmfScaleViewportExtex(source) 
```

初始化 [EmfScaleViewportExtex](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/) 类的新实例。

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


