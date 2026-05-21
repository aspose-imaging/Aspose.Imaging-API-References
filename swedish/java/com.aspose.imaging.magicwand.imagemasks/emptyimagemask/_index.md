---
title: "EmptyImageMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en tom icke-abstrakt mask."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Beskriver en tom icke-abstrakt mask.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Initierar en ny instans av klassen [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) med den angivna bredden och höjden. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Hämtar gränserna för den valda delen av masken, i pixlar. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Hämtar opaciteten för den angivna pixeln. |
| [inflate(int size)](#inflate-int-) | Utökar den här masken med den angivna mängden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär masken med den angivna rektangeln. |
| [deepClone()](#deepClone--) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Initierar en ny instans av klassen [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) med den angivna bredden och höjden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Maskens bredd. |
| höjd | int | Maskens höjd. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns:**
java.lang.Object - Ett nytt objekt som är en kopia av den här instansen.
