---
title: "فئة EmfAngleArc"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---

**Summary:** The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the <br/>            current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the <br/>            given radius and center. The length of the arc is defined by the given start and sweep angles

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAngleArc

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfAngleArc()](#EmfAngleArc__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/). |
| [EmfAngleArc(source)](#EmfAngleArc_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| center | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يضبط كائن WMF PointL 64 بت، المحدد في [MS-WMF] section 2.2.2.15، والذي <br/>            يحدد الإحداثيات المنطقية لمركز الدائرة. |
| نصف القطر | int | r/w | يحصل أو يضبط عددًا صحيحًا غير موقع 32 بت يحدد نصف قطر الدائرة، بوحدات منطقية. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| start_angle | float | r/w | يحصل أو يضبط عددًا عشريًا 32 بت يحدد زاوية بدء القوس، بالدرجات. |
| sweep_angle | float | r/w | يحصل أو يضبط عددًا عشريًا 32 بت يحدد زاوية دوران القوس، بالدرجات. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAngleArc() {#EmfAngleArc__1}


```
 EmfAngleArc() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/).

### Constructor: EmfAngleArc(source) {#EmfAngleArc_source_2}


```
 EmfAngleArc(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfAngleArc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/).

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


