---
title: "类 FeatheringSettings"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.MagicWand.ImageMasks.FeatheringSettings 类。一个羽化设置类"
type: docs
weight: 10850
url: /zh/net/aspose.imaging.magicwand.imagemasks/featheringsettings/
---
## FeatheringSettings class

一个羽化设置类。

```csharp
public class FeatheringSettings
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FeatheringSettings](featheringsettings/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Mode](../../aspose.imaging.magicwand.imagemasks/featheringsettings/mode/) { get; set; } | 获取或设置羽化算法模式。 |
| [Size](../../aspose.imaging.magicwand.imagemasks/featheringsettings/size/) { get; set; } | 获取或设置羽化尺寸。 |

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

* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../aspose.imaging.magicwand.imagemasks/)
* assembly [Aspose.Imaging](../../)


