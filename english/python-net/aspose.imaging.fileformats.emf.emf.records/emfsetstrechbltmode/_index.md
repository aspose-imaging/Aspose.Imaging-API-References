---
title: EmfSetStrechBltMode Class
type: docs
weight: 1260
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/
---

The EMR_SETSTRETCHBLTMODE record specifies bitmap stretch mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetStrechBltMode

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetStrechBltMode type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetStrechBltMode(source)](#EmfSetStrechBltMode_source_0) | Initializes a new instance of the [EmfSetStrechBltMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| stretch_mode | [EmfStretchMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the stretch mode and MAY be<br/>            in the StretchMode enumeration. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetStrechBltMode(source) {#EmfSetStrechBltMode_source_0}


```
 EmfSetStrechBltMode(source) 
```

Initializes a new instance of the [EmfSetStrechBltMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetstrechbltmode/) class.

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


