---
title: "فئة EmfPie"
type: docs
weight: 730
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/
---

**Summary:** The EMR_PIE record specifies a pie-shaped wedge bounded by the intersection of an ellipse and two <br/>            radials. The pie is outlined by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPie

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPie()](#EmfPie__1) | ينشئ مثيلاً جديدًا من الفئة [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
| [EmfPie(source)](#EmfPie_source_2) | ينشئ مثيلاً جديدًا من الفئة [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل الحدّي شاملة-شاملة. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن PointL 64 بت يحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية <br/>            للشعاع الثاني. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائنات WMF PointL 64 بت، المحددة في [MS-WMF] القسم 2.2.2.15، والتي <br/>            تحدد الإحداثيات، بوحدات منطقية، لنقطة النهاية للشعاع الأول. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPie() {#EmfPie__1}


```
 EmfPie() 
```

ينشئ مثيلاً جديدًا من الفئة [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

### Constructor: EmfPie(source) {#EmfPie_source_2}


```
 EmfPie(source) 
```

ينشئ مثيلاً جديدًا من الفئة [EmfPie](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpie/).

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


