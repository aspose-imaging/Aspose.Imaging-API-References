---
title: BitmapV5Header
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 1380
url: /net/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure. If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed. The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory. For packed DIBs, the profile data should follow the bitmap bits similar to the file format. The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER. Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Properties

| Name | Description |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Gets or sets the color mask that specifies the alpha component of each pixel. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Gets or sets number of important palette colors. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Gets or sets number of palette colors used. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Gets or sets bitmap compression. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Gets or sets bitmap height. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Gets or sets specifies bitmap raw data size in bytes. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Gets or sets number of planes. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Gets or sets bitmap width. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Gets or sets horizontal pixels resolution. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Gets or sets vertical pixels resolution. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Gets or sets bits per pixel count. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Gets or sets the color space of the DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Gets or sets the CoordinatesTriple class. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Gets or sets the extra bit masks. Present only in case the DIB header is the BITMAPINFOHEADER and the [`BitmapCompression`](../bitmapinfoheader/bitmapcompression) is set to either Bitfields (RGB) or AlphaBitfields (RGBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Gets or sets the gamma blue. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Gets or sets the gamma green. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Gets or sets the gamma red. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Gets or sets size of this structure in bytes. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Gets or sets the rendering intent for bitmap. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Gets or sets the profile data. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Gets or sets the size of the profile. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Gets or sets the reserved member. |

### See Also

* class [BitmapV4Header](../bitmapv4header)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
