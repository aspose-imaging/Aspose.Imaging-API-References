---
title: aspose.imaging.fileformats.bmp
type: docs
weight: 140
url: /python-net/aspose.imaging.fileformats.bmp/
---


The module handles Bmp file format processing.

## **Classes**
| **Class** | **Description** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Dimensions and color format of DIB.<br/>            Header name BITMAPCOREHEADER aka OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Specifies BITMAPINFOHEADER. <br/>                OS Support: Windows NT, 3.1x or later.<br/>                Features: Adds 16 bpp and 32 bpp formats. Adds RLE compression. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>The BitmapV4Header structure is extended to allow a JPEG or PNG image to be passed as the source image to StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed.<br/>            The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). <br/>            See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, <br/>            and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. <br/>            The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, <br/>            because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. <br/>            (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory.<br/>            For packed DIBs, the profile data should follow the bitmap bits similar to the file format. <br/>            The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER.<br/>            Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap<br/>            (DIB) files, facilitating efficient manipulation and processing of raster<br/>            images. Performing various operations on images, this API streamlines the<br/>            workflow, offering developers a reliable toolkit for working with BMP and<br/>            DIB formats in their software applications. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | An OS/2 2.x OS22XBITMAPHEADER aka BITMAPCOREHEADER2. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Specifies different bitmap compression methods. |
