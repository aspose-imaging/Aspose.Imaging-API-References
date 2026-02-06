---
title: Class EmfStretchBlt
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfStretchBlt class. The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle optionally in combination with a brush pattern according to a specified raster operation stretching or compressing the output to fit the dimensions of the destination if necessary
type: docs
weight: 4710
url: /net/aspose.imaging.fileformats.emf.emf.records/emfstretchblt/
---
## EmfStretchBlt class

The EMR_STRETCHBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

```csharp
public sealed class EmfStretchBlt : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfStretchBlt](emfstretchblt/#constructor)() | Initializes a new instance of the `EmfStretchBlt` class. |
| [EmfStretchBlt](emfstretchblt/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfStretchBlt` class. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/argb32bkcolorsrc/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap. |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bitbltrasteroperation/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the raster operation code. This code defines how the color data of the source rectangle is to be combined with the color data of the destination rectangle and optionally a brush pattern, to achieve the final color |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cxsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/cysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle. |
| [DestRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/destrect/) { get; set; } | Gets or sets the dest rect. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR_STRETCHBLT record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/srcrect/) { get; set; } | Gets or sets the source rect. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xformsrc/) { get; set; } | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchblt/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


