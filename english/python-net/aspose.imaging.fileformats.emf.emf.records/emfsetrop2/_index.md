---
title: EmfSetRop2 Class
type: docs
weight: 1250
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---

The EMR_SETROP2 record defines a binary raster operation mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetRop2

**Inheritance:** EmfStateRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetRop2 type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetRop2(source)](#EmfSetRop2_source_0) | Initializes a new instance of the [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) class. |
| [EmfSetRop2()](#EmfSetRop2__1) | Initializes a new instance of the [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| rop_2_mode | [WmfBinaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the raster operation mode and<br/>            MUST be in the WMF Binary Raster Op enumeration ([MS-WMF] section 2.1.1.2). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_3) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetRop2(source) {#EmfSetRop2_source_0}


```
 EmfSetRop2(source) 
```

Initializes a new instance of the [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfSetRop2() {#EmfSetRop2__1}


```
 EmfSetRop2() 
```

Initializes a new instance of the [EmfSetRop2](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetrop2/) class.

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


