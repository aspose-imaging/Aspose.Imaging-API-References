---
title: EmfPlusDrawDriverString Class
type: docs
weight: 110
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

The EmfPlusDrawDriverString record specifies text output with character positions.

**Namespace:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Class Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Assembly:**  Aspose.Imaging Version: 23.5.6

The EmfPlusDrawDriverString type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|EmfPlusDrawDriverString(source)|Initializes a new instance of the EmfPlusDrawDriverString class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|type|  |
|flags|  |
|size|  |
|data_size|  |
|object_id|Gets or sets the object identifier.<br/>            The EMF+ Object Table index of an|
|brush_id|Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush,<br/>            depending on the value of the S flag in the Flags|
|driver_string_options_flags|Gets or sets the driver string options flags<br/>            A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string.|
|glyph_count|Gets or sets the glyph count<br/>            A 32-bit unsigned integer that specifies number of glyphs in the string|
|glyph_pos|Gets or sets the glyph positions array<br/>            An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph.<br/>            There MUST be GlyphCount elements, which have a one-to-one correspondence with the elements in the Glyphs array.<br/>            Glyph positions are calculated from the position of the first glyph if the DriverStringOptionsRealizedAdvance<br/>            flag in DriverStringOptions flags is set. In this case, GlyphPos specifies the position of the first glyph only.|
|glyphs|Gets or sets the glyphs array<br/>            An array of 16-bit values that define the text string to draw.<br/>            If the DriverStringOptionsCmapLookup flag in the DriverStringOptionsFlags field is set, each value in this<br/>            array specifies a Unicode character. Otherwise, each value specifies an index to a<br/>            character glyph in the EmfPlusFont object specified by the ObjectId value in Flags field.|
|is_color|Gets or sets a value indicating whether this instance is color.<br/>            This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies the color value in an EmfPlusARGB object<br/>            (section 2.2.2.1). If clear, BrushId contains the EMF+ Object<br/>            Table index of an EmfPlusBrush object (section 2.2.1.1).|
|matrix_present|Gets or sets if the matrix present flag<br/>            A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field<br/>            0 - no matrix present. 1 - transform matrix is in TransformMatrix field|
|transform_matrix|Gets or sets the transform matrix<br/>            An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to<br/>            each value in the text array. The presence of this data is determined from the MatrixPresent field.|
