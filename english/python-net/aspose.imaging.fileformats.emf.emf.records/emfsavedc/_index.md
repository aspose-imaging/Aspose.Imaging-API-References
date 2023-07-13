---
title: EmfSaveDc Class
type: docs
weight: 1000
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---

Saves the current state of playback device context on a<br/>            stack of states saved by preceding EMR_SAVEDC<br/>            records, if any. The state consists of graphics properties<br/>            and objects, including the currently selected bitmap,<br/>            brush, palette, font, pen, and region. An<br/>            EMR_RESTOREDC record is used to restore the state.<br/>            This EMF record specifies no parameters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSaveDc

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSaveDc type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSaveDc(source)](#EmfSaveDc_source_0) | Initializes a new instance of the [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) class. |
| [EmfSaveDc()](#EmfSaveDc__1) | Initializes a new instance of the [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSaveDc(source) {#EmfSaveDc_source_0}


```
 EmfSaveDc(source) 
```

Initializes a new instance of the [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSaveDc() {#EmfSaveDc__1}


```
 EmfSaveDc() 
```

Initializes a new instance of the [EmfSaveDc](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsavedc/) class.

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


