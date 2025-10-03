---
title: EmfSetIcmProfileA Class
type: docs
weight: 1170
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---

**Summary:** The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII<br/>            characters, for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetIcmProfileA

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetIcmProfileA(source)](#EmfSetIcmProfileA_source_1) | Initializes a new instance of the [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cb_data | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the size of the color profile data, if it<br/>            is contained in the Data field. |
| cb_name | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the ASCII<br/>            name of the desired color profile. |
| data | System.Byte | r/w | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the ASCII<br/>            name and raw data of the desired color profile. |
| dw_flags | int | r/w | Gets or sets a 32-bit unsigned integer that contains color profile flags. |
| name | string | r | Gets the name |
| raw_data | System.Byte | r | Gets the raw data |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetIcmProfileA(source) {#EmfSetIcmProfileA_source_1}


```
 EmfSetIcmProfileA(source) 
```

Initializes a new instance of the [EmfSetIcmProfileA](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/) class.

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


