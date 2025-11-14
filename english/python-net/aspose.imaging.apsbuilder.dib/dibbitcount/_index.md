---
title: DibBitCount Enumeration
type: docs
weight: 10
url: /python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

The BitCount Enumeration specifies the number of bits that define each pixel and<br/>                the maximum number of colors in a device-independent bitmap (DIB).

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BITCOUNT0 | The number of bits per pixel is undefined.<br/>                The image SHOULD be in either JPEG or PNG format.<br/>                Neither of these formats includes a color table, so this value<br/>                specifies that no color table is present. See [JFIF] and [RFC2083]<br/>                for more information concerning JPEG and PNG compression formats. |
| BITCOUNT1 | The image is specified with two colors.Each pixel in the bitmap is<br/>                represented by a single bit. If the bit is clear, the pixel is<br/>                displayed with the color of the first entry in the color table;<br/>                if the bit is set, the pixel has the color of the second entry in the table. |
| BITCOUNT2 | The image is specified with a maximum of 16 colors.<br/>                Each pixel in the bitmap is represented by a 4-bit index into the<br/>                color table, and each byte contains 2 pixels. |
| BITCOUNT3 | The image is specified with a maximum of 256 colors.<br/>                Each pixel in the bitmap is represented by an 8-bit index into the<br/>                color table, and each byte contains 1 pixel. |
| BITCOUNT4 | The image is specified with a maximum of 2^16 colors.<br/>                Each pixel in the bitmap is represented by a 16-bit value |
| BITCOUNT5 | The bitmap has a maximum of 2^24 colors, and the Colors field of DIB is NULL.<br/>                Each 3-byte triplet in the bitmap array represents the relative intensities<br/>                of blue, green, and red, respectively, for a pixel. The Colors color table<br/>                is used for optimizing colors used on palette-based devices, and MUST contain<br/>                the number of entries specified by the ColorUsed field of the BitmapInfoHeader Object |
| BITCOUNT6 | The bitmap has a maximum of 2^24 colors |
