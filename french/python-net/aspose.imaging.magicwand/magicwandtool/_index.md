---
title: "Classe MagicWandTool"
type: docs
weight: 100
url: /fr/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Traite les pixels chargés. |
| [select(source, settings)](#select_source_settings_2) | Crée un nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basé sur [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) et l'[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) source. |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Traite les pixels chargés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle des pixels. |
| pixels | int[] | Les pixels ARGB 32 bits. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Le point de départ des pixels. S'il n'est pas égal à (left,top), cela signifie que nous n'avons pas de rectangle complet. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Le point final des pixels. S'il n'est pas égal à (right,bottom), cela signifie que nous n'avons pas de rectangle complet. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Crée un nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basé sur [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) et l'[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) source.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Image raster sur laquelle l'algorithme travaille. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Paramètres de l'algorithme baguette magique utilisés pour créer le masque. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Nouveau [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


