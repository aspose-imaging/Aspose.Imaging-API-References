---
title: MagicWandTool Class
type: docs
weight: 100
url: /python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Processes the loaded pixels . |
| [select(source, settings)](#select_source_settings_2) | Creates a new [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) based on [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) and source [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Processes the loaded pixels .

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The pixels rectangle. |
| pixels | int[] | The 32-bit ARGB pixels. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Creates a new [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) based on [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) and source [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Raster image for the algorithm to work over. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Settings of magic wand algorithm used in creating mask. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | New [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


