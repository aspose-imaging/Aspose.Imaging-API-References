---
title: "ImageGrayscaleMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en gråskalebildmask."
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

Beskriver en gråskalebildmask.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | Initierar en ny instans av klassen [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) med den angivna bredden och höjden. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | Initierar en ny instans av klassen [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) med storleken på den angivna befintliga [RasterImage](../../com.aspose.imaging/rasterimage). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSource()](#getSource--) | Hämtar källbilden som används för att skapa denna mask, om den finns. |
| [getWidth()](#getWidth--) | Hämtar bredden, i pixlar, för denna mask. |
| [getHeight()](#getHeight--) | Hämtar höjden, i pixlar, för denna mask. |
| [getBounds()](#getBounds--) | Hämtar gränserna, i pixlar, för denna mask. |
| [getSelectionBounds()](#getSelectionBounds--) | Hämtar gränserna för den valda delen av masken, i pixlar. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Hämtar opaciteten för den angivna pixeln. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | Ställer in opaciteten för den angivna pixeln. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Kontrollerar om den angivna pixeln är ogenomskinlig. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Kontrollerar om den angivna pixeln är transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Hämtar opaciteten för den angivna pixeln med byteprecision. |
| [deepClone()](#deepClone--) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
| [apply()](#apply--) | Applicerar aktuell mask på [RasterImage](../../com.aspose.imaging/rasterimage) källan, om den finns. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Applicerar aktuell mask på den angivna [RasterImage](../../com.aspose.imaging/rasterimage). |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Beskär masken med den angivna storleken. |
| [crop(int width, int height)](#crop-int-int-) | Beskär masken med den angivna bredden och höjden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär masken med den angivna rektangeln. |
| [invert()](#invert--) | Hämtar inversionen av den aktuella masken. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Union av två masker. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Hämtar subtraktionen av den angivna masken från den aktuella. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Hämtar snittet av den aktuella masken med den angivna. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Inverterar masken. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Union av två masker. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Subtrahera andra masken från den första. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Snitt av två masker. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Exklusiv disjunktion av två masker. |

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

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


Initierar en ny instans av klassen [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) med den angivna bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Maskens bredd. |
| höjd | int | Maskens höjd. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


Initierar en ny instans av klassen [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) med storleken på den angivna befintliga [RasterImage](../../com.aspose.imaging/rasterimage). Den angivna [RasterImage](../../com.aspose.imaging/rasterimage) kommer att lagras som källbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Källbild. |

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
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


Hämtar gränserna för den valda delen av masken, i pixlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


Hämtar opaciteten för den angivna pixeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. Värde: Bytevärde; 0 om transparent; 255 om opak. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


Ställer in opaciteten för den angivna pixeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. Värde: Bytevärde; 0 om transparent; 255 om opak. |
| värde | byte | opaciteten för den angivna pixeln. |

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
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns:**
java.lang.Object - Ett nytt objekt som är en kopia av den här instansen.
### apply() {#apply--}
```
public final void apply()
```


Applicerar aktuell mask på [RasterImage](../../com.aspose.imaging/rasterimage) källan, om den finns.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Applicerar aktuell mask på den angivna [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild att applicera mask på. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


Beskär masken med den angivna storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Den angivna storleken. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


Beskär masken med den angivna bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Den angivna bredden. |
| höjd | int | Den angivna höjden. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


Beskär masken med den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den angivna rektangeln. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


Hämtar inversionen av den aktuella masken.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


Union av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Angiven mask |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


Hämtar subtraktionen av den angivna masken från den aktuella.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Angiven mask |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


Hämtar snittet av den aktuella masken med den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Angiven mask |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


Hämtar den exklusiva disjunktionen av den aktuella masken med den angivna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Angiven mask |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


Inverterar masken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Masken som ska inverteras. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Union av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den första masken. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den andra masken. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Subtrahera andra masken från den första.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den första masken. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den andra masken. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Snitt av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den första masken. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den andra masken. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Exklusiv disjunktion av två masker.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den första masken. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Den andra masken. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
