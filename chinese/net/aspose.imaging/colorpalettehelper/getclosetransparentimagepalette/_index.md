---
title: "ColorPaletteHelper.GetCloseTransparentImagePalette"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ColorPaletteHelper 方法。获取栅格图像的颜色调色板；如果图像没有调色板，则为图像进行调色板化。如果调色板已存在，则直接使用它，而不进行计算。"
type: docs
weight: 80
url: /zh/net/aspose.imaging/colorpalettehelper/getclosetransparentimagepalette/
---
## ColorPaletteHelper.GetCloseTransparentImagePalette method

当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。

```csharp
public static IColorPalette GetCloseTransparentImagePalette(RasterImage image, int entriesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 栅格图像。 |
| entriesCount | Int32 | 所需的条目数量。 |

### 返回值

颜色调色板，以 *image* 中最常见的颜色开始，并包含 *entriesCount* 条目。

### 另请参见

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


