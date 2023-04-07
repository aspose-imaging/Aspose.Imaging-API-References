---
title: PdfImageCompressionOptions Enumeration
type: docs
weight: 390
url: /python-net/api-reference/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

Pdf image compression options

**Namespace:** [aspose.imaging.imageoptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

**Assembly:**  Aspose.Imaging Version: 23.3.0

## **Members**
|**Member name**|**Description**|
| :- | :- |
|AUTO|Automatically selects the most appropriate compression for each image.|
|NONE|Saves raw image bytes resulting in bigger pdf file sizes.|
|RLE|Run Length compression.|
|FLATE|Flate compression.|
|LZW_BASELINE_PREDICTOR|Predictor selection is restricted to PNG Paeth predictor to speed-up the process. In practice<br/>            performs surprisingly good. Better than [LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/api-reference/aspose.imaging.imageoptions/pdfimagecompressionoptions/).|
|LZW_OPTIMIZED_PREDICTOR|Predictor selection is more complicated and should result in smaller image sizes but<br/>            taking more time. RFC 2083 says it is the best way to go. But on the test data baseline predictor<br/>            [LZW_BASELINE_PREDICTOR](/imaging/python-net/api-reference/aspose.imaging.imageoptions/pdfimagecompressionoptions/) kicks ass leaving optimized predictor behing <br/>            by 25-40% compression rate gains.|
|JPEG|Jpeg compression.<br/>            Does not support transparency.|
|CCITT3|/CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Does not support transparency.|
|CCITT4|/CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Does not support transparency.|
