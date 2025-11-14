---
title: EmfCreatePalette Class
type: docs
weight: 310
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---

**Summary:** The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreatePalette

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfCreatePalette(source)](#EmfCreatePalette_source_1) | Initializes a new instance of the [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_pal | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object<br/>            in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be<br/>            reused or modified. |
| log_palette | [EmfLogPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpalette/) | r/w | Gets or sets a LogPalette object (section 2.2.17). The Version field of this object<br/>            MUST be set to 0x0300. If the NumberOfEntries value in this object is zero, processing of<br/>            this record MUST fail. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfCreatePalette(source) {#EmfCreatePalette_source_1}


```
 EmfCreatePalette(source) 
```

Initializes a new instance of the [EmfCreatePalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/) class.

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


