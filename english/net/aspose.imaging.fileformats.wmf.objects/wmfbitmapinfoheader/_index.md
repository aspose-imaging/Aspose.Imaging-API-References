---
title: Class WmfBitmapInfoHeader
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Objects.WmfBitmapInfoHeader class. The BitmapInfoHeader Object contains information about the dimensions and color format of a deviceindependent bitmap DIB
type: docs
weight: 8650
url: /net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent bitmap (DIB).

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount/) { get; set; } | Gets or sets a 16-bit unsigned integer that defines the format of each pixel, and the maximum number of colors in the DIB. This value MUST be in the [`BitCount`](../wmfbitmapbaseheader/bitcount/) Enumeration (section 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the number of color indexes that are required for displaying the DIB. If this value is zero, all color indexes are required |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of indexes in the color table used by the DIB, as follows: If this value is zero, the DIB uses the maximum number of colors that correspond to the BitCount value. If this value is nonzero and the BitCount value is less than 16, this value specifies the number of colors used by the DIB. If this value is nonzero and the BitCount value is 16 or greater, this value specifies the size of the color table used to optimize performance of the system palette. Note If this value is nonzero and greater than the maximum possible size of the color table based on the BitCount value, the maximum color table size SHOULD be assumed. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the compression mode of the DIB. This value MUST be in the Compression Enumeration (section 2.1.1.7). This value MUST NOT specify a compressed format if the DIB is a top-down bitmap, as indicated by the Height value. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the size of this object, in bytes. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height/) { get; set; } | Gets or sets 32-bit signed integer that defines the height of the DIB, in pixels. This value MUST NOT be zero. If this value is positive, the DIB is a bottom-up bitmap, and its origin is the lower-left corner. If this value is negative, the DIB is a top-down bitmap, and its origin is the upper-left corner. Top-down bitmaps do not support compression. This field SHOULD specify the height of the decompressed image file, if the Compression value specifies JPEG or PNG format. |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize/) { get; set; } | Gets or sets a 32-bit unsigned integer that defines the size, in bytes, of the image. If the Compression value is BI_RGB, this value SHOULD be zero and MUST be ignored. If the Compression value is BI_JPEG or BI_PNG, this value MUST specify the size of the JPEG or PNG image buffer, respectively. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes/) { get; set; } | Gets or sets a 16-bit unsigned integer that defines the number of planes for the target device. This value MUST be 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width/) { get; set; } | Gets or sets a 32-bit signed integer that defines the width of the DIB, in pixels. This value MUST be positive. This field SHOULD specify the width of the decompressed image file, if the Compression value specifies JPEG or PNG format. |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter/) { get; set; } | Gets or sets a 32-bit signed integer that defines the horizontal resolution, in pixels-per-meter, of the target device for the DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter/) { get; set; } | Gets or sets a 32-bit signed integer that defines the vertical resolution, in pixels-per-meter, of the target device for the DIB |

## Fields

| Name | Description |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize/) | The structure size |

### See Also

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


