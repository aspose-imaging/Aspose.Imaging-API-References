---
title: PdfImageCompressionOptions Enumeration
type: docs
weight: 400
url: /python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

Pdf image compression options

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Member name** | **Description** |
| :- | :- |
| AUTO | Automatically selects the most appropriate compression for each image. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Does not support transparency. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Does not support transparency. |
| FLATE | Flate compression. |
| JPEG | Jpeg compression.<br/>            Does not support transparency. |
| LZW_BASELINE_PREDICTOR | Predictor selection is restricted to PNG Paeth predictor to speed-up the process. In practice<br/>            performs surprisingly good. Better than [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | Predictor selection is more complicated and should result in smaller image sizes but<br/>            taking more time. RFC 2083 says it is the best way to go. But on the test data baseline predictor<br/>            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) kicks ass leaving optimized predictor behing <br/>            by 25-40% compression rate gains. |
| NONE | Saves raw image bytes resulting in bigger pdf file sizes. |
| RLE | Run Length compression. |
