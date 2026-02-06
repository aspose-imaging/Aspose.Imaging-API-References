---
title: Class EmfPlusSetTsGraphics
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTsGraphics class. The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server
type: docs
weight: 6530
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/
---
## EmfPlusSetTsGraphics class

The EmfPlusSetTSGraphics record specifies the state of a graphics device context for a terminal server.

```csharp
public sealed class EmfPlusSetTsGraphics : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetTsGraphics](emfplussettsgraphics/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetTsGraphics` class. |

## Properties

| Name | Description |
| --- | --- |
| [AntiAliasMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/antialiasmode/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the quality of line rendering, including the type of line anti-aliasing. It MUST be defined in the SmoothingMode enumeration (section 2.1.1.28). |
| [BasicVgaColors](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/basicvgacolors/) { get; } | Gets a value indicating whether [basic vga colors]. If set, the palette contains only the basic VGA colors. |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingmode/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies how source colors are combined with background colors. It MUST be a value in the CompositingMode enumeration (section 2.1.1.5). |
| [CompositingQuality](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/compositingquality/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the degree of smoothing to apply to lines, curves and the edges of filled areas to make them appear more continuous or sharply defined. It MUST be a value in the CompositingQuality enumeration (section 2.1.1.6). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| [FilterType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/filtertype/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies how scaling, including stretching and shrinking, is performed. It MUST be a value in the FilterType enumeration (section 2.1.1.11). |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [HavePalette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/havepalette/) { get; } | Gets a value indicating whether [have palette]. If set, this record contains an EmfPlusPalette object (section 2.2.2.28) in the Palette field following the graphics state data. |
| [Palette](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/palette/) { get; set; } | Gets or sets an optional EmfPlusPalette object. |
| [PixelOffset](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/pixeloffset/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the overall quality of the image and text-rendering process. It MUST be a value in the PixelOffsetMode enumeration (section 2.1.1.26). |
| [RenderOriginX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginx/) { get; set; } | Gets or sets a 16-bit signed integer, which is the horizontal coordinate of the origin for rendering halftoning and dithering matrixes. |
| [RenderOriginY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/renderoriginy/) { get; set; } | Gets or sets a 16-bit signed integer, which is the vertical coordinate of the origin for rendering halftoning and dithering matrixes. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textcontrast/) { get; set; } | Gets or sets a 16-bit unsigned integer that specifies the gamma correction value used for rendering anti-aliased and ClearType text. This value MUST be in the range 0 to 12, inclusive. |
| [TextRenderHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/textrenderhint/) { get; set; } | Gets or sets an 8-bit unsigned integer that specifies the quality of text rendering, including the type of text anti-aliasing. It MUST be defined in the TextRenderingHint enumeration (section 2.1.1.32). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |
| [WorldToDevice](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettsgraphics/worldtodevice/) { get; set; } | Gets or sets an 192-bit EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the world space to device space transforms. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


