---
title: "枚举 EmfPlusCombineMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts.EmfPlusCombineMode 枚举。CombineMode 枚举定义了合并两个图形区域的模式。在以下描述中，要合并的区域称为现有区域和新区域。"
type: docs
weight: 4830
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/
---
## EmfPlusCombineMode enumeration

CombineMode 枚举定义合并两个图形区域的模式。在以下描述中，要合并的区域称为“existing”（现有）和“new”（新）区域。

```csharp
public enum EmfPlusCombineMode : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| CombineModeReplace | `0` | 用新区域替换现有区域。 |
| CombineModeIntersect | `1` | 用现有区域与新区域的交集替换现有区域。 |
| CombineModeUnion | `2` | 用现有区域和新区域的并集替换现有区域。 |
| CombineModeXor | `3` | 用现有区域和新区域的异或结果替换现有区域。 |
| CombineModeExclude | `4` | 用不在新区域中的现有区域部分替换现有区域。 |
| CombineModeComplement | `5` | 用不在现有区域中的新区域部分替换现有区域。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts/)
* assembly [Aspose.Imaging](../../)


