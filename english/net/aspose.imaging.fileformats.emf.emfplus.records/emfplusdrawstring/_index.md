---
title: Class EmfPlusDrawString
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawString class. The EmfPlusDrawString record specifies text output with string formatting
type: docs
weight: 6140
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
## EmfPlusDrawString class

The EmfPlusDrawString record specifies text output with string formatting

```csharp
public sealed class EmfPlusDrawString : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawString](emfplusdrawstring/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawString` class. |

## Properties

| Name | Description |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/brushid/) { get; set; } | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. This definition is used to paint the foreground text color; that is, just the glyphs themselves. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [FormatId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/formatid/) { get; set; } | Gets or sets the format identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. This object specifies text layout information and display manipulations to be applied to a string |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/iscolor/) { get; set; } | Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. |
| [LayoutRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/layoutrect/) { get; set; } | Gets or sets the layout rect An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area of the destination that will receive the string |
| [Length](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/length/) { get; set; } | Gets or sets the length 32-bit unsigned integer that specifies the number of characters in the string. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusFont object (section 2.2.1.3) in the EMF+ Object Table to render the text. The value MUST be zero to 63, inclusive. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [StringData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/stringdata/) { get; set; } | Gets or sets the string data An array of 16-bit Unicode characters that specifies the string to be drawn |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


