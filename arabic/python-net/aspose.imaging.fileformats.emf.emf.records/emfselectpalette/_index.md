---
title: "فئة EmfSelectPalette"
type: docs
weight: 1080
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/
---

**Summary:** The EMR_SELECTPALETTE record specifies a logical palette for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectPalette

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSelectPalette(source)](#EmfSelectPalette_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfSelectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد إما فهرس كائن LogPalette<br/>            (القسم 2.2.17) في جدول كائنات EMF أو القيمة DEFAULT_PALETTE، التي هي فهرس<br/>            لوحة كائن مخزون من تعداد StockObject (القسم 2.1.31). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectPalette(source) {#EmfSelectPalette_source_1}


```
 EmfSelectPalette(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfSelectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectpalette/) .

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


