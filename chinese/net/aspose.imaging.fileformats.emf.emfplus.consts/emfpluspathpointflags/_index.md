---
title: EmfPlusPathPointFlags
second_title: Aspose.Imaging for .NET API 参考
description: 一个 32 位无符号整数指定如何解释由该对象定义的点和关联的点类型 C1 位如果设置PathPoints 数组使用 16 位整数指定坐标空间中的绝对位置坐标 如果清除PathPoints 数组使用 32 位浮点坐标指定坐标空间中的绝对位置 注意如果设置了 P 标志如下则该标志可以清除并且必须被忽略 R  1 位如果设置则 PathPointTypes 数组中的点类型由 EmfPlusPathPointTypeRle 对象第 2.2.2.32 节使用行程编码 RLE 压缩的 和/或 EmfPlusPathPointType 对象第 2.2.2.31 节指定有关 RLE 压缩的详细信息请参阅 MS-WMF 3.1.6 节 如果清除则 PathPointTypes 数组中的点类型由 EmfPlusPathPointType 对象指定 P1 位如果设置则 PathPoints 数组中的每个元素指定坐标空间中相对于数组中前一个元素指定的 位置的位置对于 PathPoints 中的第一个元素假定坐标 00 处的先前位置 如果清除则 PathPoints 数组中的每个元素都指定一个绝对位置
type: docs
weight: 4960
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
## EmfPlusPathPointFlags enumeration

一个 32 位无符号整数，指定如何解释由该对象定义的点和关联的点类型。 C（1 位）：如果设置，PathPoints 数组使用 16 位整数指定坐标空间中的绝对位置坐标。 如果清除，PathPoints 数组使用 32 位浮点坐标指定坐标空间中的绝对位置。 注意如果设置了 P 标志（如下），则该标志可以清除并且必须被忽略。 R ( 1 位）：如果设置，则 PathPointTypes 数组中的点类型由 EmfPlusPathPointTypeRle 对象（第 2.2.2.32 节）、使用行程编码 (RLE) 压缩的 和/或 EmfPlusPathPointType 对象（第 2.2.2.31 节）指定。有关 RLE 压缩的详细信息，请参阅 [MS-WMF] 3.1.6 节。 如果清除，则 PathPointTypes 数组中的点类型由 EmfPlusPathPointType 对象指定。 P（1 位）：如果设置，则 PathPoints 数组中的每个元素指定坐标空间中相对于数组中前一个元素指定的 位置的位置。对于 PathPoints 中的第一个元素，假定坐标 (0,0) 处的先前位置。 如果清除，则 PathPoints 数组中的每个元素都指定一个绝对位置。

```csharp
[Flags]
public enum EmfPlusPathPointFlags : short
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| C | `4000` | c 标志 |
| R | `1000` | r 标志 |
| P | `800` | p 标志 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
