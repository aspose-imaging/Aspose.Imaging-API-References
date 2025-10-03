---
title: EmfPlusDrawString Class
type: docs
weight: 190
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

**Summary:** The EmfPlusDrawString record specifies text output with string formatting

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawString(source)](#EmfPlusDrawString_source_1) | Initializes a new instance of the [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies the brush, the content of which <br/>            is determined by the S bit in the Flags field. This definition is used <br/>            to paint the foreground text color; that is, just the glyphs themselves. |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| format_id | int | r/w | Gets or sets the format identifier<br/>            A 32-bit unsigned integer that specifies the index of an optional <br/>            EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. <br/>            This object specifies text layout information and display manipulations <br/>            to be applied to a string |
| is_color | bool | r/w | Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object <br/>            (section 2.2.1.1) in the EMF+ Object Table. |
| layout_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Gets or sets the layout rect<br/>            An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area <br/>            of the destination that will receive the string |
| length | int | r/w | Gets or sets the length<br/>            32-bit unsigned integer that specifies the number of characters in the string. |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The index of an EmfPlusFont object (section 2.2.1.3) in the EMF+<br/>            Object Table to render the text. The value MUST be zero to 63, inclusive. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| string_data | string | r/w | Gets or sets the string data<br/>            An array of 16-bit Unicode characters that specifies the string to be drawn |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawString(source) {#EmfPlusDrawString_source_1}


```
 EmfPlusDrawString(source) 
```

Initializes a new instance of the [EmfPlusDrawString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

