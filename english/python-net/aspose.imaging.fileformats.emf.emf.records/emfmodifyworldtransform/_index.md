---
title: EmfModifyWorldTransform Class
type: docs
weight: 640
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---

**Summary:** The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space<br/>            transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfModifyWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform__1) | Initializes a new instance of the [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) class. |
| [EmfModifyWorldTransform(source)](#EmfModifyWorldTransform_source_2) | Initializes a new instance of the [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| modify_world_transform_mode | [EmfModifyWorldTransformMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/) | r/w | Gets or sets a 32-bit unsigned integer that specifies how the<br/>            transform specified in Xform is used. This value MUST be in the<br/>            ModifyWorldTransformMode enumeration (section 2.1.24). |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets an XForm object (section 2.2.28), which defines a world-space to page space transform. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfModifyWorldTransform() {#EmfModifyWorldTransform__1}


```
 EmfModifyWorldTransform() 
```

Initializes a new instance of the [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) class.

### Constructor: EmfModifyWorldTransform(source) {#EmfModifyWorldTransform_source_2}


```
 EmfModifyWorldTransform(source) 
```

Initializes a new instance of the [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The source. |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


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
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


