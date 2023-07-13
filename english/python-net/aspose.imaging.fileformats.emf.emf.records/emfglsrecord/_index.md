---
title: EmfGlsRecord Class
type: docs
weight: 540
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---

The EMR_GLSRECORD record specifies an OpenGL function.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGlsRecord

**Inheritance:** EmfOpenGlRecordType

**Aspose.Imaging Version:** 23.6

The EmfGlsRecord type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfGlsRecord(source)](#EmfGlsRecord_source_0) | Initializes a new instance of the [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| cb_data | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size, in bytes, of the Data field.<br/>            If this value is zero, no data is attached to this record. |
| data | byte | r/w | Gets or sets an optional array of bytes of cbData length that specifies data for the OpenGL function. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfGlsRecord(source) {#EmfGlsRecord_source_0}


```
 EmfGlsRecord(source) 
```

Initializes a new instance of the [EmfGlsRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfglsrecord/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### create_from_record(source)  [static] {#create_from_record_source_1}


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


### create_from_type(type)  [static] {#create_from_type_type_2}


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


