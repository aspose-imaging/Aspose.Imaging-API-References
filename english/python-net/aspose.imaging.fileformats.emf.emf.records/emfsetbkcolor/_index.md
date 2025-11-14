---
title: EmfSetBkColor Class
type: docs
weight: 1100
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/
---

**Summary:** The EMR_SETBKCOLOR record specifies the background color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetBkColor

**Inheritance:** EmfStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetBkColor()](#EmfSetBkColor__1) | Initializes a new instance of the [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/) class. |
| [EmfSetBkColor(source)](#EmfSetBkColor_source_2) | Initializes a new instance of the [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color | int | r/w | Gets or sets a 32-bit WMF ColorRef object, specified in [MS-WMF] section 2.2.2.8, which<br/>            specifies the background color value. |
| size | int | r/w | Gets or sets the size of the record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |


### Constructor: EmfSetBkColor() {#EmfSetBkColor__1}


```
 EmfSetBkColor() 
```

Initializes a new instance of the [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/) class.

### Constructor: EmfSetBkColor(source) {#EmfSetBkColor_source_2}


```
 EmfSetBkColor(source) 
```

Initializes a new instance of the [EmfSetBkColor](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetbkcolor/) class.

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


