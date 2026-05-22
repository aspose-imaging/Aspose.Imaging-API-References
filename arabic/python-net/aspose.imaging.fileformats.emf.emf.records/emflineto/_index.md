---
title: "فئة EmfLineTo"
type: docs
weight: 590
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/
---

**Summary:** The EMR_LINETO record specifies a line from the current position up to, but not including, the<br/>            specified point.It resets the current position to the specified point.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfLineTo

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfLineTo()](#EmfLineTo__1) | يُنشئ مثيلًا جديدًا من الفئة [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) . |
| [EmfLineTo(record)](#EmfLineTo_record_2) | يُنشئ مثيلًا جديدًا من الفئة [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | يحصل أو يعيّن كائن WMF PointL 64 بت، المحدد في [MS-WMF] القسم 2.2.2.15، <br/>            الذي يحدد إحداثيات نقطة نهاية الخط. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfLineTo() {#EmfLineTo__1}


```
 EmfLineTo() 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) .

### Constructor: EmfLineTo(record) {#EmfLineTo_record_2}


```
 EmfLineTo(record) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfLineTo](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emflineto/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | السجل. |

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


