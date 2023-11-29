---
title: EmfDrawEscape Class
type: docs
weight: 340
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---

**Summary:** The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the<br/>            information will result in drawing being done.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfDrawEscape

**Inheritance:** EmfEscapeRecordType

**Aspose.Imaging Version:** 23.11.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDrawEscape(source)](#EmfDrawEscape_source_1) | Initializes a new instance of the [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cj_in | int | r/w | Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| data | byte | r/w | Gets or sets the data to pass to the printer driver. There MUST be cjIn bytes available. |
| escape | [WmfMetafileEscapes](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfmetafileescapes/) | r/w | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to<br/>            execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17). |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfDrawEscape(source) {#EmfDrawEscape_source_1}


```
 EmfDrawEscape(source) 
```

Initializes a new instance of the [EmfDrawEscape](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


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
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) |  |


