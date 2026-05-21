---
title: "ImageGrayscaleMask"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "描述灰度图像掩码。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

描述灰度图像掩码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | 使用指定的宽度和高度初始化 [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) 类的新实例。 |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | 使用指定的现有 [RasterImage](../../com.aspose.imaging/rasterimage) 的尺寸初始化 [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSource()](#getSource--) | 获取用于创建此掩码的源图像（如果存在）。 |
| [getWidth()](#getWidth--) | 获取此掩码的宽度（以像素为单位）。 |
| [getHeight()](#getHeight--) | 获取此掩码的高度（以像素为单位）。 |
| [getBounds()](#getBounds--) | 获取此掩码的边界（以像素为单位）。 |
| [getSelectionBounds()](#getSelectionBounds--) | 获取掩码选定部分的边界（以像素为单位）。 |
| [get_Item(int x, int y)](#get-Item-int-int-) | 获取指定像素的透明度。 |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | 设置指定像素的透明度。 |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | 检查指定像素是否不透明。 |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | 检查指定像素是否透明。 |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | 获取指定像素的透明度，精确到字节。 |
| [deepClone()](#deepClone--) | 创建一个新对象，该对象是当前实例的副本。 |
| [apply()](#apply--) | 如果存在，则将当前掩码应用于 [RasterImage](../../com.aspose.imaging/rasterimage) 源。 |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | 将当前掩码应用于指定的 [RasterImage](../../com.aspose.imaging/rasterimage)。 |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | 使用指定的尺寸裁剪掩码。 |
| [crop(int width, int height)](#crop-int-int-) | 使用指定的宽度和高度裁剪掩码。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用指定的矩形裁剪掩码。 |
| [invert()](#invert--) | 获取当前掩码的反转。 |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 两个掩码的并集。 |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 获取从当前掩码中减去提供的掩码的结果。 |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 获取当前掩码与提供的掩码的交集。 |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 获取当前掩码与提供的掩码的异或。 |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 反转掩码。 |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 两个掩码的并集。 |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 从第一个掩码中减去第二个掩码。 |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 两个掩码的交集。 |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | 两个掩码的异或。 |

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

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


使用指定的宽度和高度初始化 [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 掩码的宽度。 |
| 高度 | int | 掩码的高度。 |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


使用指定的现有 [RasterImage](../../com.aspose.imaging/rasterimage) 的尺寸初始化 [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) 类的新实例。指定的 [RasterImage](../../com.aspose.imaging/rasterimage) 将被存储为源图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 源图像。 |

### getSource() {#getSource--}
```
public final RasterImage getSource()
```


获取用于创建此掩码的源图像（如果存在）。

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取此掩码的宽度（以像素为单位）。

**Returns:**
int - 此掩码的宽度（以像素为单位）。
### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取此掩码的高度（以像素为单位）。

**Returns:**
int - 此掩码的高度（以像素为单位）。
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


获取此掩码的边界（以像素为单位）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


获取掩码选定部分的边界（以像素为单位）。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


获取指定像素的透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 Y 坐标。取值：字节值；透明时为 0；不透明时为 255。 |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


设置指定像素的透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 Y 坐标。取值：字节值；透明时为 0；不透明时为 255。 |
| value | byte | 指定像素的透明度。 |

### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


检查指定像素是否不透明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
boolean - 如果指定像素不透明则为 true；否则为 false。
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


检查指定像素是否透明。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
boolean - 如果指定像素透明则为 true；否则为 false。
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


获取指定像素的透明度，精确到字节。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |

**Returns:**
byte - 字节值，表示指定像素的透明度。
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


创建一个新对象，该对象是当前实例的副本。

**Returns:**
java.lang.Object - 此实例的副本的新对象。
### apply() {#apply--}
```
public final void apply()
```


如果存在，则将当前掩码应用于 [RasterImage](../../com.aspose.imaging/rasterimage) 源。

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


将当前掩码应用于指定的 [RasterImage](../../com.aspose.imaging/rasterimage)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 要应用掩码的图像。 |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


使用指定的尺寸裁剪掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | 指定的大小。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


使用指定的宽度和高度裁剪掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 指定的宽度。 |
| 高度 | int | 指定的高度。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


使用指定的矩形裁剪掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | 指定的矩形。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


获取当前掩码的反转。

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


两个掩码的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 提供的掩码 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


获取从当前掩码中减去提供的掩码的结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 提供的掩码 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


获取当前掩码与提供的掩码的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 提供的掩码 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


获取当前掩码与提供的掩码的异或。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 提供的掩码 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


反转掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 待反转的掩码。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


两个掩码的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第一个掩码。 |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第二个掩码。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


从第一个掩码中减去第二个掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第一个掩码。 |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第二个掩码。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


两个掩码的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第一个掩码。 |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第二个掩码。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


两个掩码的异或。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第一个掩码。 |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | 第二个掩码。 |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
