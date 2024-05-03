---
title: Aspose.Imaging.FileFormats.Bmp
second_title: Aspose.Imaging for .NET API Reference
description: The namespace handles Bmp file format processing
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.bmp/
---
The namespace handles Bmp file format processing.

## Classes

| Class | Description |
| --- | --- |
| [BitmapCoreHeader](./bitmapcoreheader/) | Dimensions and color format of DIB. Header name BITMAPCOREHEADER aka OS21XBITMAPHEADER. |
| [BitmapInfoHeader](./bitmapinfoheader/) | Specifies BITMAPINFOHEADER. OS Support: Windows NT, 3.1x or later. Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression. |
| [BitmapV4Header](./bitmapv4header/) | The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure. The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits. |
| [BitmapV5Header](./bitmapv5header/) | The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure. If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed. The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory. For packed DIBs, the profile data should follow the bitmap bits similar to the file format. The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER. Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED. |
| [BmpImage](./bmpimage/) | You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap (DIB) files, facilitating efficient manipulation and processing of raster images. Performing various operations on images, this API streamlines the workflow, offering developers a reliable toolkit for working with BMP and DIB formats in their software applications. |
| [Os22XBitmapHeader](./os22xbitmapheader/) | An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [BitmapCompression](./bitmapcompression/) | Specifies different bitmap compression methods. |


