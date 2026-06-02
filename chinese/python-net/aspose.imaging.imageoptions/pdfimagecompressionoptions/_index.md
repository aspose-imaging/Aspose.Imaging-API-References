---
title: "PdfImageCompressionOptions 枚举"
type: docs
weight: 400
url: /zh/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

PDF 图像压缩选项

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| AUTO | 自动为每个图像选择最合适的压缩方式。 |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            不支持透明度。 |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            不支持透明度。 |
| FLATE | Flate 压缩。 |
| JPEG | Jpeg 压缩。<br/>            不支持透明度。 |
| LZW_BASELINE_PREDICTOR | 预测器选择受限于 PNG Paeth 预测器以加快处理速度。 在实践中<br/>            表现出乎意料地好。 优于 [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/)。 |
| LZW_OPTIMIZED_PREDICTOR | 预测器选择更为复杂，应该会产生更小的图像尺寸，但<br/>            需要更多时间。 RFC 2083 表示这是最佳方案。 但在测试数据中，基线预测器<br/>            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) 表现出色，使得优化预测器落后 <br/>            25-40% 的压缩率提升。 |
| NONE | 保存原始图像字节，导致 PDF 文件大小增大。 |
| RLE | 行程长度压缩。 |
