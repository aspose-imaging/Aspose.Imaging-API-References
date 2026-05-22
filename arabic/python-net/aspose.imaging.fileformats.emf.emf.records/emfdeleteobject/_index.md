---
title: "فئة EmfDeleteObject"
type: docs
weight: 340
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---

**Summary:** The EMR_DELETEOBJECT record deletes a graphics object, which is specified by its index in the EMF Object Table(section 3.1.1.1).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDeleteObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfDeleteObject()](#EmfDeleteObject__1) | ينشئ مثلاً جديداً من الفئة [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) |
| [EmfDeleteObject(record)](#EmfDeleteObject_record_2) | ينشئ مثلاً جديداً من الفئة [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| object_handle | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد إما فهرس كائن رسومي <br/>            في جدول كائنات EMF أو فهرس كائن مخزون من تعداد StockObject. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfDeleteObject() {#EmfDeleteObject__1}


```
 EmfDeleteObject() 
```

ينشئ مثلاً جديداً من الفئة [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/)

### Constructor: EmfDeleteObject(record) {#EmfDeleteObject_record_2}


```
 EmfDeleteObject(record) 
```

ينشئ مثلاً جديداً من الفئة [EmfDeleteObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | السجل. |

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


