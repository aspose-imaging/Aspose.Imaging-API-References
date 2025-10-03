---
title: EmfSetViewportExtEx Class
type: docs
weight: 1330
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/
---

**Summary:** The EMR_SETVIEWPORTEXTEX record defines the viewport extent.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportExtEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetViewportExtEx()](#EmfSetViewportExtEx__1) | Initializes a new instance of the [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) class. |
| [EmfSetViewportExtEx(source)](#EmfSetViewportExtEx_source_2) | Initializes a new instance of the [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| extent | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Gets or sets a 64-bit WMF SizeL object ([MS-WMF] section 2.2.2.22) that specifies the<br/>            horizontal and vertical extents in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetViewportExtEx() {#EmfSetViewportExtEx__1}


```
 EmfSetViewportExtEx() 
```

Initializes a new instance of the [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) class.

### Constructor: EmfSetViewportExtEx(source) {#EmfSetViewportExtEx_source_2}


```
 EmfSetViewportExtEx(source) 
```

Initializes a new instance of the [EmfSetViewportExtEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportextex/) class.

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


