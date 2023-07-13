---
title: EmfSetPaletteEntries Class
type: docs
weight: 1220
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---

The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing<br/>            LogPalette (section 2.2.17) object.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetPaletteEntries

**Inheritance:** EmfObjectManipulationRecordType

**Aspose.Imaging Version:** 23.6

The EmfSetPaletteEntries type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSetPaletteEntries(source)](#EmfSetPaletteEntries_source_0) | Initializes a new instance of the [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| ih_pal | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the palette EMF Object Table index. |
| start | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to set. |
| numberof_entries | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the number of entries. |
| argb_32_pal_entries | int | r/w | Gets or sets an array of LogPaletteEntry (section 2.2.18) objects, of<br/>            NumberOfEntries length, which specifies the palette entry data. The Values members do<br/>            not contain any values. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSetPaletteEntries(source) {#EmfSetPaletteEntries_source_0}


```
 EmfSetPaletteEntries(source) 
```

Initializes a new instance of the [EmfSetPaletteEntries](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### create_from_record(source)  [static] {#create_from_record_source_1}


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


### create_from_type(type)  [static] {#create_from_type_type_2}


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


