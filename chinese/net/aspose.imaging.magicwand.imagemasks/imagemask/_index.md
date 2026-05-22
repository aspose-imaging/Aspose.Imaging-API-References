---
title: "类 ImageMask"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.MagicWand.ImageMasks.ImageMask 类。描述二值图像掩码"
type: docs
weight: 10890
url: /zh/net/aspose.imaging.magicwand.imagemasks/imagemask/
---
## ImageMask class

描述二值图像掩码。

```csharp
public abstract class ImageMask : IImageMask
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagemask/bounds/) { get; } | 获取此掩码的边界（以像素为单位）。 |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagemask/height/) { get; } | 获取此掩码的高度（以像素为单位）。 |
| abstract [Item](../../aspose.imaging.magicwand.imagemasks/imagemask/item/) { get; } | 获取指定像素的透明度。 |
| abstract [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/imagemask/selectionbounds/) { get; } | 获取掩码选定部分的边界（以像素为单位）。 |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagemask/source/) { get; } | 获取用于创建此掩码的源图像（如果存在）。 |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagemask/width/) { get; } | 获取此掩码的宽度（以像素为单位）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagemask/apply/)() | 如果存在，将当前遮罩应用于 [`RasterImage`](../../aspose.imaging/rasterimage/) 源。 |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagemask/applyto/)(RasterImage) | 将当前遮罩应用于指定的 [`RasterImage`](../../aspose.imaging/rasterimage/)。 |
| abstract [Clone](../../aspose.imaging.magicwand.imagemasks/imagemask/clone/)() | 创建一个新对象，该对象是当前实例的副本。 |
| abstract [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/#crop)(Rectangle) | 使用指定的矩形裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/#crop_1)(Size) | 使用指定的尺寸裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/#crop_2)(int, int) | 使用指定的宽度和高度裁剪遮罩。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/#exclusivedisjunction)(ImageMask) | 获取当前遮罩与提供的遮罩的异或。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/#exclusivedisjunction_1)(MagicWandSettings) | 获取当前遮罩与对遮罩源应用魔棒选择后的结果的异或。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/#exclusivedisjunction_2)(RasterImage, MagicWandSettings) | 获取当前遮罩与对提供的图像应用魔棒选择后的结果的异或。 |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagemask/getbyteopacity/)(int, int) | 获取指定像素的透明度，精确到字节。 |
| [GetFeathered](../../aspose.imaging.magicwand.imagemasks/imagemask/getfeathered/)(FeatheringSettings) | 获取使用指定设置羽化边界的灰度遮罩。 |
| abstract [Inflate](../../aspose.imaging.magicwand.imagemasks/imagemask/inflate/)(int) | 按指定量膨胀此遮罩。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/#intersect)(ImageMask) | 获取当前遮罩与提供的遮罩的交集。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/#intersect_1)(MagicWandSettings) | 获取当前遮罩与对遮罩源应用魔棒选择结果的交集。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/#intersect_2)(RasterImage, MagicWandSettings) | 获取当前掩码与对提供的图像应用魔棒选择的结果的交集。 |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagemask/invert/)() | 获取当前掩码的反转。 |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagemask/isopaque/)(int, int) | 检查指定像素是否不透明。 |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagemask/istransparent/)(int, int) | 检查指定像素是否透明。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/#subtract)(ImageMask) | 获取当前掩码减去提供的掩码的结果。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/#subtract_1)(MagicWandSettings) | 获取对当前掩码源应用魔棒选择的结果，并从掩码中减去该结果。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/#subtract_2)(RasterImage, MagicWandSettings) | 获取对提供的图像应用魔棒选择的结果，并从当前掩码中减去该结果。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/#union)(ImageMask) | 获取当前掩码与提供的掩码的并集。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/#union_1)(MagicWandSettings) | 获取当前掩码与对掩码源应用魔棒选择的结果的并集。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/#union_2)(RasterImage, MagicWandSettings) | 获取当前掩码与对提供的图像应用魔棒选择的结果的并集。 |
| [operator +](../../aspose.imaging.magicwand.imagemasks/imagemask/op_addition/) | 两个掩码的并集。 |
| [operator ^](../../aspose.imaging.magicwand.imagemasks/imagemask/op_exclusiveor/) | 两个掩码的异或。 |
| [explicit operator](../../aspose.imaging.magicwand.imagemasks/imagemask/op_explicit/) | [`ImageGrayscaleMask`](../imagegrayscalemask/) 转换运算符。 |
| [operator !](../../aspose.imaging.magicwand.imagemasks/imagemask/op_logicalnot/) | 反转掩码。 |
| [operator *](../../aspose.imaging.magicwand.imagemasks/imagemask/op_multiply/) | 两个掩码的交集。 |
| [operator -](../../aspose.imaging.magicwand.imagemasks/imagemask/op_subtraction/) | 从第一个掩码中减去第二个掩码。 |

## 示例

示例展示了如何使用魔棒工具选择图像的复杂区域以及与掩码交互的能力（反转、并集、减去）。

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // 使用魔棒工具基于像素 (845, 128) 的色调和颜色创建新掩码
    MagicWandTool.Select(image, new MagicWandSettings(845, 128))
        // 将现有掩码与由魔棒工具创建的指定掩码进行并集
        .Union(new MagicWandSettings(416, 387))
        // 反转现有掩码
        .Invert()
        // 从现有掩码中减去由魔棒工具使用指定阈值创建的指定掩码
        .Subtract(new MagicWandSettings(1482, 346) { Threshold = 69 })
        // 一次一次地从现有掩码中减去四个指定的矩形掩码
        .Subtract(new RectangleMask(0, 0, 800, 150))
        .Subtract(new RectangleMask(0, 380, 600, 220))
        .Subtract(new RectangleMask(930, 520, 110, 40))
        .Subtract(new RectangleMask(1370, 400, 120, 200))
        // 使用指定设置羽化掩码
        .GetFeathered(new FeatheringSettings() { Size = 3 })
        // 将掩码应用于图像
        .Apply();
        
    // 保存图像
    image.Save(outputFilePath);
}
```

### 另请参见

* interface [IImageMask](../iimagemask/)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


