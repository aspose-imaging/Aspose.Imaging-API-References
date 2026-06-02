---
title: "枚举 PdfImageCompressionOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.PdfImageCompressionOptions 枚举。PDF 图像压缩选项。"
type: docs
weight: 10480
url: /zh/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

PDF 图像压缩选项

```csharp
public enum PdfImageCompressionOptions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 自动为每个图像选择最合适的压缩方式。 |
| None | `1` | 保存原始图像字节，导致 PDF 文件大小增大。 |
| Rle | `2` | 运行长度压缩。 |
| Flate | `3` | Flate 压缩。 |
| LzwBaselinePredictor | `4` | 预测器选择被限制为 PNG Paeth 预测器以加快处理速度。实际表现出乎意料地好。优于 LzwOptimizedPredictor。 |
| LzwOptimizedPredictor | `5` | 预测器选择更为复杂，应该能得到更小的图像尺寸，但需要更多时间。RFC 2083 认为这是最佳方案。但在测试数据中，基线预测器 LzwBaselinePredictor 表现出色，使优化预测器的压缩率提升落后了 25-40%。 |
| Jpeg | `6` | Jpeg 压缩。不支持透明度。 |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 不支持透明度。 |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 不支持透明度。 |

### 另请参见

* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


