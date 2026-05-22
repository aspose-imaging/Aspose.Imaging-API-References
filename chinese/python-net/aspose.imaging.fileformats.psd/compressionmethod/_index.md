---
title: "CompressionMethod 枚举"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.psd/compressionmethod/
---

定义用于图像数据的压缩方法。

**Module:** [aspose.imaging.fileformats.psd](/imaging/python-net/aspose.imaging.fileformats.psd/)

**Full Name:** aspose.imaging.fileformats.psd.CompressionMethod

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| RAW | 无压缩。图像数据以 RGBA 平面顺序存储为原始字节。<br/>            这意味着首先写入所有 R 数据，然后是所有 G 数据，接着是所有 B 数据，最后是所有 A 数据。 |
| RLE | RLE 压缩的图像数据以所有扫描线（行 * 通道）的字节计数开始，每个<br/>            计数以两个字节的值存储。随后是 RLE 压缩数据，每条扫描线分别压缩。<br/>            RLE 压缩使用的算法与 Macintosh ROM 例程 PackBits 和 TIFF 标准中使用的相同。 |
| ZIP_WITHOUT_PREDICTION | ZIP 无预测。 |
| ZIP_WITH_PREDICTION | ZIP 有预测。 |
