---
title: "RasterImageExtension"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe con metodi di estensione per maschere per ."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Classe con metodi di estensione per maschere per [RasterImage](../../com.aspose.imaging/rasterimage).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Crea un [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con la selezione di pixel con colori simili al colore del punto di riferimento basata su [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Applica [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) al [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Crea un [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) con la selezione di pixel con colori simili al colore del punto di riferimento basata su [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine raster su cui l'algoritmo deve operare. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Le impostazioni utilizzate per elaborare la selezione, includono il punto di riferimento. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Applica [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) al [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Immagine a cui applicare la maschera. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | La maschera da applicare. |

