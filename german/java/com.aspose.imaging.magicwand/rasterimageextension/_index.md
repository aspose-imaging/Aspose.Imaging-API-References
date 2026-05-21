---
title: "RasterImageExtension"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Klasse mit Masken-Erweiterungsmethoden für ."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Klasse mit Masken-Erweiterungsmethoden für [RasterImage](../../com.aspose.imaging/rasterimage).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Erstellt ein [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) mit einer Auswahl von Pixeln, deren Farben der Farbe des Referenzpunkts ähnlich sind, basierend auf [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Wendet [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) auf das [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Erstellt ein [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) mit einer Auswahl von Pixeln, deren Farben der Farbe des Referenzpunkts ähnlich sind, basierend auf [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbild, über dem der Algorithmus arbeiten soll. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Die Einstellungen, die zur Verarbeitung der Auswahl verwendet werden, enthalten den Referenzpunkt. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Wendet [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) auf das [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild, auf das die Maske angewendet wird. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | Die anzuwendende Maske. |

