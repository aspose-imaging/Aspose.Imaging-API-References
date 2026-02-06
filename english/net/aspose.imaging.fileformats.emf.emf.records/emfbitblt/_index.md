---
title: Class EmfBitBlt
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBitBlt class. The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle optionally in combination with a brush pattern according to a specified raster operation
type: docs
weight: 3340
url: /net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---
## EmfBitBlt class

The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

```csharp
public sealed class EmfBitBlt : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfBitBlt](emfbitblt/)(EmfRecord) | Initializes a new instance of the `EmfBitBlt` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bitbltrasteroperation/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the raster operation code. This code defines how the color data of the source rectangle is to be combined with the color data of the destination rectangle and optionally a brush pattern, to achieve the final color. |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bksrcargb32color/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cxdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the source and destination rectangles. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/cydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the source and destination rectangles. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR_BITBLT record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xformsrc/) { get; set; } | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfbitblt/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


