---
title: "RasterImageExtension"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe avec des méthodes d'extension de masques pour ."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Classe avec des méthodes d'extension de masques pour [RasterImage](../../com.aspose.imaging/rasterimage).
## Méthodes

| Méthode | Description |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Crée un [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) avec une sélection de pixels dont les couleurs sont similaires à la couleur du point de référence basée sur [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Applique [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) au [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Crée un [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) avec une sélection de pixels dont les couleurs sont similaires à la couleur du point de référence basée sur [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Image raster sur laquelle l'algorithme doit travailler. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Les paramètres utilisés pour traiter la sélection, incluent le point de référence. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Applique [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) au [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image à laquelle appliquer le masque. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | Le masque à appliquer. |

