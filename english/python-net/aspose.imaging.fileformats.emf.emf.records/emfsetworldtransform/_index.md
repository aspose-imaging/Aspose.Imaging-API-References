---
title: EmfSetWorldTransform Class
type: docs
weight: 1340
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---

The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWorldTransform

**Inheritance:** EmfTransformRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetWorldTransform type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetWorldTransform(source)](#EmfSetWorldTransform_source_0) | Initializes a new instance of the [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) class. |
| [EmfSetWorldTransform()](#EmfSetWorldTransform__1) | Initializes a new instance of the [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix) | r/w | Gets or sets an XForm object (section 2.2.28), which defines a world-space to page space transform. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetWorldTransform(source) {#EmfSetWorldTransform_source_0}


```
 EmfSetWorldTransform(source) 
```

Initializes a new instance of the [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetWorldTransform() {#EmfSetWorldTransform__1}


```
 EmfSetWorldTransform() 
```

Initializes a new instance of the [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) class.

### create_from_record(source)  [static] {#create_from_record_source_2}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


### create_from_type(type)  [static] {#create_from_type_type_3}


```
 create_from_type(type) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | The record type. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


