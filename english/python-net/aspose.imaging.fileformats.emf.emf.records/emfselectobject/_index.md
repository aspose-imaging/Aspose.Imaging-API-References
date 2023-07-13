---
title: EmfSelectObject Class
type: docs
weight: 1040
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---

The EMR_SELECTOBJECT record adds a graphics object to the current metafile playback device<br/>            context. The object is specified either by its index in the EMF Object Table(section 3.1.1.1) or by its<br/>            value from the StockObject enumeration(section 2.1.31).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectObject

**Inheritance:** EmfRecord

**Aspose.Imaging Version:** 23.6

The EmfSelectObject type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSelectObject(record)](#EmfSelectObject_record_0) | Initializes a new instance of the [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) class. |
| [EmfSelectObject()](#EmfSelectObject__1) | Initializes a new instance of the [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| object_handle | int | r/w | Gets or sets 32-bit unsigned integer that specifies either the index of a graphics object <br/>            in the EMF Object Table or the index of a stock object from the [EmfStockObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/) enumeration. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSelectObject(record) {#EmfSelectObject_record_0}


```
 EmfSelectObject(record) 
```

Initializes a new instance of the [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The record. |

### EmfSelectObject() {#EmfSelectObject__1}


```
 EmfSelectObject() 
```

Initializes a new instance of the [EmfSelectObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectobject/) class.

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


