---
title: Class EmfMaskBlt
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMaskBlt class. The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle optionally in combination with a brush pattern and with the application of a color mask bitmap according to specified foreground and background raster operations
type: docs
weight: 3900
url: /net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---
## EmfMaskBlt class

The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations.

```csharp
public sealed class EmfMaskBlt : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfMaskBlt](emfmaskblt/)(EmfRecord) | Initializes a new instance of the `EmfMaskBlt` class. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32BkColorSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/argb32bkcolorsrc/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cxdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/cydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/maskbitmap/) { get; set; } | Gets or sets a buffer containing the mask bitmaps, which are not required to be contiguous with the fixed portion of the EMR_MASKBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Rop4](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/rop4/) { get; set; } | Gets or sets a quaternary raster operation, which specifies ternary raster operations for the foreground and background colors of a bitmap. These values define how the color data of the source rectangle is to be combined with the color data of the destination rectangle. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmaps, which are not required to be contiguous with the fixed portion of the EMR_MASKBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagemask/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the mask bitmap header. This value MUST be in the DIBColors enumeration. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xformsrc/) { get; set; } | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xmask/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ymask/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfmaskblt/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


