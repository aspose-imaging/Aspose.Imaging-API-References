---
title: Enum CompressionMethod
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Psd.CompressionMethod enum. Defines the compression method used for image data
type: docs
weight: 7580
url: /net/aspose.imaging.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Defines the compression method used for image data.

```csharp
public enum CompressionMethod : short
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Raw | `0` | No compression. The image data stored as raw bytes in RGBA planar order. That means that first all R data is written, then all G is written, then all B and finally all A data is written. |
| RLE | `1` | RLE compressed the image data starts with the byte counts for all the scan lines (rows * channels), with each count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately. The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard. |
| ZipWithoutPrediction | `2` | ZIP without prediction. |
| ZipWithPrediction | `3` | ZIP with prediction. |

### See Also

* namespace [Aspose.Imaging.FileFormats.Psd](../../aspose.imaging.fileformats.psd/)
* assembly [Aspose.Imaging](../../)


