---
title: Enum PdfImageCompressionOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.PdfImageCompressionOptions enum. Pdf image compression options
type: docs
weight: 10410
url: /net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

Pdf image compression options

```csharp
public enum PdfImageCompressionOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Auto | `0` | Automatically selects the most appropriate compression for each image. |
| None | `1` | Saves raw image bytes resulting in bigger pdf file sizes. |
| Rle | `2` | Run Length compression. |
| Flate | `3` | Flate compression. |
| LzwBaselinePredictor | `4` | Predictor selection is restricted to PNG Paeth predictor to speed-up the process. In practice performs surprisingly good. Better than LzwOptimizedPredictor. |
| LzwOptimizedPredictor | `5` | Predictor selection is more complicated and should result in smaller image sizes but taking more time. RFC 2083 says it is the best way to go. But on the test data baseline predictor LzwBaselinePredictor kicks ass leaving optimized predictor behing by 25-40% compression rate gains. |
| Jpeg | `6` | Jpeg compression. Does not support transparency. |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Does not support transparency. |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Does not support transparency. |

### See Also

* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


