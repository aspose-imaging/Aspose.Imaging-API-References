---
title: "类 CircleMask"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.MagicWand.ImageMasks.CircleMask 类。描述圆形遮罩。"
type: docs
weight: 10820
url: /zh/net/aspose.imaging.magicwand.imagemasks/circlemask/
---
## CircleMask class

描述圆形掩码。

```csharp
public class CircleMask : ImageMask
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CircleMask](circlemask/#constructor)(Point, int) | 使用指定的中心点和半径初始化 `CircleMask` 类的新实例。 |
| [CircleMask](circlemask/#constructor_1)(int, int, int) | 使用指定的中心点和半径初始化 `CircleMask` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bounds](../../aspose.imaging.magicwand.imagemasks/imagemask/bounds/) { get; } | 获取此掩码的边界（以像素为单位）。 |
| [Height](../../aspose.imaging.magicwand.imagemasks/imagemask/height/) { get; } | 获取此掩码的高度（以像素为单位）。 |
| override [Item](../../aspose.imaging.magicwand.imagemasks/circlemask/item/) { get; } | 获取指定像素的透明度。 |
| override [SelectionBounds](../../aspose.imaging.magicwand.imagemasks/circlemask/selectionbounds/) { get; } | 获取此掩码的边界（以像素为单位）。 |
| [Source](../../aspose.imaging.magicwand.imagemasks/imagemask/source/) { get; } | 获取用于创建此掩码的源图像（如果存在）。 |
| [Width](../../aspose.imaging.magicwand.imagemasks/imagemask/width/) { get; } | 获取此掩码的宽度（以像素为单位）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Apply](../../aspose.imaging.magicwand.imagemasks/imagemask/apply/)() | 如果存在，将当前遮罩应用于 [`RasterImage`](../../aspose.imaging/rasterimage/) 源。 |
| [ApplyTo](../../aspose.imaging.magicwand.imagemasks/imagemask/applyto/)(RasterImage) | 将当前遮罩应用于指定的 [`RasterImage`](../../aspose.imaging/rasterimage/)。 |
| override [Clone](../../aspose.imaging.magicwand.imagemasks/circlemask/clone/)() | 创建一个新对象，该对象是当前实例的副本。 |
| override [Crop](../../aspose.imaging.magicwand.imagemasks/circlemask/crop/#crop)(Rectangle) | 使用指定的矩形裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/)(Size) | 使用指定的尺寸裁剪遮罩。 |
| [Crop](../../aspose.imaging.magicwand.imagemasks/imagemask/crop/)(int, int) | 使用指定的宽度和高度裁剪遮罩。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(ImageMask) | 获取当前遮罩与提供的遮罩的异或。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(MagicWandSettings) | 获取当前遮罩与对遮罩源应用魔棒选择后的结果的异或。 |
| [ExclusiveDisjunction](../../aspose.imaging.magicwand.imagemasks/imagemask/exclusivedisjunction/)(RasterImage, MagicWandSettings) | 获取当前遮罩与对提供的图像应用魔棒选择后的结果的异或。 |
| [GetByteOpacity](../../aspose.imaging.magicwand.imagemasks/imagemask/getbyteopacity/)(int, int) | 获取指定像素的透明度，精确到字节。 |
| [GetFeathered](../../aspose.imaging.magicwand.imagemasks/imagemask/getfeathered/)(FeatheringSettings) | 获取使用指定设置羽化边界的灰度遮罩。 |
| override [Inflate](../../aspose.imaging.magicwand.imagemasks/circlemask/inflate/)(int) | 按指定量膨胀此遮罩。 |
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

### 另请参见

* class [ImageMask](../imagemask/)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


