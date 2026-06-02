---
title: "RectangleMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en rektangelmask."
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Beskriver en rektangelmask.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Initierar en ny instans av klassen [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) med den angivna vänsterövre punkten, bredden och höjden. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Initierar en ny instans av klassen [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) med den angivna rektangeln. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Hämtar gränserna för den valda delen av masken, i pixlar. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Hämtar opaciteten för den angivna pixeln. |
| [inflate(int size)](#inflate-int-) | Utökar den här masken med den angivna mängden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär masken med den angivna rektangeln. |
| [deepClone()](#deepClone--) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Initierar en ny instans av klassen [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) med den angivna vänsterövre punkten, bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för den vänsterövre punkten i det markerade området. |
| y | int | Y-koordinaten för den vänsterövre punkten i det markerade området. |
| bredd | int | Bredden på det markerade området. |
| höjd | int | Höjden på det markerade området. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Initierar en ny instans av klassen [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) med den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Markerat område specificerat som en rektangel. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Hämtar gränserna för den valda delen av masken, i pixlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
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
public ImageMask inflate(int size)
```


Utökar den här masken med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| storlek | int | Mängden för att blåsa upp den här masken. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Beskär masken med den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den angivna rektangeln. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns:**
java.lang.Object - Ett nytt objekt som är en kopia av den här instansen.
