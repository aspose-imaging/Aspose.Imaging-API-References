---
title: "Classe MagicWandTool"
type: docs
weight: 100
url: /it/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Elabora i pixel caricati. |
| [select(source, settings)](#select_source_settings_2) | Crea una nuova [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basata su [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) e sulla [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Elabora i pixel caricati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei pixel. |
| pixel | int[] | I pixel ARGB a 32 bit. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Il punto di inizio dei pixel. Se non è uguale a (left,top) significa che non è un rettangolo completo. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Il punto finale dei pixel. Se non è uguale a (right,bottom) significa che non è un rettangolo completo. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Crea una nuova [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basata su [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) e sulla [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Immagine raster su cui l'algoritmo deve operare. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Impostazioni dell'algoritmo magic wand utilizzate per creare la maschera. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nuovo [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


