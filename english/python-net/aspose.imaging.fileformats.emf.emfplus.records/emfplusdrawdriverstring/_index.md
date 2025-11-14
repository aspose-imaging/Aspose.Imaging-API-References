---
title: EmfPlusDrawDriverString Class
type: docs
weight: 110
url: /python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---

**Summary:** The EmfPlusDrawDriverString record specifies text output with character positions.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawDriverString

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawDriverString(source)](#EmfPlusDrawDriverString_source_1) | Initializes a new instance of the [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Gets or sets the brush identifier<br/>            A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush,<br/>            depending on the value of the S flag in the Flags |
| data_size | int | r/w | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of<br/>            bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| driver_string_options_flags | [EmfPlusDriverStringOptionsFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/) | r/w | Gets or sets the driver string options flags<br/>            A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string. |
| flags | int | r/w | Gets or sets a 16-bit unsigned integer that contains information for some records on how<br/>            the operation is to be performed and on the structure of the record. |
| glyph_count | int | r/w | Gets or sets the glyph count<br/>            A 32-bit unsigned integer that specifies number of glyphs in the string |
| glyph_pos | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Gets or sets the glyph positions array<br/>            An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph.<br/>            There MUST be GlyphCount elements, which have a one-to-one correspondence with the elements in the Glyphs array.<br/>            Glyph positions are calculated from the position of the first glyph if the DriverStringOptionsRealizedAdvance<br/>            flag in DriverStringOptions flags is set. In this case, GlyphPos specifies the position of the first glyph only. |
| glyphs | int[] | r/w | Gets or sets the glyphs array<br/>            An array of 16-bit values that define the text string to draw.<br/>            If the DriverStringOptionsCmapLookup flag in the DriverStringOptionsFlags field is set, each value in this<br/>            array specifies a Unicode character. Otherwise, each value specifies an index to a<br/>            character glyph in the EmfPlusFont object specified by the ObjectId value in Flags field. |
| is_color | bool | r/w | Gets or sets a value indicating whether this instance is color.<br/>            This bit indicates the type of data in the BrushId field.<br/>            If set, BrushId specifies the color value in an EmfPlusARGB object<br/>            (section 2.2.2.1). If clear, BrushId contains the EMF+ Object<br/>            Table index of an EmfPlusBrush object (section 2.2.1.1). |
| matrix_present | int | r/w | Gets or sets if the matrix present flag<br/>            A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field<br/>            0 - no matrix present. 1 - transform matrix is in TransformMatrix field |
| object_id | System.Byte | r/w | Gets or sets the object identifier.<br/>            The EMF+ Object Table index of an ***EmfPlusFont*** object (section<br/>            2.2.1.3) to render the text. The value MUST be zero to 63, inclusive. |
| size | int | r/w | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes<br/>            in the entire record, including the 12-byte record header and record-specific data. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Gets or sets the transform matrix<br/>            An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to<br/>            each value in the text array. The presence of this data is determined from the MatrixPresent field. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Gets a 16-bit unsigned integer that identifies the record type. |


### Constructor: EmfPlusDrawDriverString(source) {#EmfPlusDrawDriverString_source_1}


```
 EmfPlusDrawDriverString(source) 
```

Initializes a new instance of the [EmfPlusDrawDriverString](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | The source. |

