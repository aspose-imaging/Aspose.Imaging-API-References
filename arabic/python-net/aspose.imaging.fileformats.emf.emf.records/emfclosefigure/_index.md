---
title: "الفئة EmfCloseFigure"
type: docs
weight: 130
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/
---

**Summary:** This record closes an open figure in a path.<br/>            Processing the EMR_CLOSEFIGURE record MUST close the figure by drawing a line<br/>            from the current position to the first point of the figure, and then it MUST connect<br/>            the lines by using the line join style.If a figure is closed by processing the<br/>            EMR_LINETO record instead of the EMR_CLOSEFIGURE record, end caps are<br/>            used to create the corner instead of a join.EMR_LINETO is specified in section<br/>            2.3.5.13.<br/>            The EMR_CLOSEFIGURE record SHOULD only be used if there is an open path<br/>            bracket in the playback device context.<br/>            A figure in a path is open unless it is explicitly closed by processing this record.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCloseFigure

**Inheritance:** EmfPathBracketRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCloseFigure()](#EmfCloseFigure__1) | ينشئ مثيلًا جديدًا من الفئة [EmfCloseFigure](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCloseFigure() {#EmfCloseFigure__1}


```
 EmfCloseFigure() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfCloseFigure](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfclosefigure/).

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | المصدر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | نوع السجل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


