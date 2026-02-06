---
title: Class EmfStretchDiBits
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfStretchDiBits class. The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a destination rectangle optionally in combination with a brush pattern according to a specified raster operation stretching or compressing the output to fit the dimensions of the destination if necessary
type: docs
weight: 4720
url: /net/aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/
---
## EmfStretchDiBits class

The EMR_STRETCHDIBITS record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

```csharp
public sealed class EmfStretchDiBits : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfStretchDiBits](emfstretchdibits/)(EmfRecord) | Initializes a new instance of the `EmfStretchDiBits` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitBltRasterOperation](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bitbltrasteroperation/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies a raster operation code. These codes define how the color data of the source rectangle is to be combined with the color data of the destination rectangle and optionally a brush pattern, to achieve the final color. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CxDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical width of the destination rectangle. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cxsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| [CyDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical height of the destination rectangle. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/cysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR_STRETCHDIBITS record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the upper-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfstretchdibits/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the upper-left corner of the source rectangle. |

## Remarks

This record supports source images in JPEG and PNG formats. The Compression field in the source bitmap header specifies the image format. If the signs of the source and destination height and width fields differ, this record specifies a mirror-image copy of the source bitmap to the destination. That is, if cxSrc and cxDest have different signs, a mirror image of the source bitmap along the x-axis is specified. If cySrc and cyDest have different signs, a mirror image of the source bitmap along the y-axis is specified.

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


