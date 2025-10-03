---
title: BitmapV5Header Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.bmp/bitmapv5header/
---

**Summary:** The BitmapV5Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.<br/>            <br/>If bV5Height is negative, indicating a top-down DIB, bV5Compression must be either BI_RGB or BI_BITFIELDS. Top-down DIBs cannot be compressed.<br/>            The Independent Color Management interface (ICM) 2.0 allows International Color Consortium (ICC) color profiles to be linked or embedded in DIBs (DIBs). <br/>            See Using Structures for more information. When a DIB is loaded into memory, the profile data (if present) should follow the color table, <br/>            and the bV5ProfileData should provide the offset of the profile data from the beginning of the BITMAPV5HEADER structure. <br/>            The value stored in bV5ProfileData will be different from the value returned by the sizeof operator given the BITMAPV5HEADER argument, <br/>            because bV5ProfileData is the offset in bytes from the beginning of the BITMAPV5HEADER structure to the start of the profile data. <br/>            (Bitmap bits do not follow the color table in memory). Applications should modify the bV5ProfileData member after loading the DIB into memory.<br/>            For packed DIBs, the profile data should follow the bitmap bits similar to the file format. <br/>            The bV5ProfileData member should still give the offset of the profile data from the beginning of the BITMAPV5HEADER.<br/>            Applications should access the profile data only when bV5Size equals the size of the BITMAPV5HEADER and bV5CSType equals PROFILE_EMBEDDED or PROFILE_LINKED.<br/>

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BitmapV5Header

**Inheritance:** BitmapV4Header

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BITMAP_CORE_HEADER_SIZE [static] | int | r | The BITMAPCOREHEADER aka OS21XBITMAPHEADER header size |
| BITMAP_INFO_HEADER_SIZE [static] | int | r | The bitmap information header size v3 |
| BITMAP_INFO_HEADER_SIZE_V2 [static] | int | r | The bitmap information header size v2 |
| BITMAP_INFO_HEADER_SIZE_V3 [static] | int | r | The bitmap information header size v3 |
| BITMAP_INFO_HEADER_SIZE_V4 [static] | int | r | The bitmap information header size v4 |
| BITMAP_INFO_HEADER_SIZE_V5 [static] | int | r | The bitmap information header size v5 |
| OS_22X_BITMAP_HEADER_FULL_SIZE [static] | int | r | The bitmap core header2 size |
| OS_22X_BITMAP_HEADER_SIZE [static] | int | r | The bitmap core header2 size |
| alpha_mask | int | r/w | Gets or sets the color mask that specifies the alpha component of each pixel. |
| bitmap_colors_important | int | r/w | Gets or sets number of important palette colors. |
| bitmap_colors_used | int | r/w | Gets or sets number of palette colors used. |
| bitmap_compression | int | r/w | Gets or sets bitmap compression. |
| bitmap_height | int | r/w | Gets or sets bitmap height. |
| bitmap_image_size | int | r/w | Gets or sets specifies bitmap raw data size in bytes. |
| bitmap_planes | int | r/w | Gets or sets number of planes. |
| bitmap_width | int | r/w | Gets or sets bitmap width. |
| bitmap_x_pels_per_meter | int | r/w | Gets or sets horizontal pixels resolution. |
| bitmap_y_pels_per_meter | int | r/w | Gets or sets vertical pixels resolution. |
| bits_per_pixel | int | r/w | Gets or sets bits per pixel count. |
| blue_mask | int | r/w | Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| cs_type | int | r/w | Gets or sets the color space of the DIB. |
| endpoints | [CieCoordinatesTriple](/imaging/python-net/aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple/) | r/w | Gets or sets the CoordinatesTriple class. |
| extra_bit_masks | int[] | r/w | Gets or sets the extra bit masks.<br/>            Present only in case the DIB header is the BITMAPINFOHEADER and the [BitmapInfoHeader.bitmap_compression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) is set to either [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGB) or [BitmapCompression.ALPHA_BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) (RGBA). |
| gamma_blue | int | r/w | Gets or sets the gamma blue. |
| gamma_green | int | r/w | Gets or sets the gamma green. |
| gamma_red | int | r/w | Gets or sets the gamma red. |
| green_mask | int | r/w | Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| header_size | int | r/w | Gets or sets size of this structure in bytes. |
| intent | int | r/w | Gets or sets the rendering intent for bitmap. |
| profile_data | int | r/w | Gets or sets the profile data. |
| profile_size | int | r/w | Gets or sets the size of the profile. |
| red_mask | int | r/w | Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI_BITFIELDS. |
| reserved | int | r/w | Gets or sets the reserved member. |


