---
title: ImageMask
second_title: Aspose.Imaging for Java API Reference
description: Describes a binary image mask.
type: docs
weight: 16
url: /java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

Describes a binary image mask.
## Methods

| Method | Description |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Casting `mask` to a [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask). |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Inverts mask. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Union of two masks. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Subtract second mask from first. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Intersection of two masks. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Exclusive disjunction of two masks. |
| [getSource()](#getSource--) | Gets the source image used to create this mask, if exists. |
| [getWidth()](#getWidth--) | Gets the width, in pixels, of this mask. |
| [getHeight()](#getHeight--) | Gets the height, in pixels, of this mask. |
| [getBounds()](#getBounds--) | Gets the bounds, in pixels, of this mask. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Gets the opacity of the specified pixel. |
| [inflate(int size)](#inflate-int-) | Inflates this mask by the specified amount. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Crops mask with the specified size. |
| [crop(int width, int height)](#crop-int-int-) | Crops mask with the specified width and height. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Crops mask with the specified rectangle. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Checks if the specified pixel is opaque. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Checks if the specified pixel is transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Gets the opacity of the specified pixel with byte precision. |
| [getFeathered()](#getFeathered--) | Gets grayscale mask with the border feathered with the default settings. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | Gets grayscale mask with the border feathered with the specified settings. |
| [apply()](#apply--) | Applies current mask to the [RasterImage](../../com.aspose.imaging/rasterimage) source, if exists. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Applies current mask to the specified [RasterImage](../../com.aspose.imaging/rasterimage). |
| [invert()](#invert--) | Gets the inversion of the current mask. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Gets the union of the current mask with provided. |
| [union()](#union--) | Gets the union of the current mask with the result of magic wand selection applied to the source of the mask. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the union of the current mask with the result of magic wand selection applied to the source of the mask. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | Gets the union of the current mask with the result of magic wand selection applied to the provided image. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the union of the current mask with the result of magic wand selection applied to the provided image. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Gets the subtraction of the provided mask from current. |
| [subtract()](#subtract--) | Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | Gets the result of magic wand selection applied to the provided image subtracted from the current mask. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the result of magic wand selection applied to the provided image subtracted from the current mask. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Gets the intersection of current mask with provided. |
| [intersect()](#intersect--) | Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | Gets the intersection of the current mask with the result of magic wand selection applied to the provided image. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the intersection of the current mask with the result of magic wand selection applied to the provided image. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Gets the exclusive disjunction of current mask with provided. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image. |

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

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


Casting `mask` to a [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The mask value. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


Inverts mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The mask to be inverted. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


Union of two masks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The first mask. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The second mask. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


Subtract second mask from first.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The first mask. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The second mask. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


Intersection of two masks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The first mask. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The second mask. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


Exclusive disjunction of two masks.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The first mask. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | The second mask. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Gets the source image used to create this mask, if exists.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets the width, in pixels, of this mask.

**Returns:**
int - the width, in pixels, of this mask.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets the height, in pixels, of this mask.

**Returns:**
int - the height, in pixels, of this mask.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Gets the bounds, in pixels, of this mask.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
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
public abstract ImageMask inflate(int size)
```


Inflates this mask by the specified amount.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | int | The amount to inflate this mask. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


Crops mask with the specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | The specified size. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


Crops mask with the specified width and height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | The specified width. |
| height | int | The specified height. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


Crops mask with the specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | The specified rectangle. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


Checks if the specified pixel is opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
boolean - true if the specified pixel is opaque; otherwise, false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


Checks if the specified pixel is transparent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
boolean - true if the specified pixel is transparent; otherwise, false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


Gets the opacity of the specified pixel with byte precision.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns:**
byte - Byte value, representing the opacity of the specified pixel.
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


Gets grayscale mask with the border feathered with the default settings.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


Gets grayscale mask with the border feathered with the specified settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | Feathering settings. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


Applies current mask to the [RasterImage](../../com.aspose.imaging/rasterimage) source, if exists.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

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

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Applies current mask to the specified [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image to apply mask to. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


Gets the inversion of the current mask.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

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

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


Gets the union of the current mask with provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Provided mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


Gets the union of the current mask with the result of magic wand selection applied to the source of the mask.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


Gets the union of the current mask with the result of magic wand selection applied to the source of the mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


Gets the union of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


Gets the union of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


Gets the subtraction of the provided mask from current.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Provided mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


Gets the result of magic wand selection applied to the source of the current mask subtracted from the mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


Gets the result of magic wand selection applied to the provided image subtracted from the current mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


Gets the result of magic wand selection applied to the provided image subtracted from the current mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


Gets the intersection of current mask with provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Provided mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


Gets the intersection of the current mask with the result of magic wand selection applied to the source of the mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


Gets the intersection of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


Gets the intersection of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


Gets the exclusive disjunction of current mask with provided.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Provided mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the source of the mask.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


Gets the exclusive disjunction of the current mask with the result of magic wand selection applied to the provided image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image for magic wand. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Magic wand settings. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
