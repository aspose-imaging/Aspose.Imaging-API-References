---
title: "枚举 EmfPlusPathPointFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusPathPointFlags 枚举。一个 32 位无符号整数，指定如何解释此对象定义的点及其关联的点类型。C 1 位 如果设置，则 PathPoints 数组使用 16 位整数坐标指定坐标空间中的绝对位置。如果清除，则 PathPoints 数组使用 32 位浮点坐标指定绝对位置。注意：如果下面的 P 标志被设置，则此标志可能被清除且必须被忽略。R 1 位 如果设置，则 PathPointTypes 数组中的点类型由 EmfPlusPathPointTypeRle 对象（第 2.2.2.32 节）指定，这些对象使用行程长度编码（RLE）压缩和/或 EmfPlusPathPointType 对象（第 2.2.2.31 节）。有关 RLE 压缩的更多信息，请参阅 MSWMF 第 3.1.6 节。如果清除，则 PathPointTypes 数组中的点类型由 EmfPlusPathPointType 对象指定。P 1 位 如果设置，则 PathPoints 数组中的每个元素指定相对于前一个元素在坐标空间中的位置。对于 PathPoints 的第一个元素，假定前一个位置坐标为 00。如果清除，则 PathPoints 数组中的每个元素指定绝对位置。"
type: docs
weight: 5080
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

一个 32 位无符号整数，用于指定如何解释此对象定义的点及其关联的点类型。C (1 位)：如果设置，则 PathPoints 数组使用 16 位整数坐标指定坐标空间中的绝对位置。如果未设置，则 PathPoints 数组使用 32 位浮点坐标指定绝对位置。注意：如果下面的 P 标志被设置，则此标志可能未设置且必须被忽略。R (1 位)：如果设置，PathPointTypes 数组中的点类型由 EmfPlusPathPointTypeRle 对象（第 2.2.2.32 节）指定，这些对象使用行程长度编码 (RLE) 压缩，和/或由 EmfPlusPathPointType 对象（第 2.2.2.31 节）指定。有关 RLE 压缩的更多信息，请参阅 [MS-WMF] 第 3.1.6 节。如果未设置，则 PathPointTypes 数组中的点类型由 EmfPlusPathPointType 对象指定。P (1 位)：如果设置，PathPoints 数组中的每个元素指定相对于数组中前一个元素指定的位置的坐标空间位置。对于 PathPoints 的第一个元素，假定前一个位置为坐标 (0,0)。如果未设置，PathPoints 数组中的每个元素指定绝对位置。

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| C | `4000` | c 标志 |
| R | `1000` | r 标志 |
| P | `800` | p 标志 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


