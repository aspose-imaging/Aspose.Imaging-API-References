---
title: "RasterImageExtension"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة مع طرق توسيع الأقنعة لـ ."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

فئة مع طرق توسيع الأقنعة لـ [RasterImage](../../com.aspose.imaging/rasterimage).
## الطرق

| طريقة | الوصف |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | ينشئ [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) مع اختيار البكسلات ذات الألوان المشابهة للون نقطة الإشارة بناءً على [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | يطبق [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemmask) على [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


ينشئ [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) مع اختيار البكسلات ذات الألوان المشابهة للون نقطة الإشارة بناءً على [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة نقطية لتعمل الخوارزمية عليها. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | الإعدادات المستخدمة لمعالجة الاختيار، تشمل نقطة الإشارة. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


يطبق [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemmask) على [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيُطبق عليها القناع. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | القناع الذي سيُطبق. |

