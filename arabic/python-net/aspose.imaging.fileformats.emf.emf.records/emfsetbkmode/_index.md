---
title: "فئة EmfSetBkMode"
type: docs
weight: 1110
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---

**Summary:** The EMR_SETBKMODE record specifies the background mix mode of the playback device context.<br/>            The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkMode

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetBkMode()](#EmfSetBkMode__1) | ينشئ مثلاً جديداً من الفئة [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/). |
| [EmfSetBkMode(source)](#EmfSetBkMode_source_2) | ينشئ مثلاً جديداً من الفئة [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_mode | [EmfBackgroundMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfbackgroundmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32‑بت يحدد وضع الخلفية<br/>            ويجب أن يكون ضمن تعداد BackgroundMode (القسم 2.1.4). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetBkMode() {#EmfSetBkMode__1}


```
 EmfSetBkMode() 
```

ينشئ مثلاً جديداً من الفئة [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/).

### Constructor: EmfSetBkMode(source) {#EmfSetBkMode_source_2}


```
 EmfSetBkMode(source) 
```

ينشئ مثلاً جديداً من الفئة [EmfSetBkMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/).

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


