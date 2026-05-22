---
title: "EmfArcTo فئة"
type: docs
weight: 50
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/
---

**Summary:** The EMR_ARCTO record specifies an elliptical arc. It resets the current position to the end point of the arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArcTo

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfArcTo()](#EmfArcTo__1) | ينشئ مثيلًا جديدًا من الفئة [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) . |
| [EmfArcTo(source)](#EmfArcTo_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل الحدودي. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL 64‑بت الذي يحدد إحداثيات نقطة النهاية الشعاعية الثانية <br/>            بوحدات منطقية. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي <br/>            يحدد إحداثيات نقطة النهاية الشعاعية الأولى، بوحدات منطقية. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfArcTo() {#EmfArcTo__1}


```
 EmfArcTo() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) .

### Constructor: EmfArcTo(source) {#EmfArcTo_source_2}


```
 EmfArcTo(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfArcTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarcto/) .

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


