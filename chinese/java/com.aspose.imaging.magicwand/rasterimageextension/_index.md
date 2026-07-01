---
title: "RasterImageExtension"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于 . 的掩码扩展方法类。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

用于 [RasterImage](../../com.aspose.imaging/rasterimage) 的掩码扩展方法类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | 基于 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings)，创建一个 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)，用于选择颜色与参考点颜色相似的像素。 |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | 将 [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) 应用于 [RasterImage](../../com.aspose.imaging/rasterimage)。 |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


基于 [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings)，创建一个 [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)，用于选择颜色与参考点颜色相似的像素。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | 用于算法处理的光栅图像。 |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | 用于处理选区的设置，包括参考点。 |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


将 [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) 应用于 [RasterImage](../../com.aspose.imaging/rasterimage)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | 要应用掩码的图像。 |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | 要应用的掩码。 |

