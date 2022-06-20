---
title: ColorMap
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置颜色图
type: docs
weight: 70
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

获取或设置颜色图。

```csharp
public ushort[] ColorMap { get; set; }
```

### 适当的价值

颜色图。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 值 |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception) | 可以为每像素等于 1 的样本定义颜色图。 或 未定义每个样本的位。 |
| ArgumentOutOfRangeException | value;数组长度必须对应以下公式:3 * (2**BitsPerSample)。 |

### 也可以看看

* class [TiffOptions](../../tiffoptions)
* 命名空间 [Aspose.Imaging.ImageOptions](../../tiffoptions)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->