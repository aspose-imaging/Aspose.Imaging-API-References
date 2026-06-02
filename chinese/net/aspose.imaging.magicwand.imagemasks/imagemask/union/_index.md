---
title: "ImageMask.Union"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageMask 方法。获取当前掩码与提供的掩码的并集"
type: docs
weight: 200
url: /zh/net/aspose.imaging.magicwand.imagemasks/imagemask/union/
---
## Union(ImageMask) {#union}

获取当前掩码与提供的掩码的并集。

```csharp
public ImageBitMask Union(ImageMask mask)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 掩码 | ImageMask | 提供的掩码 |

### 返回值

新建 [`ImageBitMask`](../../imagebitmask/)。

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

* class [ImageBitMask](../../imagebitmask/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)

---

## Union(MagicWandSettings) {#union_1}

获取当前掩码与对掩码源应用魔棒选择的结果的并集。

```csharp
public ImageBitMask Union(MagicWandSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设置 | MagicWandSettings | 魔棒设置。 |

### 返回值

新建 [`ImageBitMask`](../../imagebitmask/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当掩码中未定义源图像时抛出。 |

### 另请参见

* class [ImageBitMask](../../imagebitmask/)
* class [MagicWandSettings](../../../aspose.imaging.magicwand/magicwandsettings/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)

---

## Union(RasterImage, MagicWandSettings) {#union_2}

获取当前掩码与对提供的图像应用魔棒选择的结果的并集。

```csharp
public ImageBitMask Union(RasterImage image, MagicWandSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于魔棒的图像。 |
| 设置 | MagicWandSettings | 魔棒设置。 |

### 返回值

新建 [`ImageBitMask`](../../imagebitmask/)。

### 另请参见

* class [ImageBitMask](../../imagebitmask/)
* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [MagicWandSettings](../../../aspose.imaging.magicwand/magicwandsettings/)
* class [ImageMask](../)
* namespace [Aspose.Imaging.MagicWand.ImageMasks](../../imagemask/)
* assembly [Aspose.Imaging](../../../)


