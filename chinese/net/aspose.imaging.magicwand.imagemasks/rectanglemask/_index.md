---
title: "类 RectangleMask"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.MagicWand.ImageMasks.RectangleMask 类。描述矩形遮罩"
type: docs
weight: 10900
url: /zh/net/aspose.imaging.magicwand.imagemasks/rectanglemask/
---
## RectangleMask class

描述矩形掩码。

```csharp
public class RectangleMask : ImageMask
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RectangleMask](rectanglemask/#constructor)(Rectangle) | 使用指定的矩形初始化 `RectangleMask` 类的新实例。 |
| [RectangleMask](rectanglemask/#constructor_1)(int, int, int, int) | 使用指定的左上点、宽度和高度初始化 `RectangleMask` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagemask/bounds/) { get; } | 获取此掩码的边界（以像素为单位）。 |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagemask/height/) { get; } | 获取此掩码的高度（以像素为单位）。 |
| override [Item](../../aspose.imaging.magicwand.imagemasks/rectanglemask/item/) { get; } | 获取指定像素的透明度。 |
| override [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/rectanglemask/selectionbounds/) { get; } | 获取掩码选定部分的边界（以像素为单位）。 |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagemask/source/) { get; } | 获取用于创建此掩码的源图像（如果存在）。 |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagemask/width/) { get; } | 获取此掩码的宽度（以像素为单位）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagemask/apply/)() | 如果存在，将当前遮罩应用于 [`RasterImage`](../../aspose.imaging/rasterimage/) 源。 |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagemask/applyto/)(RasterImage) | 将当前遮罩应用于指定的 [`RasterImage`](../../aspose.imaging/rasterimage/)。 |
| override [Clone](../../aspose.imaging.magicwand.imagemasks/rectanglemask/clone/)() | 创建一个新对象，该对象是当前实例的副本。 |
| override [Crop](../../aspose.imaging.magicwand.imagemasks/rectanglemask/crop/#crop)(Rectangle) | 使用指定的矩形裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/)(Size) | 使用指定的尺寸裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/)(int, int) | 使用指定的宽度和高度裁剪遮罩。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(ImageMask) | 获取当前遮罩与提供的遮罩的异或。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(MagicWandSettings) | 获取当前遮罩与对遮罩源应用魔棒选择后的结果的异或。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(RasterImage, MagicWandSettings) | 获取当前遮罩与对提供的图像应用魔棒选择后的结果的异或。 |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagemask/getbyteopacity/)(int, int) | 获取指定像素的透明度，精确到字节。 |
| [GetFeathered](../../aspose.imaging.magicwand.imagemasks/imagemask/getfeathered/)(FeatheringSettings) | 获取使用指定设置羽化边界的灰度遮罩。 |
| override [Inflate](../../aspose.imaging.magicwand.imagemasks/rectanglemask/inflate/)(int) | 按指定量膨胀此遮罩。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/)(ImageMask) | 获取当前遮罩与提供的遮罩的交集。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/)(MagicWandSettings) | 获取当前遮罩与对遮罩源应用魔棒选择结果的交集。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagemask/intersect/)(RasterImage, MagicWandSettings) | 获取当前掩码与对提供的图像应用魔棒选择的结果的交集。 |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagemask/invert/)() | 获取当前掩码的反转。 |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagemask/isopaque/)(int, int) | 检查指定像素是否不透明。 |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagemask/istransparent/)(int, int) | 检查指定像素是否透明。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/)(ImageMask) | 获取当前掩码减去提供的掩码的结果。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/)(MagicWandSettings) | 获取对当前掩码源应用魔棒选择的结果，并从掩码中减去该结果。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagemask/subtract/)(RasterImage, MagicWandSettings) | 获取对提供的图像应用魔棒选择的结果，并从当前掩码中减去该结果。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/)(ImageMask) | 获取当前掩码与提供的掩码的并集。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/)(MagicWandSettings) | 获取当前掩码与对掩码源应用魔棒选择的结果的并集。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagemask/union/)(RasterImage, MagicWandSettings) | 获取当前掩码与对提供的图像应用魔棒选择的结果的并集。 |

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

* class [ImageMask](../imagemask/)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


