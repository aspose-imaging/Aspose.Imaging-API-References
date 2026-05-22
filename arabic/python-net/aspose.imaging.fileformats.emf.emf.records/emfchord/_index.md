---
title: "EmfChord فئة"
type: docs
weight: 110
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---

**Summary:** The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an <br/>            ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled <br/>            by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfChord

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfChord()](#EmfChord__1) | ينشئ مثيلًا جديدًا من الفئة [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) . |
| [EmfChord(source)](#EmfChord_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل الحدّي شاملة-شاملة. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL 64‑بت الذي يحدد الإحداثيات المنطقية لـ <br/>            نقطة النهاية الشعاعية التي تحدد نهاية الوتر. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي <br/>            يحدد الإحداثيات المنطقية لنقطة النهاية الشعاعية التي تحدد بداية الوتر. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfChord() {#EmfChord__1}


```
 EmfChord() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) .

### Constructor: EmfChord(source) {#EmfChord_source_2}


```
 EmfChord(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfChord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfchord/) .

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


