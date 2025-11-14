---
title: EmfColorCorrectPalette Class
type: docs
weight: 140
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/
---

**Summary:** The EMR_COLORCORRECTPALETTE record specifies how to correct the entries of a logical palette<br/>            object using WCS 1.0 values.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfColorCorrectPalette

**Inheritance:** EmfObjectManipulationRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfColorCorrectPalette(source)](#EmfColorCorrectPalette_source_1) | Initializes a new instance of the [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ih_palette | int | r/w | Gets or sets a 32-bit unsigned integer that specifies index of a logical palette object<br/>            (section 2.2.17) in the EMF Object Table (section 3.1.1.1). |
| n_first_entry | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to correct. |
| n_pal_entries | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of palette entries to correct. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfColorCorrectPalette(source) {#EmfColorCorrectPalette_source_1}


```
 EmfColorCorrectPalette(source) 
```

Initializes a new instance of the [EmfColorCorrectPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcolorcorrectpalette/) class.

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


