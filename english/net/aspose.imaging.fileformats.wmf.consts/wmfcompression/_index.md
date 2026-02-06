---
title: Enum WmfCompression
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Wmf.Consts.WmfCompression enum. The Compression Enumeration specifies the type of compression for a bitmap image
type: docs
weight: 8330
url: /net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
## WmfCompression enumeration

The Compression Enumeration specifies the type of compression for a bitmap image

```csharp
public enum WmfCompression
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| BI_RGB | `0` | The bitmap is in uncompressed red green blue (RGB) format that is not compressed and does not use color masks. |
| BI_RLE8 | `1` | An RGB format that uses run-length encoding (RLE) compression for bitmaps with 8 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by a byte containing a color index. |
| BI_RLE4 | `2` | An RGB format that uses RLE compression for bitmaps with 4 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by two word-length color indexes |
| BI_BITFIELDS | `3` | The bitmap is not compressed and the color table consists of three DWORD color masks that specify the red, green, and blue components, respectively, of each pixel. This is valid when used with 16 and 32-bits per pixel bitmaps. |
| BI_JPEG | `4` | The image is a JPEG image, as specified in [JFIF]. This value SHOULD only be used in certain bitmap operations, such as JPEG pass-through. The application MUST query for the pass-through support, since not all devices support JPEG pass-through. Using non-RGB bitmaps MAY limit the portability of the metafile to other devices. For instance, display device contexts generally do not support this pass-through |
| BI_PNG | `5` | The image is a PNG image, as specified in [RFC2083]. This value SHOULD only be used certain bitmap operations, such as JPEG/PNG pass-through. The application MUST query for the pass-through support, because not all devices support JPEG/PNG pass-through. Using non-RGB bitmaps MAY limit the portability of the metafile to other devices. For instance, display device contexts generally do not support this pass-through. |
| BI_CMYK | `11` | The image is an uncompressed CMYK format. |
| BI_CMYKRLE8 | `12` | A CMYK format that uses RLE compression for bitmaps with 8 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by a byte containing a color index. |
| BI_CMYKRLE4 | `13` | A CMYK format that uses RLE compression for bitmaps with 4 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by two word-length color indexes. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


