---
title: EmfSetTextAlign Class
type: docs
weight: 1300
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/
---

**Summary:** The EMR_SETTEXTALIGN record specifies text alignment.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetTextAlign

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetTextAlign()](#EmfSetTextAlign__1) | Initializes a new instance of the [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) class. |
| [EmfSetTextAlign(source)](#EmfSetTextAlign_source_2) | Initializes a new instance of the [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| size | int | r/w | Gets or sets the size of the record |
| text_alignment_mode | int | r/w | Gets or sets a 32-bit unsigned integer that specifies text alignment by<br/>            using a mask of text alignment flags. These are either [WmfTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/)<br/>            ([MS-WMF] section 2.1.2.3) for text with a horizontal baseline, or [WmfVerticalTextAlignmentModeFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfverticaltextalignmentmodeflags/)<br/>            ([MS-WMF] section 2.1.2.4) for text with a vertical<br/>            baseline. Only one value can be chosen from those that affect horizontal and vertical<br/>            alignment. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetTextAlign() {#EmfSetTextAlign__1}


```
 EmfSetTextAlign() 
```

Initializes a new instance of the [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) class.

### Constructor: EmfSetTextAlign(source) {#EmfSetTextAlign_source_2}


```
 EmfSetTextAlign(source) 
```

Initializes a new instance of the [EmfSetTextAlign](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsettextalign/) class.

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


