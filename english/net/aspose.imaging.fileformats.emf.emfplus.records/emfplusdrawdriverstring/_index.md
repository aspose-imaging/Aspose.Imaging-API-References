---
title: Class EmfPlusDrawDriverString
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawDriverString class. The EmfPlusDrawDriverString record specifies text output with character positions
type: docs
weight: 6060
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
## EmfPlusDrawDriverString class

The EmfPlusDrawDriverString record specifies text output with character positions.

```csharp
public sealed class EmfPlusDrawDriverString : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawDriverString](emfplusdrawdriverstring/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawDriverString` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush, depending on the value of the S flag in the Flags |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| [DriverStringOptionsFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/driverstringoptionsflags/) { get; set; } | Gets or sets the driver string options flags A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [GlyphCount](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphcount/) { get; set; } | Gets or sets the glyph count A 32-bit unsigned integer that specifies number of glyphs in the string |
| [GlyphPos](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphpos/) { get; set; } | Gets or sets the glyph positions array An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph. There MUST be GlyphCount elements, which have a one-to-one correspondence with the elements in the Glyphs array. Glyph positions are calculated from the position of the first glyph if the DriverStringOptionsRealizedAdvance flag in DriverStringOptions flags is set. In this case, GlyphPos specifies the position of the first glyph only. |
| [Glyphs](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/glyphs/) { get; set; } | Gets or sets the glyphs array An array of 16-bit values that define the text string to draw. If the DriverStringOptionsCmapLookup flag in the DriverStringOptionsFlags field is set, each value in this array specifies a Unicode character. Otherwise, each value specifies an index to a character glyph in the EmfPlusFont object specified by the ObjectId value in Flags field. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. This bit indicates the type of data in the BrushId field. If set, BrushId specifies the color value in an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the EMF+ Object Table index of an EmfPlusBrush object (section 2.2.1.1). |
| [MatrixPresent](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/matrixpresent/) { get; set; } | Gets or sets if the matrix present flag A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field 0 - no matrix present. 1 - transform matrix is in TransformMatrix field |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/objectid/) { get; set; } | Gets or sets the object identifier. The EMF+ Object Table index of an [EmfPlusFont](EmfPlusFont) object (section 2.2.1.3) to render the text. The value MUST be zero to 63, inclusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/transformmatrix/) { get; set; } | Gets or sets the transform matrix An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to each value in the text array. The presence of this data is determined from the MatrixPresent field. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


