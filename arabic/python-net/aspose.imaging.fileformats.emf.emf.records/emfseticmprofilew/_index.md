---
title: "EmfSetIcmProfileW فئة"
type: docs
weight: 1180
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---

**Summary:** The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of<br/>            Unicode characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileW

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetIcmProfileW(source)](#EmfSetIcmProfileW_source_1) | يُنشئ مثيلًا جديدًا من [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) فئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cb_data | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد حجم بيانات ملف تعريف اللون، إذا كان مرفقًا. |
| cb_name | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد عدد البايتات في اسم Unicode<br/>            UTF16-LE للملف التعريفي للون المطلوب. |
| البيانات | System.Byte | r/w | يحصل أو يعيّن مصفوفة بحجم (cbName + cbData) بايت، والتي تحدد اسم UTF16-LE<br/>            والبيانات الخام للملف اللوني المطلوب. |
| dw_flags | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32-بت يحتوي على أعلام ملف تعريف اللون. |
| الاسم | string | r | يحصل على الاسم |
| raw_data | System.Byte | r | يحصل على البيانات الخام |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetIcmProfileW(source) {#EmfSetIcmProfileW_source_1}


```
 EmfSetIcmProfileW(source) 
```

يُنشئ مثيلًا جديدًا من [EmfSetIcmProfileW](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/) فئة.

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


