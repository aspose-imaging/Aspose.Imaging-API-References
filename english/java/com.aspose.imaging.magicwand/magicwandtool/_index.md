---
title: MagicWandTool
second_title: Aspose.Imaging for Java API Reference
description: The class for magic wand algorithm main logic.
type: docs
weight: 14
url: /java/com.aspose.imaging.magicwand/magicwandtool/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader)
```
public class MagicWandTool implements IPartialArgb32PixelLoader
```

The class for magic wand algorithm main logic.
## Methods

| Method | Description |
| --- | --- |
| [select(RasterImage source, MagicWandSettings settings)](#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Creates a new [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) based on [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) and source [RasterImage](../../com.aspose.imaging/rasterimage). |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-) | Processes the loaded pixels . |
### select(RasterImage source, MagicWandSettings settings) {#select-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask select(RasterImage source, MagicWandSettings settings)
```


Creates a new [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) based on [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) and source [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster image for the algorithm to work over. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Settings of magic wand algorithm used in creating mask. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.imaging.Rectangle-int---com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public final void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Processes the loaded pixels .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The pixels rectangle. |
| pixels | int[] | The 32-bit ARGB pixels. |
| start | [Point](../../com.aspose.imaging/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.imaging/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

