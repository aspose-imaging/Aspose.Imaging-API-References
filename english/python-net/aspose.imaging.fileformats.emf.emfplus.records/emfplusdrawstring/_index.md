---
title: EmfPlusDrawString Class
type: docs
weight: 190
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---

The EmfPlusDrawString record specifies text output with string formatting

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawString

**Assembly:**  Aspose.Imaging Version: 23.6.0

The EmfPlusDrawString type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawString(source)|Initializes a new instance of the EmfPlusDrawString class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1).<br/>            If clear, BrushId contains the index of an EmfPlusBrush object <br/>            (section 2.2.1.1) in the EMF+ Object Table.|
|object_id|Gets or sets the object identifier.<br/>            The index of an EmfPlusFont object (section 2.2.1.3) in the EMF+<br/>            Object Table to render the text. The value MUST be zero to 63, inclusive.|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies the brush, the content of which <br/>            is determined by the S bit in the Flags field. This definition is used <br/>            to paint the foreground text color; that is, just the glyphs themselves.|
|format_id|Gets or sets the format identifier<br/>            A 32-bit unsigned integer that specifies the index of an optional <br/>            EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. <br/>            This object specifies text layout information and display manipulations <br/>            to be applied to a string|
|length|Gets or sets the length<br/>            32-bit unsigned integer that specifies the number of characters in the string.|
|layout_rect|Gets or sets the layout rect<br/>            An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area <br/>            of the destination that will receive the string|
|string_data|Gets or sets the string data<br/>            An array of 16-bit Unicode characters that specifies the string to be drawn|
