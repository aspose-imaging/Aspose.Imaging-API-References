---
title: RectangleMask
second_title: Aspose.Imaging for Java API Reference
description: Describes a rectangle mask.
type: docs
weight: 17
url: /com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Describes a rectangle mask.
## Constructors

| Constructor | Description |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Initializes a new instance of the [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) class with the specified left-top point, width and height. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Initializes a new instance of the [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) class with the specified rectangle. |
## Methods

| Method | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Gets the bounds of the selected part of the mask, in pixels. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Gets the opacity of the specified pixel. |
| [inflate(int size)](#inflate-int-) | Inflates this mask by the specified amount. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops mask with the specified rectangle. |
| [deepClone()](#deepClone--) | Creates a new object that is a copy of the current instance. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Initializes a new instance of the [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) class with the specified left-top point, width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the left-top point of the selected area. |
| y | int | The y-coordinate of the left-top point of the selected area. |
| width | int | Width of the selected area. |
| height | int | Height of the selected area. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Initializes a new instance of the [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) class with the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Selected area specified as a rectangle. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Gets the bounds of the selected part of the mask, in pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Gets the opacity of the specified pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
boolean - true if the specified pixel is opaque; otherwise, false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Inflates this mask by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The amount to inflate this mask. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Crops mask with the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The specified rectangle. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Creates a new object that is a copy of the current instance.

**Returns:**
java.lang.Object - A new object that is a copy of this instance.
