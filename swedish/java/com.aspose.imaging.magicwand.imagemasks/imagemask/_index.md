---
title: "ImageMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en binär bildmask."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

Beskriver en binär bildmask.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Kastar `mask` till en [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask). |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Inverterar masken. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Union av två masker. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Subtrahera andra masken från den första. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Snitt av två masker. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Exklusiv disjunktion av två masker. |
| [getSource()](#getSource--) | Hämtar källbilden som används för att skapa denna mask, om den finns. |
| [getWidth()](#getWidth--) | Hämtar bredden, i pixlar, för denna mask. |
| [getHeight()](#getHeight--) | Hämtar höjden, i pixlar, för denna mask. |
| [getBounds()](#getBounds--) | Hämtar gränserna, i pixlar, för denna mask. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Hämtar opaciteten för den angivna pixeln. |
| [inflate(int size)](#inflate-int-) | Utökar den här masken med den angivna mängden. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Beskär masken med den angivna storleken. |
| [crop(int width, int height)](#crop-int-int-) | Beskär masken med den angivna bredden och höjden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär masken med den angivna rektangeln. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Kontrollerar om den angivna pixeln är ogenomskinlig. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Kontrollerar om den angivna pixeln är transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Hämtar opaciteten för den angivna pixeln med byteprecision. |
| [getFeathered()](#getFeathered--) | Hämtar gråskalemask med kanten mjukad med standardinställningarna. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | Hämtar gråskalemask med kanten mjukad med de angivna inställningarna. |
| [apply()](#apply--) | Applicerar aktuell mask på [RasterImage](../../com.aspose.imaging/rasterimage) källan, om den finns. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Applicerar aktuell mask på den angivna [RasterImage](../../com.aspose.imaging/rasterimage). |
| [invert()](#invert--) | Hämtar inversionen av den aktuella masken. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Hämtar unionen av den aktuella masken med den angivna. |
| [union()](#union--) | Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på den angivna bilden. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på den angivna bilden. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Hämtar subtraktionen av den angivna masken från den aktuella. |
| [subtract()](#subtract--) | Hämtar resultatet av magic wand selection som tillämpas på källan för den aktuella masken, subtraherat från masken. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar resultatet av magic wand selection som tillämpas på källan för den aktuella masken, subtraherat från masken. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | Hämtar resultatet av magic wand selection som tillämpas på den angivna bilden, subtraherat från den aktuella masken. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar resultatet av magic wand selection som tillämpas på den angivna bilden, subtraherat från den aktuella masken. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Hämtar snittet av den aktuella masken med den angivna. |
| [intersect()](#intersect--) | Hämtar snittet av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar snittet av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | Hämtar skärningspunkten mellan den aktuella masken och resultatet av magisk stav‑urval som tillämpas på den angivna bilden. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar skärningspunkten mellan den aktuella masken och resultatet av magisk stav‑urval som tillämpas på den angivna bilden. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på maskens källa. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på maskens källa. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på den angivna bilden. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på den angivna bilden. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Förena den befintliga masken med den angivna som skapats av magiskt stav-verktyg
            .union(new MagicWandSettings(416, 387))
            // Invertera den befintliga masken
            .invert()
            // Subtrahera den angivna masken skapad av magiskt stav-verktyg med specificerad tröskel från den befintliga
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtrahera fyra angivna rektangelmasker från den befintliga masken en efter en
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Mjukgör masken med angivna inställningar
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden
    image.save(outputFilePath);
}

```

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


Kastar `mask` till en [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Maskvärdet. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


Inverterar masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Masken som ska inverteras. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


Union av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den första masken. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


Subtrahera andra masken från den första.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den första masken. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


Snitt av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den första masken. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


Exklusiv disjunktion av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den första masken. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Den andra masken. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Hämtar källbilden som används för att skapa denna mask, om den finns.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar bredden, i pixlar, för denna mask.

**Returns:**
int - bredden, i pixlar, för den här masken.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar höjden, i pixlar, för denna mask.

**Returns:**
int - höjden, i pixlar, för den här masken.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Hämtar gränserna, i pixlar, för denna mask.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
```


Hämtar opaciteten för den angivna pixeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns:**
boolean - sant om den angivna pixeln är ogenomskinlig; annars falskt.
### inflate(int size) {#inflate-int-}
```
public abstract ImageMask inflate(int size)
```


Utökar den här masken med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Mängden för att blåsa upp den här masken. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


Beskär masken med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Den angivna storleken. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


Beskär masken med den angivna bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Den angivna bredden. |
| höjd | int | Den angivna höjden. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


Beskär masken med den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den angivna rektangeln. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


Kontrollerar om den angivna pixeln är ogenomskinlig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns:**
boolean - sant om den angivna pixeln är ogenomskinlig; annars falskt.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


Kontrollerar om den angivna pixeln är transparent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns:**
boolean - sant om den angivna pixeln är transparent; annars falskt.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


Hämtar opaciteten för den angivna pixeln med byteprecision.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns:**
byte - Bytevärde som representerar opaciteten för den angivna pixeln.
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


Hämtar gråskalemask med kanten mjukad med standardinställningarna.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


Hämtar gråskalemask med kanten mjukad med de angivna inställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | Fjädringsinställningar. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


Applicerar aktuell mask på [RasterImage](../../com.aspose.imaging/rasterimage) källan, om den finns.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (120, 100) med anpassad tröskel lika med 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden med tvingad transparensfärgstyp‑alternativ
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


Applicerar aktuell mask på den angivna [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild att applicera mask på. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


Hämtar inversionen av den aktuella masken.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Förena den befintliga masken med den angivna som skapats av magiskt stav-verktyg
            .union(new MagicWandSettings(416, 387))
            // Invertera den befintliga masken
            .invert()
            // Subtrahera den angivna masken skapad av magiskt stav-verktyg med specificerad tröskel från den befintliga
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtrahera fyra angivna rektangelmasker från den befintliga masken en efter en
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Mjukgör masken med angivna inställningar
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden
    image.save(outputFilePath);
}

```

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


Hämtar unionen av den aktuella masken med den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Angiven mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


Hämtar unionen av den aktuella masken med resultatet av magic wand selection som tillämpas på den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


Hämtar subtraktionen av den angivna masken från den aktuella.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Angiven mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


Hämtar resultatet av magic wand selection som tillämpas på källan för den aktuella masken, subtraherat från masken.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


Hämtar resultatet av magic wand selection som tillämpas på källan för den aktuella masken, subtraherat från masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


Hämtar resultatet av magic wand selection som tillämpas på den angivna bilden, subtraherat från den aktuella masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


Hämtar resultatet av magic wand selection som tillämpas på den angivna bilden, subtraherat från den aktuella masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


Hämtar snittet av den aktuella masken med den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Angiven mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


Hämtar snittet av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


Hämtar snittet av den aktuella masken med resultatet av magic wand selection som tillämpas på maskens källa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


Hämtar skärningspunkten mellan den aktuella masken och resultatet av magisk stav‑urval som tillämpas på den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


Hämtar skärningspunkten mellan den aktuella masken och resultatet av magisk stav‑urval som tillämpas på den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Angiven mask |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på maskens källa.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på maskens källa.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


Hämtar den exklusiva disjunktionen av den aktuella masken med resultatet av magisk stav‑urval som tillämpas på den angivna bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild för magisk stav. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Inställningar för magisk stav. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
