---
title: "MagicWandTool Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Verarbeitet die geladenen Pixel. |
| [select(source, settings)](#select_source_settings_2) | Erstellt eine neue [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basierend auf [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) und dem Quell-[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Verarbeitet die geladenen Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Das Pixelrechteck. |
| Pixel | int[] | Die 32‑Bit‑ARGB‑Pixel. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Der Startpixelpunkt. Wenn er nicht gleich (left,top) ist, bedeutet das, dass es kein vollständiges Rechteck ist. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Der Endpixelpunkt. Wenn er nicht gleich (right,bottom) ist, bedeutet das, dass es kein vollständiges Rechteck ist. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Erstellt eine neue [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) basierend auf [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) und dem Quell-[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbild, über dem der Algorithmus arbeitet. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Einstellungen des Magic‑Wand‑Algorithmus, die beim Erstellen der Maske verwendet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Neu [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


