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

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Create a new mask using magic wand tool based on tone and color of pixel (120, 100) with custom threshold equal to 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Apply mask to the image
            .apply();

    // Save image with forced transparency color type option
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Create a new mask using magic wand tool based on tone and color of pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Union the existing mask with the specified one created by magic wand tool
            .union(new MagicWandSettings(416, 387))
            // Invert the existing mask
            .invert()
            // Subtract the specified mask created by magic wand tool with specified threshold from the existing one
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtract four specified rectangle masks from the existing mask one by one
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Feather mask with specified settings
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Apply mask to the image
            .apply();

    // Save image
    image.save(outputFilePath);
}

```

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

