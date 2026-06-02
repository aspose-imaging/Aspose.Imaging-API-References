---
title: "RasterImageExtension‑Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | Wendet [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) auf das [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) an. |
| [select_mask(source, settings)](#select_mask_source_settings_2) | Erstellt ein [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) mit einer Auswahl von Pixeln, deren Farben der Farbe des Referenzpunkts ähneln, basierend auf [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/). |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

Wendet [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) auf das [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bild, auf das die Maske angewendet wird. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | Die anzuwendende Maske. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

Erstellt ein [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) mit einer Auswahl von Pixeln, deren Farben der Farbe des Referenzpunkts ähneln, basierend auf [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbild, über dem der Algorithmus arbeitet. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Die Einstellungen, die zur Verarbeitung der Auswahl verwendet werden, enthalten den Referenzpunkt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


