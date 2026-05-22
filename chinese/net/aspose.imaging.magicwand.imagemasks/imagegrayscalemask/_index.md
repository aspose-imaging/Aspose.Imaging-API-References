---
title: "类 ImageGrayscaleMask"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.MagicWand.ImageMasks.ImageGrayscaleMask 类。描述灰度图像遮罩"
type: docs
weight: 10880
url: /zh/net/aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
## ImageGrayscaleMask class

描述灰度图像掩码。

```csharp
public class ImageGrayscaleMask : IImageMask
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageGrayscaleMask](imagegrayscalemask/#constructor)(RasterImage) | 使用指定的现有[`RasterImage`](../../aspose.imaging/rasterimage/)的尺寸初始化 `ImageGrayscaleMask` 类的新实例。指定的[`RasterImage`](../../aspose.imaging/rasterimage/)将被存储为源图像。 |
| [ImageGrayscaleMask](imagegrayscalemask/#constructor_1)(int, int) | 使用指定的宽度和高度初始化 `ImageGrayscaleMask` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/bounds/) { get; } | 获取此掩码的边界（以像素为单位）。 |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/height/) { get; } | 获取此掩码的高度（以像素为单位）。 |
| [Item](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/item/) { get; set; } | 获取或设置指定像素的不透明度。 |
| [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/selectionbounds/) { get; } | 获取掩码选定部分的边界（以像素为单位）。 |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/source/) { get; } | 获取用于创建此掩码的源图像（如果存在）。 |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/width/) { get; } | 获取此掩码的宽度（以像素为单位）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/apply/)() | 如果存在，将当前遮罩应用于 [`RasterImage`](../../aspose.imaging/rasterimage/) 源。 |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/applyto/)(RasterImage) | 将当前遮罩应用于指定的 [`RasterImage`](../../aspose.imaging/rasterimage/)。 |
| [Clone](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/clone/)() | 创建一个新对象，该对象是当前实例的副本。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop)(Rectangle) | 使用指定的矩形裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop_1)(Size) | 使用指定的尺寸裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/crop/#crop_2)(int, int) | 使用指定的宽度和高度裁剪遮罩。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/exclusivedisjunction/)(ImageGrayscaleMask) | 获取当前遮罩与提供的遮罩的异或。 |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/getbyteopacity/)(int, int) | 获取指定像素的透明度，精确到字节。 |
| [Intersect](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/intersect/)(ImageGrayscaleMask) | 获取当前遮罩与提供的遮罩的交集。 |
| [Invert](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/invert/)() | 获取当前掩码的反转。 |
| [IsOpaque](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/isopaque/)(int, int) | 检查指定像素是否不透明。 |
| [IsTransparent](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/istransparent/)(int, int) | 检查指定像素是否透明。 |
| [Subtract](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/subtract/)(ImageGrayscaleMask) | 获取当前掩码减去提供的掩码的结果。 |
| [Union](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/union/)(ImageGrayscaleMask) | 两个掩码的并集。 |
| [operator +](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_addition/) | 两个掩码的并集。 |
| [operator ^](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_exclusiveor/) | 两个掩码的异或。 |
| [operator !](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_logicalnot/) | 反转掩码。 |
| [operator *](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_multiply/) | 两个掩码的交集。 |
| [operator -](../../aspose.imaging.magicwand.imagemasks/imagegrayscalemask/op_subtraction/) | 从第一个掩码中减去第二个掩码。 |

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


