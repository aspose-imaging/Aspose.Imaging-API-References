---
title: "فئة EmfSetWorldTransform"
type: docs
weight: 1370
url: /ar/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---

**Summary:** The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [EmfSetWorldTransform()](#EmfSetWorldTransform__1) | يُهيئ مثيلًا جديدًا من الفئة [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) |
| [EmfSetWorldTransform(source)](#EmfSetWorldTransform_source_2) | يُهيئ مثيلًا جديدًا من الفئة [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الحجم | int | r/w | يحصل أو يعيّن حجم السجل |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | يحصل أو يحدد النوع. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | يحصل أو يعيّن كائن XForm (القسم 2.2.28)، الذي يحدد تحويل من الفضاء العالمي إلى فضاء الصفحة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | ينشئ مثيلًا جديدًا من الفئة [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetWorldTransform() {#EmfSetWorldTransform__1}


```
 EmfSetWorldTransform() 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/)

### Constructor: EmfSetWorldTransform(source) {#EmfSetWorldTransform_source_2}


```
 EmfSetWorldTransform(source) 
```

يُهيئ مثيلًا جديدًا من الفئة [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/)

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


