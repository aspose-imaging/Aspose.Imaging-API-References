---
title: "الفئة EmfModifyWorldTransform"
type: docs
weight: 640
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---

**Summary:** The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space<br/>            transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfModifyWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform__1) | ينشئ مثيلًا جديدًا من الفئة [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/). |
| [EmfModifyWorldTransform(source)](#EmfModifyWorldTransform_source_2) | ينشئ مثيلًا جديدًا من الفئة [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| modify_world_transform_mode | [EmfModifyWorldTransformMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/) | r/w | يحصل أو يعيّن عددًا صحيحًا غير موقعًا 32-بت يحدد كيفية<br/>            استخدام التحويل المحدد في Xform. يجب أن تكون هذه القيمة ضمن تعداد ModifyWorldTransformMode (القسم 2.1.24). |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن XForm (القسم 2.2.28)، الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfModifyWorldTransform() {#EmfModifyWorldTransform__1}


```
 EmfModifyWorldTransform() 
```

ينشئ مثيلًا جديدًا من الفئة [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/).

### Constructor: EmfModifyWorldTransform(source) {#EmfModifyWorldTransform_source_2}


```
 EmfModifyWorldTransform(source) 
```

ينشئ مثيلًا جديدًا من الفئة [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/).

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


