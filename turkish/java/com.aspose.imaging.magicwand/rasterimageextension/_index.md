---
title: "RasterImageExtension"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Maske uzantı metodlarına sahip sınıf ."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Maske uzantı metodlarına sahip sınıf [RasterImage](../../com.aspose.imaging/rasterimage).
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Referans noktasının rengine benzer renklere sahip pikselleri seçerek bir [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) oluşturur, [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) temelinde. |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) [RasterImage](../../com.aspose.imaging/rasterimage) üzerine uygular. |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Referans noktasının rengine benzer renklere sahip pikselleri seçerek bir [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) oluşturur, [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) temelinde.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Algoritmanın çalışacağı raster görüntü. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Seçimi işlemek için kullanılan ayarlar, referans noktasını içerir. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


[IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) [RasterImage](../../com.aspose.imaging/rasterimage) üzerine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Maskenin uygulanacağı görüntü. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | Uygulanacak maske. |

