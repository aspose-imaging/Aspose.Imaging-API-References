---
title: Class EmfPlusBitmap
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusBitmap class. The EmfPlusBitmap object specifies a bitmap that contains a graphics image
type: docs
weight: 5290
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---
## EmfPlusBitmap class

The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

```csharp
public sealed class EmfPlusBitmap : EmfPlusBaseImageData
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusBitmap](emfplusbitmap/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BitmapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/bitmapdata/) { get; set; } | Gets or sets bitmap data BitmapData (variable): Variable-length data that defines the bitmap data object specified in the Type field. The content and format of the data can be different for every bitmap type. |
| [Height](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/height/) { get; set; } | Gets or sets bitmap height Height (4 bytes): A 32-bit signed integer that specifies the height in pixels of the area occupied by the bitmap. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |
| [PixelFormat](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/pixelformat/) { get; set; } | Gets or sets pixel format PixelFormat (4 bytes): A 32-bit unsigned integer that specifies the format of the pixels that make up the bitmap image. The supported pixel formats are specified in the [`EmfPlusPixelFormat`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) enumeration (section 2.1.1.25). If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |
| [Stride](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/stride/) { get; set; } | Gets or sets stride of the image Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and the next. This value is the number of bytes per pixel, which is specified in the PixelFormat field, multiplied by the width in pixels, which is specified in the Width field. The value of this field MUST be a multiple of four. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/type/) { get; set; } | Gets or sets type of the image Type (4 bytes): A 32-bit unsigned integer that specifies the type of data in the BitmapData field. This value MUST be defined in the [`EmfPlusBitmapDataType`](../../aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) enumeration (section 2.1.1.2). |
| [Width](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/width/) { get; set; } | Gets or sets image Width Width (4 bytes): A 32-bit signed integer that specifies the width in pixels of the area occupied by the bitmap. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored. |

### See Also

* class [EmfPlusBaseImageData](../emfplusbaseimagedata/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


