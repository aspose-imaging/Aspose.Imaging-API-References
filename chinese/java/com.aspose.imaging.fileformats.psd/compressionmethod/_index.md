---
title: "压缩方法"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义用于图像数据的压缩方法。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

定义用于图像数据的压缩方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Raw](#Raw) | 无压缩。 |
| [RLE](#RLE) | RLE 压缩的图像数据以所有扫描线（行 \* 通道）的字节计数开始，每个计数存储为两个字节的值。 |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP（无预测）。 |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP（有预测）。 |
### Raw {#Raw}
```
public static final short Raw
```


无压缩。图像数据以 RGBA 平面顺序存储为原始字节。这意味着首先写入所有 R 数据，然后是所有 G 数据，接着是所有 B 数据，最后是所有 A 数据。

### RLE {#RLE}
```
public static final short RLE
```


RLE 压缩的图像数据以所有扫描线（行 \* 通道）的字节计数开始，每个计数存储为两个字节的值。随后是 RLE 压缩数据，对每条扫描线分别压缩。RLE 压缩使用的算法与 Macintosh ROM 例程 PackBits 以及 TIFF 标准中使用的相同。

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP（无预测）。

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP（有预测）。

