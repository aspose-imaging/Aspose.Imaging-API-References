---
title: EmfSetViewportOrgEx Class
type: docs
weight: 1310
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/
---

The EMR_SETVIEWPORTORGEX record defines the viewport origin.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetViewportOrgEx

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetViewportOrgEx type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetViewportOrgEx(source)](#EmfSetViewportOrgEx_source_0) | Initializes a new instance of the [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) class. |
| [EmfSetViewportOrgEx()](#EmfSetViewportOrgEx__1) | Initializes a new instance of the [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | r/w | Gets or sets a 64-bit WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the<br/>            window horizontal and vertical origin in device units. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetViewportOrgEx(source) {#EmfSetViewportOrgEx_source_0}


```
 EmfSetViewportOrgEx(source) 
```

Initializes a new instance of the [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetViewportOrgEx() {#EmfSetViewportOrgEx__1}


```
 EmfSetViewportOrgEx() 
```

Initializes a new instance of the [EmfSetViewportOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetviewportorgex/) class.

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


