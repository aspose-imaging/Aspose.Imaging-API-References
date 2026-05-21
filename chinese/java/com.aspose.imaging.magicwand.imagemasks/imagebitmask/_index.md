---
title: "ImageBitMask"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "描述二值图像掩码。"
type: docs
weight: 14
url: /zh/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

描述二值图像掩码。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | 使用指定的宽度和高度初始化 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) 类的新实例。 |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | 使用指定的现有 [RasterImage](../../com.aspose.imaging/rasterimage) 的尺寸初始化 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | 获取掩码选定部分的边界（以像素为单位）。 |
| [get_Item(int x, int y)](#get-Item-int-int-) | 获取指定像素的透明度。 |
| [inflate(int size)](#inflate-int-) | 按指定量膨胀此掩码。 |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | 使用指定的矩形裁剪掩码。 |
| [deepClone()](#deepClone--) | 创建一个新对象，该对象是当前实例的副本。 |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | 设置指定像素的透明度。 |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | 反转掩码。 |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | 两个掩码的并集。 |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | 从第一个掩码中减去第二个掩码。 |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | 两个掩码的交集。 |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | 两个掩码的异或。 |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


使用指定的宽度和高度初始化 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | int | 掩码的宽度。 |
| 高度 | int | 掩码的高度。 |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


初始化一个新的 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) 类实例，大小为指定的现有 [RasterImage](../../com.aspose.imaging/rasterimage)。指定的 [RasterImage](../../com.aspose.imaging/rasterimage) 将被存储为源图像。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 源图像。 |

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
| y | int | 像素的 y 坐标。值：如果指定像素是不透明的则为 true；否则为 false。 |

**Returns:**
boolean
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


创建一个新对象，该对象是当前实例的副本。

**Returns:**
java.lang.Object - 此实例的副本的新对象。
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


设置指定像素的透明度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | int | 像素的 x 坐标。 |
| y | int | 像素的 y 坐标。 |
| value | boolean | 如果指定像素是不透明的则为 true；否则为 false。 |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


反转掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 待反转的掩码。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


两个掩码的并集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第一个掩码。 |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第二个掩码。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


从第一个掩码中减去第二个掩码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第一个掩码。 |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第二个掩码。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


两个掩码的交集。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第一个掩码。 |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第二个掩码。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


两个掩码的异或。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第一个掩码。 |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | 第二个掩码。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
