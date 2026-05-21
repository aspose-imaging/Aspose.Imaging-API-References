---
title: "RasterImageExtension"
second_title: "Aspose.Imaging för Java API-referens"
description: "Klass med maskutökningmetoder för ."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Klass med maskutökningmetoder för [RasterImage](../../com.aspose.imaging/rasterimage).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Skapar en [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) med urval av pixlar med färger som liknar färgen på referenspunkten baserat på [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Tillämpar [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemmask) på [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Skapar en [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) med urval av pixlar med färger som liknar färgen på referenspunkten baserat på [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Rasterbild för algoritmen att arbeta på. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningarna som används för att bearbeta urvalet, inkluderar referenspunkten. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Tillämpar [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemmask) på [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild att applicera mask på. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | Masken som ska appliceras. |

