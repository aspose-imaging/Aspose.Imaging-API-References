---
title: "RasterImageExtension klass"
type: docs
weight: 110
url: /sv/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | Tillämpar [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) på [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [select_mask(source, settings)](#select_mask_source_settings_2) | Skapar en [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) med urval av pixlar vars färger liknar färgen på referenspunkten baserat på [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/). |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

Tillämpar [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) på [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild att applicera masken på. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | Masken som ska tillämpas. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

Skapar en [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) med urval av pixlar vars färger liknar färgen på referenspunkten baserat på [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbild för algoritmen att arbeta på. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningarna som används för att bearbeta urvalet, inkluderar referenspunkten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


