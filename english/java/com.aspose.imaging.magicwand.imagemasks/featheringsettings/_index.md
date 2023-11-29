---
title: FeatheringSettings
second_title: Aspose.Imaging for Java API Reference
description: A feathering settings class.
type: docs
weight: 13
url: /java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

A feathering settings class.
## Constructors

| Constructor | Description |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Initializes a new instance of the [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class. |
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Gets the feathering size. |
| [setSize(int value)](#setSize-int-) | Sets the feathering size. |
| [getMode()](#getMode--) | Gets the feathering algorithm mode. |
| [setMode(int value)](#setMode-int-) | Sets the feathering algorithm mode. |

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

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Initializes a new instance of the [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class.

### getSize() {#getSize--}
```
public final int getSize()
```


Gets the feathering size.

Value: The size of the feathering brush in pixels.

**Returns:**
int - the feathering size.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Sets the feathering size.

Value: The size of the feathering brush in pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the feathering size. |

### getMode() {#getMode--}
```
public final int getMode()
```


Gets the feathering algorithm mode.

Value: The feathering algorithm mode.

**Returns:**
int - the feathering algorithm mode.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Sets the feathering algorithm mode.

Value: The feathering algorithm mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | the feathering algorithm mode. |

