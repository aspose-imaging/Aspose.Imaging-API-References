---
title: "فئة EmfPolygon"
type: docs
weight: 900
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---

**Summary:** The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by <br/>            straight lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolygon

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolygon()](#EmfPolygon__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) . |
| [EmfPolygon(source)](#EmfPolygon_source_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| a_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن مصفوفة من كائنات WMF PointL ([MS-WMF] القسم 2.2.2.15) التي تحدد بيانات النقاط، بوحدات منطقية. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت ([MS-WMF] القسم 2.2.2.19) الذي يحدد المستطيل الحدّي، بوحدات الجهاز. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPolygon() {#EmfPolygon__1}


```
 EmfPolygon() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) .

### Constructor: EmfPolygon(source) {#EmfPolygon_source_2}


```
 EmfPolygon(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/) .

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


