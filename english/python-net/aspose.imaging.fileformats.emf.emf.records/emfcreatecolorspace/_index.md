---
title: EmfCreateColorSpace Class
type: docs
weight: 270
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---

**Summary:** The EMR_CREATECOLORSPACE record creates a logical color space object from a color profile with a<br/>            name consisting of ASCII characters.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateColorSpace

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreateColorSpace(source)](#EmfCreateColorSpace_source_1) | Initializes a new instance of the [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_cs | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the index of the logical color space<br/>            object in the EMF object table (section 3.1.1.1). This index MUST be saved so that this object<br/>            can be reused or modified. |
| lcs | [WmfLogColorSpace](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) | r/w | Gets or sets a WMF LogColorSpace object ([MS-WMF] section 2.2.2.11), which can specify<br/>            the name of a color profile in ASCII characters. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfCreateColorSpace(source) {#EmfCreateColorSpace_source_1}


```
 EmfCreateColorSpace(source) 
```

Initializes a new instance of the [EmfCreateColorSpace](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/) class.

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


