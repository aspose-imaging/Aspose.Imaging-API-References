---
title: Class EmfPlgBlt
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPlgBlt class. The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination parallelogram with the application of a color mask bitmap
type: docs
weight: 4050
url: /net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---
## EmfPlgBlt class

The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap.

```csharp
public sealed class EmfPlgBlt : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlgBlt](emfplgblt/)(EmfRecord) | Initializes a new instance of the `EmfPlgBlt` class. |

## Properties

| Name | Description |
| --- | --- |
| [AptlDest](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/aptldest/) { get; set; } | Gets or sets an array of three WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies three corners a parallelogram destination area for the block transfer. The upper-left corner of the source rectangle is mapped to the first point in this array, the upper-right corner to the second point, and the lower-left corner to the third point. The lower-right corner of the source rectangle is mapped to the implicit fourth point in the parallelogram, which is computed from the first three points (A, B, and C) by treating them as vectors. D = B + C A |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bksrcargb32color/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the background color of the source bitmap. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the bounding rectangle, in device units, for output to the destination. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cxsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/cysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle. |
| [MaskBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/maskbitmap/) { get; set; } | Gets or sets a buffer containing the mask bitmap, which are not required to be contiguous with the fixed portion of the EMR_PLGBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which are not required to be contiguous with the fixed portion of the EMR_PLGBLT record or with each other. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagemask/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the mask bitmap header. This value MUST be in the DIBColors enumeration. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration |
| [XFormSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xformsrc/) { get; set; } | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [XMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xmask/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the mask bitmap. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [YMask](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ymask/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the mask bitmap. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfplgblt/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


