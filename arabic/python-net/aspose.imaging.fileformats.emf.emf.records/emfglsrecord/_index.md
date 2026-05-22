---
title: "فئة EmfGlsRecord"
type: docs
weight: 550
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---

**Summary:** The EMR_GLSRECORD record specifies an OpenGL function.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsRecord

**Inheritance:** EmfOpenGlRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfGlsRecord(source)](#EmfGlsRecord_source_1) | يُنشئ مثيلًا جديدًا من الفئة [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cb_data | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32‑بت يحدد حجم حقل Data بالبايت.<br/>            إذا كانت هذه القيمة صفرًا، لا يتم إرفاق أي بيانات بهذا السجل. |
| البيانات | System.Byte | r/w | يحصل أو يعيّن مصفوفة اختيارية من البايت بطول cbData تحدد البيانات لوظيفة OpenGL. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfGlsRecord(source) {#EmfGlsRecord_source_1}


```
 EmfGlsRecord(source) 
```

يُنشئ مثيلًا جديدًا من الفئة [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/).

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


