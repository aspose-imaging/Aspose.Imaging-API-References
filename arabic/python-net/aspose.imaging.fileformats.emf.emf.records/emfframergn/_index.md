---
title: "EmfFrameRgn فئة"
type: docs
weight: 530
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---

**Summary:** The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfFrameRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfFrameRgn()](#EmfFrameRgn__1) | ينشئ مثيلًا جديدًا من الفئة [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/). |
| [EmfFrameRgn(source)](#EmfFrameRgn_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL 128-بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل المحيط. |
| height | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد ارتفاع ضربة الفرشاة الأفقية <br/>            بوحدات منطقية. |
| ih_brush | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس جدول كائنات EMF للفرشاة. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | يحصل أو يعيّن مصفوفة بطول RgnDataSize من البايتات التي تحدد كائن RegionData، <br/>            بوحدات منطقية |
| rgn_data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| width | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32-بت يحدد عرض ضربة الفرشاة العمودية، بوحدات منطقية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfFrameRgn() {#EmfFrameRgn__1}


```
 EmfFrameRgn() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/).

### Constructor: EmfFrameRgn(source) {#EmfFrameRgn_source_2}


```
 EmfFrameRgn(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfFrameRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfframergn/).

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


