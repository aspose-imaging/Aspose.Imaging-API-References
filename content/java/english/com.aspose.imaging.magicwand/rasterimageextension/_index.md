---
title: RasterImageExtension
second_title: Aspose.Imaging for Java API Reference
description: Class with masks extension methods for .
type: docs
weight: 15
url: /com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Class with masks extension methods for [RasterImage](../../com.aspose.imaging/rasterimage).
## Methods

| Method | Description |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Creates a [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) with selection of pixels with colors similar to the color of the reference point based on [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Applies [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) to the [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Creates a [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) with selection of pixels with colors similar to the color of the reference point based on [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster image for the algorithm to work over. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | The settings used to process the selection, includes the reference point. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Applies [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) to the [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image to apply mask to. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | The mask to be applied. |

