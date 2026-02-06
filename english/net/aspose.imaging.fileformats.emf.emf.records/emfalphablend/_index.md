---
title: Class EmfAlphaBlend
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfAlphaBlend class. The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a destination rectangle including alpha transparency data according to a specified blending operation
type: docs
weight: 3290
url: /net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---
## EmfAlphaBlend class

The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation.

```csharp
public sealed class EmfAlphaBlend : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfAlphaBlend](emfalphablend/)(EmfRecord) | Initializes a new instance of the `EmfAlphaBlend` class. |

## Properties

| Name | Description |
| --- | --- |
| [BkSrcArgb32Color](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bksrcargb32color/) { get; set; } | Gets or sets a WMF ColorRef object ([MS-WMF] section 2.2.2.8 that specifies the background color of the source bitmap. |
| [BlendFunction](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/blendfunction/) { get; set; } | Gets or sets a structure that specifies the blending operations for source and destination bitmaps |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. This value MUST be greater than zero. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cxsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the source rectangle. This value MUST be greater than zero. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. This value MUST be greater than zero. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/cysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the source rectangle. This value MUST be greater than zero. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR_ALPHABLEND record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XformSr](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xformsr/) { get; set; } | Gets or sets an XForm object (section 2.2.28) that specifies a world-space to page-space transform to apply to the source bitmap. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfalphablend/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the source rectangle. |

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


