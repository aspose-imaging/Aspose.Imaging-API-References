---
title: "فئة EmfFillRgn"
type: docs
weight: 500
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---

**Summary:** The EMR_FILLRGN record fills the specified region by using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFillRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfFillRgn()](#EmfFillRgn__1) | ينشئ مثيلاً جديداً من الفئة [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) |
| [EmfFillRgn(source)](#EmfFillRgn_source_2) | ينشئ مثيلاً جديداً من الفئة [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، <br/>            الذي يحدد المستطيل المحيط. |
| ih_brush | int | r/w | الحصول أو تعيين عدد صحيح غير موقع 32‑بت يحدد فهرس جدول كائنات EMF للفرشاة <br/>            لملء المنطقة. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | الحصول أو تعيين مصفوفة بطول RgnDataSize من البايتات التي تحتوي على كائن RegionData (section 2.2.24). |
| rgn_data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFillRgn() {#EmfFillRgn__1}


```
 EmfFillRgn() 
```

ينشئ مثيلاً جديداً من الفئة [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/)

### Constructor: EmfFillRgn(source) {#EmfFillRgn_source_2}


```
 EmfFillRgn(source) 
```

ينشئ مثيلاً جديداً من الفئة [EmfFillRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/)

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


