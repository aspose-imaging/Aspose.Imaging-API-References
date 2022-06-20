---
title: ColorPalette
second_title: Aspose.Imaging for .NET API 参考
description: 定义组成调色板的颜色数组颜色是 32 位 ARGB 颜色不可继承
type: docs
weight: 380
url: /zh/net/aspose.imaging/colorpalette/
---
## ColorPalette class

定义组成调色板的颜色数组。颜色是 32 位 ARGB 颜色。不可继承。

```csharp
public sealed class ColorPalette : IColorPalette
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ColorPalette](colorpalette#constructor)(Color[]) | 初始化[`ColorPalette`](../colorpalette)类的新实例，并且 IsCompactPalette 为假。 |
| [ColorPalette](colorpalette#constructor_2)(int[]) | 初始化[`ColorPalette`](../colorpalette)类的新实例，并且 IsCompactPalette 为假。 |
| [ColorPalette](colorpalette#constructor_1)(Color[], bool) | 初始化[`ColorPalette`](../colorpalette)类的新实例。 |
| [ColorPalette](colorpalette#constructor_3)(int[], bool) | 初始化[`ColorPalette`](../colorpalette)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Argb32Entries](../../aspose.imaging/colorpalette/argb32entries) { get; } | 获取 32 位 ARGB 结构的数组。 |
| [Entries](../../aspose.imaging/colorpalette/entries) { get; } | 获取[`Color`](../color)结构的数组。 |
| [EntriesCount](../../aspose.imaging/colorpalette/entriescount) { get; } | 获取条目数。 |
| [IsCompactPalette](../../aspose.imaging/colorpalette/iscompactpalette) { get; } | 获取或设置一个指示是否使用紧凑调色板的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [CopyPalette](../../aspose.imaging/colorpalette/copypalette#copypalette)(IColorPalette) | 复制调色板。 |
| static [CopyPalette](../../aspose.imaging/colorpalette/copypalette#copypalette_1)(IColorPalette, bool) | 复制调色板。 |
| [GetArgb32Color](../../aspose.imaging/colorpalette/getargb32color)(int) | 按索引获取 32 位 ARGB 调色板颜色。 |
| [GetColor](../../aspose.imaging/colorpalette/getcolor)(int) | 按索引获取调色板颜色。 |
| [GetNearestColorIndex](../../aspose.imaging/colorpalette/getnearestcolorindex#getnearestcolorindex)(Color) | 获取最接近颜色的索引。 |
| [GetNearestColorIndex](../../aspose.imaging/colorpalette/getnearestcolorindex#getnearestcolorindex_1)(int) | 获取最接近颜色的索引。 |

### 也可以看看

* interface [IColorPalette](../icolorpalette)
* 命名空间 [Aspose.Imaging](../../aspose.imaging)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->