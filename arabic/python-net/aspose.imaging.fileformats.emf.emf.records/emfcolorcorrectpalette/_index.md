---
title: "فئة EmfColorCorrectPalette"
type: docs
weight: 140
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---

**Summary:** The EMR_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette<br/>            object using WCS 1.0 values.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorCorrectPalette

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfColorCorrectPalette(source)](#EmfColorCorrectPalette_source_1) | ينشئ مثيلًا جديدًا للفئة [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| ih_palette | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد فهرس كائن لوحة ألوان منطقية<br/>            (القسم 2.2.17) في جدول كائنات EMF (القسم 3.1.1.1). |
| n_first_entry | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد فهرس أول إدخال لتصحيحه. |
| n_pal_entries | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد عدد إدخالات لوحة الألوان التي يجب تصحيحها. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfColorCorrectPalette(source) {#EmfColorCorrectPalette_source_1}


```
 EmfColorCorrectPalette(source) 
```

ينشئ مثيلًا جديدًا للفئة [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/).

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


