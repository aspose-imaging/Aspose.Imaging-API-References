---
title: "فئة EmfRoundRect"
type: docs
weight: 1020
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---

**Summary:** The EMR_ROUNDRECT record specifies a rectangle with rounded corners. The rectangle is outlined <br/>            by using the current pen and filled by using the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRoundRect

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfRoundRect()](#EmfRoundRect__1) | ينشئ مثيلاً جديدًا من الفئة [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) |
| [EmfRoundRect(source)](#EmfRoundRect_source_2) | ينشئ مثيلاً جديدًا من الفئة [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| box | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | يحصل أو يعيّن كائن WMF RectL 128‑بت، المحدد في [MS-WMF] القسم 2.2.2.19، والذي <br/>            يحدد المستطيل الشامل‑الشامل للرسم. |
| corner | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | يحصل أو يعيّن كائن WMF SizeL 64‑بت، المحدد في [MS-WMF] القسم 2.2.2.22، والذي <br/>            يحدد العرض والارتفاع، بوحدات إحداثية منطقية، للبيضاوي المستخدم لرسم الزوايا المستديرة. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRoundRect() {#EmfRoundRect__1}


```
 EmfRoundRect() 
```

ينشئ مثيلاً جديدًا من الفئة [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/)

### Constructor: EmfRoundRect(source) {#EmfRoundRect_source_2}


```
 EmfRoundRect(source) 
```

ينشئ مثيلاً جديدًا من الفئة [EmfRoundRect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfroundrect/)

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


