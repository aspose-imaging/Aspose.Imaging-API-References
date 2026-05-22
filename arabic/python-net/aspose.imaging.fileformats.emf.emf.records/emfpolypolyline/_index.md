---
title: "فئة EmfPolyPolyline"
type: docs
weight: 850
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/
---

**Summary:** The EMR_POLYPOLYLINE record specifies multiple series of connected line segments.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolyline

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolyPolyline()](#EmfPolyPolyline__1) | يُنشئ مثيلاً جديدًا من الفئة [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/). |
| [EmfPolyPolyline(source)](#EmfPolyPolyline_source_2) | يُنشئ مثيلاً جديدًا من الفئة [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | يحصل أو يعيّن مصفوفة من كائنات WMF PointS، المحددة في [MS-WMF] <br/>            القسم 2.2.2.16، والتي تحدد مصفوفة النقاط. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolyPolyline() {#EmfPolyPolyline__1}


```
 EmfPolyPolyline() 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/).

### Constructor: EmfPolyPolyline(source) {#EmfPolyPolyline_source_2}


```
 EmfPolyPolyline(source) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfPolyPolyline](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/).

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


