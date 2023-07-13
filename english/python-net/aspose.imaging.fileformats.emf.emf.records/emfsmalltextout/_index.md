---
title: EmfSmallTextOut Class
type: docs
weight: 1350
url: /python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

**Aspose.Imaging Version:** 23.6

The EmfSmallTextOut type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_0) | Initializes a new instance of the [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Gets or sets the type. |
| size | int | r/w | Gets or sets the size of the record |
| x | int | r/w | Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string. |
| y | int | r/w | Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string. |
| c_chars | int | r/w | Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the<br/>            string. The string is NOT null-terminated. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Gets or sets a 32-bit unsigned integer specifying the text output options to use. These<br/>            options are specified by one or a combination of values from the ExtTextOutOptions<br/>            enumeration (section 2.1.11). |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the<br/>            GraphicsMode enumeration (section 2.1.16). |
| ex_scale | float | r/w | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction. |
| ey_scale | float | r/w | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that<br/>            specifies the bounding rectangle in device units. |
| text_string | string | r/w | Gets or sets a variable-length string that contains the text string to draw, in either<br/>            8-bit or 16-bit character codes, according to the value of the fuOptions field. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |
| [create_from_type(type)](#create_from_type_type_2) | Initializes a new instance of the [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) class. |

### EmfSmallTextOut(source) {#EmfSmallTextOut_source_0}


```
 EmfSmallTextOut(source) 
```

Initializes a new instance of the [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/) class.

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


