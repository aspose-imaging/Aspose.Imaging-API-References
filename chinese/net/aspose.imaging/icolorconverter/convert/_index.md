---
title: Convert
second_title: Aspose.Imaging for .NET API 参考
description: 将传递的数据转换为输出格式
type: docs
weight: 10
url: /zh/net/aspose.imaging/icolorconverter/convert/
---
## IColorConverter.Convert method

将传递的数据转换为输出格式。

```csharp
public int Convert(PixelDataFormat sourceFormat, byte[] data, int offset, int bitStart, 
    int samplesCount, int linesCount, PixelDataFormat destFormat, byte[] outputData, 
    int outputOffset)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sourceFormat | PixelDataFormat | 源格式。 |
| data | Byte[] | 源数据。 |
| offset | Int32 | 应该开始数据复制的字节偏移量。 |
| bitStart | Int32 | 位开始。请注意，此值不是字节对齐的值，而是应该开始复制的实际位。 |
| samplesCount | Int32 | 样本计数。 |
| linesCount | Int32 | 行数。 |
| destFormat | PixelDataFormat | 目标格式。 |
| outputData | Byte[] | 输出数据。 |
| outputOffset | Int32 | 数据复制应该开始的输出偏移量。 |

### 返回值

转换后的字节数。

### 也可以看看

* class [PixelDataFormat](../../pixeldataformat)
* interface [IColorConverter](../../icolorconverter)
* 命名空间 [Aspose.Imaging](../../icolorconverter)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
