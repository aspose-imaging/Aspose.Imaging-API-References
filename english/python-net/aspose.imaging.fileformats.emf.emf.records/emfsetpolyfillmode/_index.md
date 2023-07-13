---
title: EmfSetPolyFillMode Class
type: docs
weight: 1240
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/
---

The EMR_SETPOLYFILLMODE record defines polygon fill mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPolyFillMode

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetPolyFillMode type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetPolyFillMode(source)](#EmfSetPolyFillMode_source_0) | Initializes a new instance of the [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) class. |
| [EmfSetPolyFillMode()](#EmfSetPolyFillMode__1) | Initializes a new instance of the [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| polygon_fill_mode | [EmfPolygonFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfpolygonfillmode/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the polygon fill mode and<br/>            MUST be in the PolygonFillMode (section 2.1.27) enumeration. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetPolyFillMode(source) {#EmfSetPolyFillMode_source_0}


```
 EmfSetPolyFillMode(source) 
```

Initializes a new instance of the [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetPolyFillMode() {#EmfSetPolyFillMode__1}


```
 EmfSetPolyFillMode() 
```

Initializes a new instance of the [EmfSetPolyFillMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpolyfillmode/) class.

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


