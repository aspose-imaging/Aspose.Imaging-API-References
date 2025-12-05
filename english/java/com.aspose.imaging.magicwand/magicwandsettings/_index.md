---
title: MagicWandSettings
second_title: Aspose.Imaging for Java API Reference
description: A magic wand selection settings class.
type: docs
weight: 13
url: /java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

A magic wand selection settings class.
## Constructors

| Constructor | Description |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Initializes a new instance of the [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class. |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Initializes a new instance of the [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class. |
## Methods

| Method | Description |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Gets the bounds of the area for algorithm work. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Sets the bounds of the area for algorithm work. |
| [getPoint()](#getPoint--) | Gets the reference point for algorithm work. |
| [getThreshold()](#getThreshold--) | Gets the tolerance level for pixels color comparison. |
| [setThreshold(int value)](#setThreshold-int-) | Sets the tolerance level for pixels color comparison. |
| [getContiguousMode()](#getContiguousMode--) | Gets a value indicating whether magic wand will define only contiguous pixels. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Sets a value indicating whether magic wand will define only contiguous pixels. |
| [getDirectionalMode()](#getDirectionalMode--) | Gets the mode of flood fill search algorithm: four of eight direction search. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Sets the mode of flood fill search algorithm: four of eight direction search. |
| [getColorCompareMode()](#getColorCompareMode--) | Gets the algorithm how colors are compared. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Sets the algorithm how colors are compared. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Gets the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Sets the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

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

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Initializes a new instance of the [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | The reference point. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Initializes a new instance of the [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | int | The x-coordinate of the reference point. |
| y | int | The y-coordinate of the reference point. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Gets the bounds of the area for algorithm work.

Value: The rectangle representing the bounds of the area of interest.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Sets the bounds of the area for algorithm work.

Value: The rectangle representing the bounds of the area of interest.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | the bounds of the area for algorithm work. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Gets the reference point for algorithm work.

Value: The `Point` value.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Gets the tolerance level for pixels color comparison.

Value: The threshold for color comparing.

**Returns:**
int - the tolerance level for pixels color comparison.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Sets the tolerance level for pixels color comparison.

Value: The threshold for color comparing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the tolerance level for pixels color comparison. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Gets a value indicating whether magic wand will define only contiguous pixels.

Value: `true` if the element is enabled; otherwise, `false`. The default value is `true`.

**Returns:**
boolean - a value indicating whether magic wand will define only contiguous pixels.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Sets a value indicating whether magic wand will define only contiguous pixels.

Value: `true` if the element is enabled; otherwise, `false`. The default value is `true`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether magic wand will define only contiguous pixels. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Gets the mode of flood fill search algorithm: four of eight direction search.

Value: The mode of flood fill search algorithm.

**Returns:**
int - the mode of flood fill search algorithm: four of eight direction search.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Sets the mode of flood fill search algorithm: four of eight direction search.

Value: The mode of flood fill search algorithm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the mode of flood fill search algorithm: four of eight direction search. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Gets the algorithm how colors are compared.

Value: The color compare mode.

**Returns:**
int - the algorithm how colors are compared.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Sets the algorithm how colors are compared.

Value: The color compare mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the algorithm how colors are compared. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Gets the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Value: The color compare delegate.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Sets the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Value: The color compare delegate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

