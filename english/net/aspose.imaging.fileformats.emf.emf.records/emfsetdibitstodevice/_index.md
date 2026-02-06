---
title: Class EmfSetDiBitsToDevice
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetDiBitsToDevice class. The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle
type: docs
weight: 4450
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
## EmfSetDiBitsToDevice class

The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle.

```csharp
public sealed class EmfSetDiBitsToDevice : EmfBitmapRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetDiBitsToDevice](emfsetdibitstodevice/)(EmfRecord) | Initializes a new instance of the `EmfSetDiBitsToDevice` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that defines the destination bounding rectangle in device units. |
| [CScans](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cscans/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of scan lines. |
| [CxSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cxsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the width in pixels of the source rectangle. |
| [CySrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/cysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the height in pixels of the source rectangle |
| [IStartScan](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/istartscan/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the first scan line in the array. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SourceBitmap](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/sourcebitmap/) { get; set; } | Gets or sets a buffer containing the source bitmap, which is not required to be contiguous with the fixed portion of the EMR_SETDIBITSTODEVICE record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [UsageSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/usagesrc/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies how to interpret values in the color table in the source bitmap header. This value MUST be in the DIBColors enumeration (section 2.1.9). |
| [XDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xdest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical x-coordinate of the upper-left corner of the destination rectangle. |
| [XSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/xsrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the x-coordinate in pixels of the lower-left corner of the source rectangle. |
| [YDest](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ydest/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the logical y-coordinate of the upper-left corner of the destination rectangle. |
| [YSrc](../../aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/ysrc/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the y-coordinate in pixels of the lower-left corner of the source rectangle. |

## Remarks

This record supports source images in JPEG and PNG format. The Compression field in the source bitmap header specifies the image format.

### See Also

* class [EmfBitmapRecordType](../emfbitmaprecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


