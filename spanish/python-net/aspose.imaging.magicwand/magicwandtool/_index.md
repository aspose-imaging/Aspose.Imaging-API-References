---
title: "Clase MagicWandTool"
type: docs
weight: 100
url: /es/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Procesa los píxeles cargados. |
| [select(source, settings)](#select_source_settings_2) | Crea una nueva [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basada en [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) y en el [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) de origen. |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Procesa los píxeles cargados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | El rectángulo de píxeles. |
| píxeles | int[] | Los píxeles ARGB de 32 bits. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | El punto de píxeles inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | El punto de píxeles final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Crea una nueva [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basada en [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) y en el [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) de origen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Imagen raster para que el algoritmo funcione. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Configuración del algoritmo varita mágica usado para crear la máscara. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuevo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


