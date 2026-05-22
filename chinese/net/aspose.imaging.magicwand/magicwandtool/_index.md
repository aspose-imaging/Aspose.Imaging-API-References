---
title: "类 MagicWandTool"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.MagicWand.MagicWandTool 类。用于魔棒算法主要逻辑的类"
type: docs
weight: 10930
url: /zh/net/aspose.imaging.magicwand/magicwandtool/
---
## MagicWandTool class

用于魔棒算法主逻辑的类。

```csharp
public class MagicWandTool : IPartialArgb32PixelLoader
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [Process](../../aspose.imaging.magicwand/magicwandtool/process/)(Rectangle, int[], Point, Point) | 处理已加载的像素。 |
| static [Select](../../aspose.imaging.magicwand/magicwandtool/select/)(RasterImage, MagicWandSettings) | 基于 [`MagicWandSettings`](../magicwandsettings/) 和源 [`RasterImage`](../../aspose.imaging/rasterimage/) 创建一个新的 [`ImageBitMask`](../../aspose.imaging.magicwand.imagemasks/imagebitmask/)。 |

## 示例

示例演示如何使用魔棒工具，根据任意像素的色调和颜色选择图像的简单区域。

```csharp
[C#]

var imageFilePath = "input.png"; 
using (RasterImage image = (RasterImage)Image.Load(inputFilePath))
{
    // 使用魔棒工具基于像素 (120, 100) 的色调和颜色创建新掩码，阈值自定义为 150
    MagicWandTool
        .Select(image, new MagicWandSettings(120, 100) { Threshold = 150 })
        // 将掩码应用于图像
        .Apply();

    // 使用强制透明颜色类型选项保存图像
    image.Save(outputFilePath, new ImageOptions.PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

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

* interface [IPartialArgb32PixelLoader](../../aspose.imaging/ipartialargb32pixelloader/)
* namespace [Aspose.Imaging.MagicWand](../../aspose.imaging.magicwand/)
* assembly [Aspose.Imaging](../../)


