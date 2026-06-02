---
title: "فئة EmfPolyPolygon"
type: docs
weight: 830
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---

**Summary:** The EMR_POLYPOLYGON record specifies a series of closed polygons.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolyPolygon()](#EmfPolyPolygon__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) . |
| [EmfPolyPolygon(source)](#EmfPolyPolygon_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) . |
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


### Constructor: EmfPolyPolygon() {#EmfPolyPolygon__1}


```
 EmfPolyPolygon() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) .

### Constructor: EmfPolyPolygon(source) {#EmfPolyPolygon_source_2}


```
 EmfPolyPolygon(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPolyPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/) .

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


