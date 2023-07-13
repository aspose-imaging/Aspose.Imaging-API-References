---
title: EmfResizePalette Class
type: docs
weight: 960
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---

The EMR_RESIZEPALETTE record increases or decreases the size of an existing LogPalette object (section 2.2.17).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfResizePalette

**Inheritance:** EmfObjectManipulationRecordType

**Aspose.Imaging Version:** 23.6

The EmfResizePalette type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfResizePalette(source)](#EmfResizePalette_source_0) | Initializes a new instance of the [EmfResizePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfresizepalette/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| ih_pal | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the index of the palette object in the<br/>            EMF Object Table (section 3.1.1.1). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfResizePalette(source) {#EmfResizePalette_source_0}


```
 EmfResizePalette(source) 
```

Initializes a new instance of the [EmfResizePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfresizepalette/) class.

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


