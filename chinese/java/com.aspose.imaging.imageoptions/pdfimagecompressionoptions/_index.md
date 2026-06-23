---
title: "PdfImageCompressionOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "Pdf 图像压缩选项"
type: docs
weight: 35
url: /zh/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Pdf 图像压缩选项
## 字段

| 字段 | 描述 |
| --- | --- |
| [Auto](#Auto) | 自动为每个图像选择最合适的压缩方式。 |
| [None](#None) | 保存原始图像字节，导致 PDF 文件大小增大。 |
| [Rle](#Rle) | 行程长度压缩。 |
| [Flate](#Flate) | Flate 压缩。 |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | 预测器选择受限于 PNG Paeth 预测器，以加快处理速度。 |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | 预测器选择更为复杂，应该能得到更小的图像尺寸，但会耗费更多时间。 |
| [Jpeg](#Jpeg) | Jpeg 压缩。 |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 不支持透明度。 |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 不支持透明度。 |
### Auto {#Auto}
```
public static final int Auto
```


自动为每个图像选择最合适的压缩方式。

### None {#None}
```
public static final int None
```


保存原始图像字节，导致 PDF 文件大小增大。

### Rle {#Rle}
```
public static final int Rle
```


行程长度压缩。

### Flate {#Flate}
```
public static final int Flate
```


Flate 压缩。

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


预测器选择受限于 PNG Paeth 预测器，以加快处理速度。实际表现出奇地好。优于 [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor)。

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


预测器选择更为复杂，应该能得到更小的图像尺寸，但会耗费更多时间。RFC 2083 认为这是最佳方案。但在测试数据中，基线预测器 [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) 表现出色，使优化预测器的压缩率提升落后了 25-40%。

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Jpeg 压缩。不支持透明度。

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 不支持透明度。

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 不支持透明度。

