---
title: EmfSetMapMode Class
type: docs
weight: 1210
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/
---

**Summary:** The EMR_SETMAPMODE record specifies the mapping mode of the playback device context. <br/>            The mapping mode specifies the unit of measure used to transform page space units <br/>            into device space units, and also specifies the orientation of the device's x-axis and y-axis.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetMapMode

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetMapMode()](#EmfSetMapMode__1) | Initializes a new instance of the [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) class. |
| [EmfSetMapMode(record)](#EmfSetMapMode_record_2) | Initializes a new instance of the [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| map_mode | [EmfMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/) | r/w | Gets or sets the map mode. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetMapMode() {#EmfSetMapMode__1}


```
 EmfSetMapMode() 
```

Initializes a new instance of the [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) class.

### Constructor: EmfSetMapMode(record) {#EmfSetMapMode_record_2}


```
 EmfSetMapMode(record) 
```

Initializes a new instance of the [EmfSetMapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetmapmode/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | The record. |

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


