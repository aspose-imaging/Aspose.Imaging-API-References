---
title: "فئة EmfPolyPolygon16"
type: docs
weight: 840
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/
---

**Summary:** The EMR_POLYPOLYGON16 record specifies a series of closed polygons. Each polygon is outlined <br/>            using the current pen, and filled using the current brush and polygon fill mode. The polygons drawn <br/>            by this record can overlap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolyPolygon16

**Inheritance:** EmfPolyPolyShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolyPolygon16()](#EmfPolyPolygon16__1) | ينشئ نسخة جديدة من الفئة [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) . |
| [EmfPolyPolygon16(source)](#EmfPolyPolygon16_source_2) | ينشئ نسخة جديدة من الفئة [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) . |
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


### Constructor: EmfPolyPolygon16() {#EmfPolyPolygon16__1}


```
 EmfPolyPolygon16() 
```

ينشئ نسخة جديدة من الفئة [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) .

### Constructor: EmfPolyPolygon16(source) {#EmfPolyPolygon16_source_2}


```
 EmfPolyPolygon16(source) 
```

ينشئ نسخة جديدة من الفئة [EmfPolyPolygon16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon16/) .

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


