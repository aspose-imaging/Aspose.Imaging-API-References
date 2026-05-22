---
title: "فئة EmfPolylineTo16"
type: docs
weight: 950
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---

**Summary:** The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. <br/>            A line is drawn from the current position to the first point specified by the aPoints field by using the <br/>            current pen. For each additional line, drawing is performed from the ending point of the previous <br/>            line to the next point specified by aPoints.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPolylineTo16

**Inheritance:** EmfPolyShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPolylineTo16()](#EmfPolylineTo16__1) | يُهيئ مثيلًا جديدًا من الفئة [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) |
| [EmfPolylineTo16(source)](#EmfPolylineTo16_source_2) | يُهيئ مثيلًا جديدًا من الفئة [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/) |
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


### Constructor: EmfPolylineTo16() {#EmfPolylineTo16__1}


```
 EmfPolylineTo16() 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/)

### Constructor: EmfPolylineTo16(source) {#EmfPolylineTo16_source_2}


```
 EmfPolylineTo16(source) 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfPolylineTo16](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/)

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


