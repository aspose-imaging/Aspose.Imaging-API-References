---
title: "ImageMask.Apply"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageMask 方法。将当前掩码应用于 RasterImage 源（如果存在）"
type: docs
weight: 70
url: /zh/net/aspose.imaging.magicwand.imagemasks/imagemask/apply/
---
## ImageMask.Apply method

将当前掩码应用于[`RasterImage`](../../../aspose.imaging/rasterimage/) 源（如果存在）。

```csharp
public void Apply()
```

### 异常

| 异常 | 条件 |
| --- | --- |
| NullReferenceException | 当源图像未定义时抛出。 |

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

### 另请参见

* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)


