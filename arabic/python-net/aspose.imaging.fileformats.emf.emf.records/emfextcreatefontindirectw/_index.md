---
title: "EmfExtCreateFontIndirectW فئة"
type: docs
weight: 420
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---

**Summary:** The EMR_EXTCREATEFONTINDIRECTW record defines a logical font for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreateFontIndirectW

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW__1) | ينشئ مثيلًا جديدًا من الفئة [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) . |
| [EmfExtCreateFontIndirectW(source)](#EmfExtCreateFontIndirectW_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| elw | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | r/w | يحصل أو يعيّن كائن LogFontExDv (القسم 2.2.15)، الذي يحدد الخط المنطقي. قد يكون كائن<br/>            LogFont 2.2.13 موجودًا بدلاً من ذلك.[90] العملية لتحديد نوع<br/>            الكائن في هذا الحقل موصوفة أدناه. |
| ih_fonts | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد فهرس كائن الخط المنطقي<br/>            في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن إعادة استخدام هذا الكائن<br/>            أو تعديله. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW__1}


```
 EmfExtCreateFontIndirectW() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) .

### Constructor: EmfExtCreateFontIndirectW(source) {#EmfExtCreateFontIndirectW_source_2}


```
 EmfExtCreateFontIndirectW(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfExtCreateFontIndirectW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/) .

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


