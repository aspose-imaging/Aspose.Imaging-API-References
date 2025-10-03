---
title: EmfSetBrushOrgEx Class
type: docs
weight: 1120
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/
---

**Summary:** The EMR_SETBRUSHORGEX record specifies the origin of the current brush.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBrushOrgEx

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetBrushOrgEx()](#EmfSetBrushOrgEx__1) | Initializes a new instance of the [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) class. |
| [EmfSetBrushOrgEx(source)](#EmfSetBrushOrgEx_source_2) | Initializes a new instance of the [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which<br/>            specifies the brush's horizontal and vertical origin in device units. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetBrushOrgEx() {#EmfSetBrushOrgEx__1}


```
 EmfSetBrushOrgEx() 
```

Initializes a new instance of the [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) class.

### Constructor: EmfSetBrushOrgEx(source) {#EmfSetBrushOrgEx_source_2}


```
 EmfSetBrushOrgEx(source) 
```

Initializes a new instance of the [EmfSetBrushOrgEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbrushorgex/) class.

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


