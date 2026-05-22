---
title: "فئة EmfFillPath"
type: docs
weight: 490
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/
---

**Summary:** The EMR_FILLPATH record closes any open figures in the current path and fills the path's interior by <br/>            using the current brush and polygon-filling mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillPath

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfFillPath()](#EmfFillPath__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/). |
| [EmfFillPath(source)](#EmfFillPath_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، <br/>            والذي يحدد المستطيل الحدودي بوحدات الجهاز. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFillPath() {#EmfFillPath__1}


```
 EmfFillPath() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/).

### Constructor: EmfFillPath(source) {#EmfFillPath_source_2}


```
 EmfFillPath(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfFillPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillpath/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | المصدر. |

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


