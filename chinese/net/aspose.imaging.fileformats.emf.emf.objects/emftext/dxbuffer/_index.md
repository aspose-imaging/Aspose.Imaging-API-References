---
title: DxBuffer
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置可选的字符间距缓冲区 UndefinedSpace2变量可选的未使用字节数 OutputDx 字段不需要 紧跟在此结构的前面部分之后 OutputDx变量一个 32 位无符号整数数组指定 逻辑单元中相邻字符单元的原点之间的输出间距该字段的位置由 从该记录的开头开始的 offDx 的值以字节为单位指定如果定义了间距则此字段包含 与输出字符串中的字符数量相同的值如果 EmrText 对象 的 Options 字段包含 ETO_PDY 标志则此缓冲区包含的值是输出字符串 中字符数的两倍一个水平偏移量和一个垂直偏移量对于每个按此顺序如果指定了 ETO_RTLREADING则 字符从右到左排列而不是从左到右排列没有其他选项会影响对该字段的解释
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emftext/dxbuffer/
---
## EmfText.DxBuffer property

获取或设置可选的字符间距缓冲区 UndefinedSpace2（变量）:可选的未使用字节数。 OutputDx 字段不需要 紧跟在此结构的前面部分之后。 OutputDx（变量）:一个 32 位无符号整数数组，指定 逻辑单元中相邻字符单元的原点之间的输出间距。该字段的位置由 从该记录的开头开始的 offDx 的值（以字节为单位）指定。如果定义了间距，则此字段包含 与输出字符串中的字符数量相同的值。如果 EmrText 对象 的 Options 字段包含 ETO_PDY 标志，则此缓冲区包含的值是输出字符串 中字符数的两倍，一个水平偏移量和一个垂直偏移量对于每个，按此顺序。如果指定了 ETO_RTLREADING，则 字符从右到左排列，而不是从左到右排列。没有其他选项会影响对该字段的解释。

```csharp
public int[] DxBuffer { get; set; }
```

### 也可以看看

* class [EmfText](../../emftext)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../emftext)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->