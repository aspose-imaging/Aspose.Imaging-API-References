---
title: "IColorConverter.Convert"
second_title: "Aspose.Imaging for .NET API 参考"
description: "IColorConverter 方法。将传入的数据转换为输出格式"
type: docs
weight: 10
url: /zh/net/aspose.imaging/icolorconverter/convert/
---
## IColorConverter.Convert method

将传入的数据转换为输出格式。

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | 源格式。 |
| 数据 | Byte[] | 源数据。 |
| 偏移 | Int32 | 以字节为单位的偏移量，指示数据复制应从何处开始。 |
| 位起始 | Int32 | 位起始。注意，此值不是字节对齐的，而是实际的位，指示复制应从何处开始。 |
| 样本计数 | Int32 | 样本计数。 |
| linesCount | Int32 | 行计数。 |
| destFormat | PixelDataFormat | 目标格式。 |
| outputData | Byte[] | 输出数据。 |
| outputOffset | Int32 | 输出偏移量，数据复制应从此处开始。 |

### 返回值

已转换的字节计数。

### 另请参见

* class [PixelDataFormat](../../pixeldataformat/)
* interface [IColorConverter](../)
* namespace [Aspose.Imaging](../../icolorconverter/)
* assembly [Aspose.Imaging](../../../)


