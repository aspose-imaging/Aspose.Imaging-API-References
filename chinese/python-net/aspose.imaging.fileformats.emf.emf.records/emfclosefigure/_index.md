---
title: "EmfCloseFigure 类"
type: docs
weight: 130
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---

**Summary:** This record closes an open figure in a path.<br/>            Processing the EMR_CLOSEFIGURE record MUST close the figure by drawing a line<br/>            from the current position to the first point of the figure, and then it MUST connect<br/>            the lines by using the line join style.If a figure is closed by processing the<br/>            EMR_LINETO record instead of the EMR_CLOSEFIGURE record, end caps are<br/>            used to create the corner instead of a join.EMR_LINETO is specified in section<br/>            2.3.5.13.<br/>            The EMR_CLOSEFIGURE record SHOULD only be used if there is an open path<br/>            bracket in the playback device context.<br/>            A figure in a path is open unless it is explicitly closed by processing this record.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCloseFigure

**Inheritance:** EmfPathBracketRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfCloseFigure()](#EmfCloseFigure__1) | 初始化 [EmfCloseFigure](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfCloseFigure() {#EmfCloseFigure__1}


```
 EmfCloseFigure() 
```

初始化 [EmfCloseFigure](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/) 类的新实例。

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


