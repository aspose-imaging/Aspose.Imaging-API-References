---
title: "EmfSetArcDirection فئة"
type: docs
weight: 1090
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---

**Summary:** The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetArcDirection

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetArcDirection()](#EmfSetArcDirection__1) | ينشئ مثيلًا جديدًا من الفئة [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
| [EmfSetArcDirection(source)](#EmfSetArcDirection_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| arc_direction | [EmfArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfarcdirection/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد اتجاه القوس. يجب أن تكون القيمة<br/>            ضمن تعداد ArcDirection (القسم 2.1.2).<br/>            الاتجاه الافتراضي هو عكس اتجاه عقارب الساعة. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetArcDirection() {#EmfSetArcDirection__1}


```
 EmfSetArcDirection() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

### Constructor: EmfSetArcDirection(source) {#EmfSetArcDirection_source_2}


```
 EmfSetArcDirection(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/).

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


