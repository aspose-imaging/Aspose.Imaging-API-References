---
title: "MagicWandTool"
second_title: "Aspose.Imaging for Java API 参考"
description: "Magic Wand 算法主逻辑的类。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

Magic Wand 算法主逻辑的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | 创建一个基于 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 和源 [RasterImage](../../com.aspose.imaging/rasterimage) 的新 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)。 |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | 处理已加载的像素。 |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // 使用魔棒工具基于像素 (120, 100) 的色调和颜色创建新掩码，自定义阈值设为 150。
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // 将掩码应用于图像
            .apply();

    // 使用强制透明颜色类型选项保存图像
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // 使用魔棒工具基于像素 (845, 128) 的色调和颜色创建新掩码
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // 将现有掩码与魔棒工具创建的指定掩码进行合并
            .union(new MagicWandSettings(416, 387))
            // 反转现有的遮罩
            .invert()
            // 从现有遮罩中减去使用魔棒工具并具有指定阈值创建的指定遮罩
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // 一次一次地从现有遮罩中减去四个指定的矩形遮罩
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // 使用指定设置羽化遮罩
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // 将掩码应用于图像
            .apply();

    // 保存图像
    image.save(outputFilePath);
}

```

### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


创建一个基于 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) 和源 [RasterImage](../../com.aspose.imaging/rasterimage) 的新 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于算法处理的光栅图像。 |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | 用于创建遮罩的魔棒算法设置。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


处理已加载的像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 像素矩形。 |
| 像素 | int[] | 32 位 ARGB 像素。 |
| start | [Point](../../com.aspose.imaging/point) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](../../com.aspose.imaging/point) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

