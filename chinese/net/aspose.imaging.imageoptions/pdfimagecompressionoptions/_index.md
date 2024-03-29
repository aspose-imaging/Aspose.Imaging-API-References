---
title: PdfImageCompressionOptions
second_title: Aspose.Imaging for .NET API 参考
description: Pdf 图像压缩选项
type: docs
weight: 10100
url: /zh/net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
## PdfImageCompressionOptions enumeration

Pdf 图像压缩选项

```csharp
public enum PdfImageCompressionOptions
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 自动为每张图像选择最合适的压缩方式。 |
| None | `1` | 保存原始图像字节导致更大的 pdf 文件大小。 |
| Rle | `2` | 运行长度压缩。 |
| Flate | `3` | 扁平压缩。 |
| LzwBaselinePredictor | `4` | 预测器选择仅限于 PNG Paeth 预测器以加快处理速度。在实践中 的表现出奇的好。优于LzwOptimizedPredictor . |
| LzwOptimizedPredictor | `5` | 预测器选择更复杂，应该会导致更小的图像尺寸但 需要更多时间。 RFC 2083 说这是最好的方法。但是在测试数据基线 predictor LzwBaselinePredictor踢屁股离开优化的预测器行为 25-40% 的压缩率增益。 |
| Jpeg | `6` | Jpeg 压缩。 不支持透明度。 |
| Ccitt3 | `7` | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 不支持透明度。 |
| Ccitt4 | `8` | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 不支持透明度。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
