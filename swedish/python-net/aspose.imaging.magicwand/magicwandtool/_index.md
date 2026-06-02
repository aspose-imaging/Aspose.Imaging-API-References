---
title: "MagicWandTool klass"
type: docs
weight: 100
url: /sv/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Bearbetar de inlästa pixlarna. |
| [select(source, settings)](#select_source_settings_2) | Skapar en ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) baserat på [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) och käll-[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Bearbetar de inlästa pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Pixelrektangeln. |
| pixlar | int[] | De 32-bitars ARGB-pixlarna. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Startpunkten för pixlarna. Om den inte är lika med (left,top) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Slutpunkten för pixlarna. Om den inte är lika med (right,bottom) betyder det att vi inte har en fullständig rektangel. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Skapar en ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) baserat på [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) och käll-[RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbild för algoritmen att arbeta på. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Inställningar för magisk stav-algoritmen som används vid skapande av mask. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Ny [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


