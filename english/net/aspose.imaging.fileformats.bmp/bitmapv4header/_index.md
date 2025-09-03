---
title: Class BitmapV4Header
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Bmp.BitmapV4Header class. The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure. The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits
type: docs
weight: 1410
url: /net/aspose.imaging.fileformats.bmp/bitmapv4header/
---
## BitmapV4Header class

The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure. The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.

```csharp
public class BitmapV4Header : BitmapInfoHeader
```

## Properties

| Name | Description |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask/) { get; set; } | Gets or sets the color mask that specifies the alpha component of each pixel. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant/) { get; set; } | Gets or sets number of important palette colors. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused/) { get; set; } | Gets or sets number of palette colors used. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression/) { get; set; } | Gets or sets bitmap compression. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight/) { get; set; } | Gets or sets bitmap height. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize/) { get; set; } | Gets or sets specifies bitmap raw data size in bytes. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes/) { get; set; } | Gets or sets number of planes. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth/) { get; set; } | Gets or sets bitmap width. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter/) { get; set; } | Gets or sets horizontal pixels resolution. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter/) { get; set; } | Gets or sets vertical pixels resolution. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel/) { get; set; } | Gets or sets bits per pixel count. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask/) { get; set; } | Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype/) { get; set; } | Gets or sets the color space of the DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints/) { get; set; } | Gets or sets the CoordinatesTriple class. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks/) { get; set; } | Gets or sets the extra bit masks. Present only in case the DIB header is the BITMAPINFOHEADER and the [`BitmapCompression`](../bitmapinfoheader/bitmapcompression/) is set to either Bitfields (RGB) or AlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue/) { get; set; } | Gets or sets the gamma blue. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen/) { get; set; } | Gets or sets the gamma green. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared/) { get; set; } | Gets or sets the gamma red. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask/) { get; set; } | Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize/) { get; set; } | Gets or sets size of this structure in bytes. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask/) { get; set; } | Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |

### See Also

* class [BitmapInfoHeader](../bitmapinfoheader/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


