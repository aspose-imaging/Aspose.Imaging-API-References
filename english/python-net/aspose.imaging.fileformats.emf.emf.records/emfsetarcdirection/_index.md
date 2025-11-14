---
title: EmfSetArcDirection Class
type: docs
weight: 1090
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---

**Summary:** The EMR_SETARCDIRECTION record specifies the drawing direction to be used for arc and rectangle output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetArcDirection

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetArcDirection()](#EmfSetArcDirection__1) | Initializes a new instance of the [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/) class. |
| [EmfSetArcDirection(source)](#EmfSetArcDirection_source_2) | Initializes a new instance of the [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| arc_direction | [EmfArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfarcdirection/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the arc direction. The value<br/>            MUST be in the ArcDirection enumeration (section 2.1.2).<br/>            The default direction is counterclockwise. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetArcDirection() {#EmfSetArcDirection__1}


```
 EmfSetArcDirection() 
```

Initializes a new instance of the [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/) class.

### Constructor: EmfSetArcDirection(source) {#EmfSetArcDirection_source_2}


```
 EmfSetArcDirection(source) 
```

Initializes a new instance of the [EmfSetArcDirection](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/) class.

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


