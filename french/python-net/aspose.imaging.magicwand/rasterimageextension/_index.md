---
title: "Classe RasterImageExtension"
type: docs
weight: 110
url: /fr/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | Applique [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) à [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [select_mask(source, settings)](#select_mask_source_settings_2) | Crée un [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) avec une sélection de pixels dont les couleurs sont similaires à la couleur du point de référence, basée sur [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/). |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

Applique [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) à [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image à laquelle appliquer le masque. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | Le masque à appliquer. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

Crée un [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) avec une sélection de pixels dont les couleurs sont similaires à la couleur du point de référence, basée sur [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image raster sur laquelle l'algorithme travaille. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Les paramètres utilisés pour traiter la sélection, incluant le point de référence. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


