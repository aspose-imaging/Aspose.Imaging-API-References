---
title: "EmfCreateBrushIndirect فئة"
type: docs
weight: 260
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---

**Summary:** The EMR_CREATEBRUSHINDIRECT record defines a logical brush for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateBrushIndirect

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect__1) | يُنشئ مثيلًا جديدًا من [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) فئة. |
| [EmfCreateBrushIndirect(source)](#EmfCreateBrushIndirect_source_2) | يُنشئ مثيلًا جديدًا من [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) فئة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| ih_brush | int | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقع 32-بت يحدد فهرس كائن الفرشاة المنطقية<br/>            في جدول كائنات EMF (القسم 3.1.1.1). يجب حفظ هذا الفهرس حتى يمكن<br/>            إعادة استخدام هذا الكائن أو تعديله. |
| log_brush | [EmfLogBrushEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/) | r/w | يحصل أو يعيّن كائن LogBrushEx (القسم 2.2.12) الذي يحدد النمط واللون و<br/>            نمط الفرشاة المنطقية. يجب أن يكون حقل BrushStyle في هذا الكائن BS_SOLID،<br/>            BS_HATCHED، أو BS_NULL. |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfCreateBrushIndirect() {#EmfCreateBrushIndirect__1}


```
 EmfCreateBrushIndirect() 
```

يُنشئ مثيلًا جديدًا من [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) فئة.

### Constructor: EmfCreateBrushIndirect(source) {#EmfCreateBrushIndirect_source_2}


```
 EmfCreateBrushIndirect(source) 
```

يُنشئ مثيلًا جديدًا من [EmfCreateBrushIndirect](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/) فئة.

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


