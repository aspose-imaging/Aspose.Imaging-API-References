---
title: "فئة EmfCreatePalette"
type: docs
weight: 310
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---

**Summary:** The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePalette

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCreatePalette(source)](#EmfCreatePalette_source_1) | ينشئ نسخة جديدة من الفئة [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن لوحة الألوان المنطقية<br/>            في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن<br/>            إعادة استخدام هذا الكائن أو تعديله. |
| log_palette | [EmfLogPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpalette/) | r/w | يحصل أو يعيّن كائن LogPalette (القسم 2.2.17). يجب أن يكون حقل Version لهذا الكائن<br/>            مضبوًًا على 0x0300. إذا كانت قيمة NumberOfEntries في هذا الكائن صفرًا، يجب أن تفشل معالجة<br/>            هذا السجل. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreatePalette(source) {#EmfCreatePalette_source_1}


```
 EmfCreatePalette(source) 
```

ينشئ نسخة جديدة من الفئة [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) .

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


