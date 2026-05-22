---
title: "فئة EmfPaintRgn"
type: docs
weight: 710
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---

**Summary:** The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the <br/>            playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPaintRgn

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfPaintRgn()](#EmfPaintRgn__1) | ينشئ مثيلاً جديدًا من الفئة [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/). |
| [EmfPaintRgn(source)](#EmfPaintRgn_source_2) | ينشئ مثيلاً جديدًا من الفئة [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL بحجم 128 بت، المحدد في [MS-WMF] القسم 2.2.2.19، <br/>            الذي يحدد المستطيل المحيط. |
| rgn_data | [EmfRegionData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondata/) | r/w | يحصل أو يعيّن مصفوفة بطول RgnDataSize من البايتات التي تحدد كائن RegionData (القسم <br/>            2.2.24) بوحدات منطقية. |
| rgn_data_size | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا بحجم 32 بت يحدد حجم بيانات المنطقة، بالبايت. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPaintRgn() {#EmfPaintRgn__1}


```
 EmfPaintRgn() 
```

ينشئ مثيلاً جديدًا من الفئة [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/).

### Constructor: EmfPaintRgn(source) {#EmfPaintRgn_source_2}


```
 EmfPaintRgn(source) 
```

ينشئ مثيلاً جديدًا من الفئة [EmfPaintRgn](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/).

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


