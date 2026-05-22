---
title: "EmfCreateColorSpaceW فئة"
type: docs
weight: 280
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---

**Summary:** The EMR_CREATECOLORSPACEW record creates a logical color space object from a color profile with<br/>            a name consisting of Unicode characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpaceW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCreateColorSpaceW(source)](#EmfCreateColorSpaceW_source_1) | يُنشئ مثيلًا جديدًا للفئة [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cb_data | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد الحجم، بالبايت، لحقل Data. |
| البيانات | System.Byte | r/w | يحصل أو يعيّن مصفوفة اختيارية من البايتات تحدد بيانات ملف تعريف اللون. |
| dw_flags | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يوفر معلومات حول البيانات في هذا السجل. |
| ih_cs | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس مساحة اللون المنطقية<br/>            في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن<br/>            أو تعديله. |
| lcs | [WmfLogColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/) | r/w | يحصل أو يعيّن كائن WMF LogColorSpaceW ([MS-WMF] القسم 2.2.2.12) يمكنه تحديد<br/>            اسم ملف تعريف اللون بحروف Unicode UTF16-LE. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateColorSpaceW(source) {#EmfCreateColorSpaceW_source_1}


```
 EmfCreateColorSpaceW(source) 
```

يُنشئ مثيلًا جديدًا للفئة [EmfCreateColorSpaceW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/) class.

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


