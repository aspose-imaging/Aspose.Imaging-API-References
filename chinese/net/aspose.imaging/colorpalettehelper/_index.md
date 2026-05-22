---
title: "类 ColorPaletteHelper"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ColorPaletteHelper 类。用于调色板操作的帮助类"
type: docs
weight: 390
url: /zh/net/aspose.imaging/colorpalettehelper/
---
## ColorPaletteHelper class

用于调色板操作的帮助类。

```csharp
public static class ColorPaletteHelper
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create4Bit](../../aspose.imaging/colorpalettehelper/create4bit/)() | 创建 4 位颜色调色板。 |
| static [Create4BitGrayscale](../../aspose.imaging/colorpalettehelper/create4bitgrayscale/)(bool) | 创建 4 位灰度调色板。 |
| static [Create8Bit](../../aspose.imaging/colorpalettehelper/create8bit/)() | 创建 8 位颜色调色板。 |
| static [Create8BitGrayscale](../../aspose.imaging/colorpalettehelper/create8bitgrayscale/)(bool) | 创建 8 位灰度调色板。 |
| static [CreateGrayscale](../../aspose.imaging/colorpalettehelper/creategrayscale/)(int) | 获取指定位数的灰度调色板。允许的位值为 1、2、4、8。 |
| static [CreateMonochrome](../../aspose.imaging/colorpalettehelper/createmonochrome/)() | 创建仅包含 2 种颜色的单色调色板。 |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_4)(RasterImage, int) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。 |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_5)(RasterImage, int, PaletteMiningMethod) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。调色板将被优化以获得更好的索引图像质量，或在使用 PaletteMiningMethod.UseCurrentPalette 时保持"AS IS"。 |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette)(RasterImage, Rectangle, int) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。 |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_1)(RasterImage, Rectangle, int, bool) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。 |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_2)(RasterImage, Rectangle, int, bool, Color) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。 |
| static [GetCloseImagePalette](../../aspose.imaging/colorpalettehelper/getcloseimagepalette/#getcloseimagepalette_3)(RasterImage, Rectangle, int, bool, Color, bool) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。 |
| static [GetCloseTransparentImagePalette](../../aspose.imaging/colorpalettehelper/getclosetransparentimagepalette/)(RasterImage, int) | 当栅格图像没有调色板时，从图像获取颜色调色板（对图像进行调色）。如果调色板已存在，则使用现有调色板而不进行计算。 |
| static [GetDownscalePalette](../../aspose.imaging/colorpalettehelper/getdownscalepalette/)(RasterImage) | 获取 256 色调色板，由初始图像颜色值的高位组成。 |
| static [GetUniformColorPalette](../../aspose.imaging/colorpalettehelper/getuniformcolorpalette/)(RasterImage) | 获取均匀的 256 色调色板。 |
| static [HasTransparentColors](../../aspose.imaging/colorpalettehelper/hastransparentcolors/)(IColorPalette) | 确定指定的调色板是否包含透明颜色。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


