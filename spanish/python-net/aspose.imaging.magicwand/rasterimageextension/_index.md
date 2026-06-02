---
title: "Clase RasterImageExtension"
type: docs
weight: 110
url: /es/python-net/aspose.imaging.magicwand/rasterimageextension/
---

**Summary:** Class with masks extension methods for [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.RasterImageExtension

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [apply_mask(image, mask)](#apply_mask_image_mask_1) | Aplica [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) a la [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [select_mask(source, settings)](#select_mask_source_settings_2) | Crea una [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) con la selección de píxeles con colores similares al color del punto de referencia basado en [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/). |


### Method: apply_mask(image, mask)  [static] {#apply_mask_image_mask_1}


```
 apply_mask(image, mask) 
```

Aplica [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) a la [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen a la que aplicar la máscara. |
| mask | [IImageMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/iimagemask/) | La máscara a aplicar. |

### Method: select_mask(source, settings)  [static] {#select_mask_source_settings_2}


```
 select_mask(source, settings) 
```

Crea una [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) con la selección de píxeles con colores similares al color del punto de referencia basado en [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen raster para que el algoritmo funcione. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Los ajustes utilizados para procesar la selección, incluyen el punto de referencia. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


