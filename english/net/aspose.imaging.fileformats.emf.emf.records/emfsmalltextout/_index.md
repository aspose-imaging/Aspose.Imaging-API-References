---
title: Class EmfSmallTextOut
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSmallTextOut class. The EMR_SMALLTEXTOUT record outputs a string
type: docs
weight: 4690
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---
## EmfSmallTextOut class

The EMR_SMALLTEXTOUT record outputs a string.

```csharp
public sealed class EmfSmallTextOut : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSmallTextOut](emfsmalltextout/)(EmfRecord) | Initializes a new instance of the `EmfSmallTextOut` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/bounds/) { get; set; } | Gets or sets an optional, 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [CChars](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/cchars/) { get; set; } | Gets or sets a 32-bit unsigned integer specifying the number of 16-bit characters in the string. The string is NOT null-terminated. |
| [ExScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/exscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the x-direction. |
| [EyScale](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/eyscale/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies how much to scale the text in the y-direction. |
| [FuOptions](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/fuoptions/) { get; set; } | Gets or sets a 32-bit unsigned integer specifying the text output options to use. These options are specified by one or a combination of values from the ExtTextOutOptions enumeration (section 2.1.11). |
| [IGraphicsMode](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/igraphicsmode/) { get; set; } | Gets or sets a 32-bit unsigned integer specifying the graphics mode, from the GraphicsMode enumeration (section 2.1.16). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [TextString](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/textstring/) { get; set; } | Gets or sets a variable-length string that contains the text string to draw, in either 8-bit or 16-bit character codes, according to the value of the fuOptions field. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [X](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/x/) { get; set; } | Gets or sets a 32-bit signed integer specifying the x-coordinate of where to place the string. |
| [Y](../../aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/y/) { get; set; } | Gets or sets a 32-bit signed integer specifying the y-coordinate of where to place the string. |

## Remarks

If ETO_SMALL_CHARS is set in the fuOptions field, TextString contains 8-bit codes for characters, derived from the low bytes of 16-bit Unicode UTF16-LE character codes, in which the high byte is assumed to be 0. If ETO_NO_RECT is set in the fuOptions field, the Bounds field is not included in the record.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


