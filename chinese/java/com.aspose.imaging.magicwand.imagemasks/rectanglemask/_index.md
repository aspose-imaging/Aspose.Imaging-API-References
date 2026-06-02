---
title: "RectangleMask"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "描述矩形掩码。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

描述矩形掩码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | 使用指定的左上点、宽度和高度初始化 [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) 类的新实例。 |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | 使用指定的矩形初始化 [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | 获取掩码选定部分的边界（以像素为单位）。 |
| [get_Item(int x, int y)](#get-Item-int-int-) | 获取指定像素的透明度。 |
| [inflate(int size)](#inflate-int-) | 按指定量膨胀此掩码。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用指定的矩形裁剪掩码。 |
| [deepClone()](#deepClone--) | 创建一个新对象，该对象是当前实例的副本。 |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // 使用魔棒工具基于像素 (845, 128) 的色调和颜色创建新掩码
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // 将现有掩码与由魔棒工具创建的指定掩码合并
            .union(new MagicWandSettings(416, 387))
            // 反转现有掩码
            .invert()
            // 从现有掩码中减去由魔棒工具创建的、具有指定阈值的指定掩码
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // 逐个从现有掩码中减去四个指定的矩形掩码
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // 使用指定设置羽化掩码
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // 将掩码应用于图像
            .apply();

    // 保存图像
    image.save(outputFilePath);
}

```

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


使用指定的左上点、宽度和高度初始化 [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 所选区域左上点的 X 坐标。 |
| y | int | 所选区域左上点的 Y 坐标。 |
| 宽度 | int | 所选区域的宽度。 |
| 高度 | int | 所选区域的高度。 |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


使用指定的矩形初始化 [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | 选定区域以矩形形式指定。 |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


获取掩码选定部分的边界（以像素为单位）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


获取指定像素的透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
boolean - 如果指定像素不透明则为 true；否则为 false。
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


按指定量膨胀此掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 大小 | int | 用于膨胀此掩码的量。 |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


使用指定的矩形裁剪掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 指定的矩形。 |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建一个新对象，该对象是当前实例的副本。

**Returns:**
java.lang.Object - 此实例的副本的新对象。
