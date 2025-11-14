---
title: WmfCompression Enumeration
type: docs
weight: 70
url: /python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

The Compression Enumeration specifies the type of compression for a bitmap image

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **Member name** | **Description** |
| :- | :- |
| BI_BITFIELDS | The bitmap is not compressed and the color table consists of three DWORD color masks that<br/>                specify the red, green, and blue components, respectively, of each pixel.<br/>                This is valid when used with 16 and 32-bits per pixel bitmaps. |
| BI_CMYK | The image is an uncompressed CMYK format. |
| BI_CMYKRLE4 | A CMYK format that uses RLE compression for bitmaps with 4 bits per pixel.<br/>                The compression uses a 2-byte format consisting of a count byte followed by two word-length color indexes. |
| BI_CMYKRLE8 | A CMYK format that uses RLE compression for bitmaps with 8 bits per pixel.<br/>                The compression uses a 2-byte format consisting of a count byte followed by a byte containing a color index. |
| BI_JPEG | The image is a JPEG image, as specified in [JFIF]. This value SHOULD only be used in certain bitmap<br/>                operations, such as JPEG pass-through. The application MUST query for the pass-through support,<br/>                since not all devices support JPEG pass-through. Using non-RGB bitmaps MAY limit the portability<br/>                of the metafile to other devices. For instance, display device contexts generally do not support this pass-through |
| BI_PNG | The image is a PNG image, as specified in [RFC2083]. This value SHOULD only be used certain bitmap operations,<br/>                such as JPEG/PNG pass-through. The application MUST query for the pass-through support, because not all devices<br/>                support JPEG/PNG pass-through. Using non-RGB bitmaps MAY limit the portability of the metafile to other devices.<br/>                For instance, display device contexts generally do not support this pass-through. |
| BI_RGB | The bitmap is in uncompressed red green blue (RGB) format that is not compressed and does not use color masks. |
| BI_RLE4 | An RGB format that uses RLE compression for bitmaps with 4 bits per pixel.<br/>                The compression uses a 2-byte format consisting of a count byte followed by two word-length color indexes |
| BI_RLE8 | An RGB format that uses run-length encoding (RLE) compression for bitmaps with 8 bits per pixel.<br/>                The compression uses a 2-byte format consisting of a count byte followed by a byte containing a color index. |
