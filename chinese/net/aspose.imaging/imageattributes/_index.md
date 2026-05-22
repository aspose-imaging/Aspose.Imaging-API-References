---
title: "类 ImageAttributes"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageAttributes 类。`ImageAttributes` 对象包含有关在渲染过程中位图和元文件颜色如何被操作的信息。`ImageAttributes` 对象维护多个颜色调整设置，包括颜色调整矩阵、灰度调整矩阵、伽马校正值、颜色映射表和颜色阈值。在渲染期间，颜色可以被校正、变暗、变亮或移除。要应用此类操作，请初始化一个 `ImageAttributes` 对象，并将该 `ImageAttributes` 对象的路径连同 `Image` 的路径一起传递给 `DrawImage` 方法。"
type: docs
weight: 9880
url: /zh/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

`ImageAttributes` 对象包含有关在渲染过程中位图和元文件颜色如何被操作的信息。`ImageAttributes` 对象维护多个颜色调整设置，包括颜色调整矩阵、灰度调整矩阵、伽马校正值、颜色映射表和颜色阈值。在渲染期间，颜色可以被校正、变暗、变亮或移除。要应用此类操作，请初始化一个 `ImageAttributes` 对象，并将该 `ImageAttributes` 对象的路径（以及 [`Image`](../image/) 的路径）传递给 `DrawImage` 方法。

```csharp
public sealed class ImageAttributes
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageAttributes](imageattributes/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable/)() | 清除此 `ImageAttributes` 对象的画刷颜色映射表。 |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey/#clearcolorkey)() | 清除默认类别的颜色键（透明度范围）。 |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | 清除指定类别的颜色键（透明度范围）。 |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix/#clearcolormatrix)() | 清除默认类别的颜色调整矩阵。 |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | 清除指定类别的颜色调整矩阵。 |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma/#cleargamma)() | 禁用默认类别的伽马校正。 |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | 禁用指定类别的伽马校正。 |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop/#clearnoop)() | 清除默认类别的 NoOp 设置。 |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | 清除指定类别的 NoOp 设置。 |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel/#clearoutputchannel)() | 清除默认类别的 CMYK（青-品红-黄-黑）输出通道设置。 |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | 清除指定类别的（青-品红-黄-黑）输出通道设置。 |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | 清除默认类别的输出通道颜色配置设置。 |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | 清除指定类别的输出通道颜色配置设置。 |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable/#clearremaptable)() | 清除默认类别的颜色重新映射表。 |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | 清除指定类别的颜色重新映射表。 |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold/#clearthreshold)() | 清除默认类别的阈值。 |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | 清除指定类别的阈值。 |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable/)(ColorMap[]) | 设置画笔类别的颜色重新映射表。 |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | 设置默认类别的颜色键。 |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | 设置指定类别的颜色键（透明度范围）。 |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | 设置默认类别的颜色调整矩阵和灰度调整矩阵。 |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | 设置默认类别的颜色调整矩阵和灰度调整矩阵。 |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 设置指定类别的颜色调整矩阵和灰度调整矩阵。 |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | 设置默认类别的颜色调整矩阵。 |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | 设置默认类别的颜色调整矩阵。 |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | 设置指定类别的颜色调整矩阵。 |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma/#setgamma)(float) | 设置默认类别的伽马值。 |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | 设置指定类别的伽马值。 |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop/#setnoop)() | 关闭默认类别的颜色调整。 |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | 关闭指定类别的颜色调整。 |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | 为默认类别设置 CMYK（青-品红-黄-黑）输出通道。 |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | 为指定类别设置 CMYK（青-品红-黄-黑）输出通道。 |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | 为默认类别设置输出通道的色彩配置文件。 |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | 为指定类别设置输出通道的色彩配置文件。 |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | 为默认类别设置颜色重新映射表。 |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | 为指定类别设置颜色重新映射表。 |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold/#setthreshold)(float) | 为默认类别设置阈值（透明度范围）。 |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | 为指定类别设置阈值（透明度范围）。 |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | 设置用于决定如何在形状上或形状边界平铺纹理的包裹模式。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。 |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | 设置用于决定如何在形状上或形状边界平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。 |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | 设置用于决定如何在形状上或形状边界平铺纹理的包裹模式和颜色。当纹理小于要填充的形状时，纹理会在形状上平铺以填充它。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


