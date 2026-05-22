---
title: "فئة EmfArc"
type: docs
weight: 40
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/
---

**Summary:** The EMR_ARC record specifies an elliptical arc.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfArc()](#EmfArc__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) . |
| [EmfArc(source)](#EmfArc_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل الحدّي شاملة-شاملة. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت يحدد الإحداثيات، بوحدات منطقية، لـ <br/>            نقطة النهاية للخط الشعاعي الذي يحدد نقطة النهاية للقوس. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL بحجم 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، والذي <br/>            يحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للخط الشعاعي الذي يحدد <br/>            نقطة البداية للقوس. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfArc() {#EmfArc__1}


```
 EmfArc() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) .

### Constructor: EmfArc(source) {#EmfArc_source_2}


```
 EmfArc(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfarc/) .

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


