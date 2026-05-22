---
title: "EmfExcludeClipRect فئة"
type: docs
weight: 410
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---

**Summary:** The EMR_EXCLUDECLIPRECT record specifies a new clipping region that consists of the existing <br/>            clipping region minus the specified rectangle. <br/>            Note  Fields that are not described in this section are specified in section 2.3.2.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExcludeClipRect

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExcludeClipRect()](#EmfExcludeClipRect__1) | يُنشئ مثيلًا جديدًا من [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) فئة. |
| [EmfExcludeClipRect(source)](#EmfExcludeClipRect_source_2) | يُنشئ مثيلًا جديدًا من [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) فئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| clip | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن RectL WMF ([MS-WMF] القسم 2.2.2.19) الذي يحدد مستطيل القص <br/>            بوحدات منطقية. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExcludeClipRect() {#EmfExcludeClipRect__1}


```
 EmfExcludeClipRect() 
```

يُنشئ مثيلًا جديدًا من [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) فئة.

### Constructor: EmfExcludeClipRect(source) {#EmfExcludeClipRect_source_2}


```
 EmfExcludeClipRect(source) 
```

يُنشئ مثيلًا جديدًا من [EmfExcludeClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/) فئة.

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


