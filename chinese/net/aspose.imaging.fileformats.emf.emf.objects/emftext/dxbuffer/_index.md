---
title: "EmfText.DxBuffer"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfText 属性。获取或设置可选的字符间距缓冲区 UndefinedSpace2 变量——可选的未使用字节数。OutputDx 字段不必紧随此结构的前一部分。OutputDx 变量是一个 32 位无符号整数数组，指定相邻字符单元原点之间的输出间距（逻辑单位）。该字段的位置由 offDx 的值（相对于此记录起始的字节数）决定。如果定义了间距，则该字段包含与输出字符串中字符数量相同的值。如果 EmrText 对象的 Options 字段包含 ETO_PDY 标志，则此缓冲区包含的值是字符数的两倍，每个字符依次有水平和垂直偏移。如果指定了 ETO_RTLREADING，则字符从右向左排列，而不是从左向右。没有其他选项会影响此字段的解释。"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emftext/dxbuffer/
---
## EmfText.DxBuffer property

获取或设置可选的字符间距缓冲区 UndefinedSpace2（变量）：可选的未使用字节数。OutputDx 字段不需要紧跟在此结构的前一部分之后。OutputDx（变量）：一个 32 位无符号整数数组，指定相邻字符单元原点之间的输出间距（逻辑单位）。该字段的位置由 offDx 的字节值（相对于记录起始）指定。如果已定义间距，则该字段包含与输出字符串中字符数量相同的值。如果 EmrText 对象的 Options 字段包含 ETO_PDY 标志，则此缓冲区包含的值数量是输出字符串字符数的两倍，每个字符对应一个水平偏移和一个垂直偏移，按此顺序。如果指定了 ETO_RTLREADING，字符将从右向左排列，而不是从左向右。没有其他选项会影响此字段的解释。

```csharp
public int[] DxBuffer { get; set; }
```

### 另请参见

* class [EmfText](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../emftext/)
* assembly [Aspose.Imaging](../../../)


