---
title: Class EmfTransparentBlt
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfTransparentBlt class. The EMR_TRANSPARENTBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle treating a specified color as transparent stretching or compressing the output to fit the dimensions of the destination if necessary
type: docs
weight: 4760
url: /net/aspose.imaging.fileformats.emf.emf.records/emftransparentblt/
---
## EmfTransparentBlt class

The EMR_TRANSPARENTBLT record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary

```csharp
public sealed class EmfTransparentBlt : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfTransparentBlt](emftransparentblt/)(EmfRecord) | Initializes a new instance of the `EmfTransparentBlt` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cxsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/cysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR_TRANSPARENTBLT record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [SrcBkArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/srcbkargb32color/) { get; set; } | Gets or sets a WMF ColorRef object that specifies the background color of the source bitmap. |
| [TransparentArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/transparentargb32color/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8) that specifies the color in the source bitmap to be treated as transparent. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9) |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XformSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xformsrc/) { get; set; } | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emftransparentblt/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


