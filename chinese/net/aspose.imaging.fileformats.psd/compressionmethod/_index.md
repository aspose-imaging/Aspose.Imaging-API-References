---
title: "枚举 CompressionMethod"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Psd.CompressionMethod 枚举。定义用于图像数据的压缩方法。"
type: docs
weight: 7580
url: /zh/net/aspose.imaging.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

定义用于图像数据的压缩方法。

```csharp
public enum CompressionMethod : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Raw | `0` | 无压缩。图像数据以 RGBA 平面顺序存储为原始字节。这意味着首先写入所有 R 数据，然后写入所有 G 数据，接着写入所有 B 数据，最后写入所有 A 数据。 |
| RLE | `1` | RLE 压缩的图像数据以所有扫描线（行 * 通道）的字节计数开始，每个计数存储为两个字节的值。随后是 RLE 压缩数据，每条扫描线单独压缩。RLE 压缩使用的算法与 Macintosh ROM 例程 PackBits 以及 TIFF 标准使用的相同。 |
| ZipWithoutPrediction | `2` | ZIP（无预测）。 |
| ZipWithPrediction | `3` | ZIP（有预测）。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Psd](../../aspose.imaging.fileformats.psd/)
* assembly [Aspose.Imaging](../../)


