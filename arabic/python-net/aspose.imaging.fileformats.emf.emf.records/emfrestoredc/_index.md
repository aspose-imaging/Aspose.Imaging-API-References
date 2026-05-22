---
title: "فئة EmfRestoreDc"
type: docs
weight: 1000
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---

**Summary:** The EMR_RESTOREDC record restores the playback device context to the specified state. The<br/>            playback device context is restored by popping state information off a stack that was created by<br/>            prior EMR_SAVEDC records (section 2.3.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfRestoreDc

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfRestoreDc()](#EmfRestoreDc__1) | ينشئ مثيلًا جديدًا من الفئة [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) . |
| [EmfRestoreDc(source)](#EmfRestoreDc_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| saved_dc | int | r/w | يحصل أو يعيّن عددًا صحيحًا موقعًا 32 بت يحدد الحالة المحفوظة لاستعادتها بالنسبة إلى<br/>            الحالة الحالية. يجب أن تكون هذه القيمة سالبة؛ –1 تمثل الحالة التي تم حفظها مؤخرًا على المكدس، –2 الحالة التي قبلها، إلخ. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfRestoreDc() {#EmfRestoreDc__1}


```
 EmfRestoreDc() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) .

### Constructor: EmfRestoreDc(source) {#EmfRestoreDc_source_2}


```
 EmfRestoreDc(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfRestoreDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrestoredc/) .

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


