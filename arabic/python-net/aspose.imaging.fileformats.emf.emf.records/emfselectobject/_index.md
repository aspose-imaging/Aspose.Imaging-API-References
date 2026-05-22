---
title: "فئة EmfSelectObject"
type: docs
weight: 1070
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---

**Summary:** The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device<br/>            context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its<br/>            value from the StockObject enumeration(section 2.1.31).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectObject

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSelectObject()](#EmfSelectObject__1) | يُنشئ مثيلاً جديدًا من الفئة [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/). |
| [EmfSelectObject(record)](#EmfSelectObject_record_2) | يُنشئ مثيلاً جديدًا من الفئة [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| object_handle | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يحدد إما فهرس كائن رسومي <br/>            في جدول كائنات EMF أو فهرس كائن مخزون من تعداد [EmfStockObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSelectObject() {#EmfSelectObject__1}


```
 EmfSelectObject() 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/).

### Constructor: EmfSelectObject(record) {#EmfSelectObject_record_2}


```
 EmfSelectObject(record) 
```

يُنشئ مثيلاً جديدًا من الفئة [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/).

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


