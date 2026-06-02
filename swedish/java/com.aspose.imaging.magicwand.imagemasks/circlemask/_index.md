---
title: "CircleMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en cirkelmask."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Beskriver en cirkelmask.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Initierar en ny instans av klassen [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) med den angivna mittpunkten och radien. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Initierar en ny instans av klassen [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) med den angivna mittpunkten och radien. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Hämtar gränserna, i pixlar, för denna mask. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Hämtar opaciteten för den angivna pixeln. |
| [inflate(int size)](#inflate-int-) | Utökar den här masken med den angivna mängden. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beskär masken med den angivna rektangeln. |
| [deepClone()](#deepClone--) | Skapar ett nytt objekt som är en kopia av den aktuella instansen. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Initierar en ny instans av klassen [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) med den angivna mittpunkten och radien.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för mittpunkten av det valda området. |
| y | int | Y-koordinaten för mittpunkten av det valda området. |
| radie | int | Radie för det valda området. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Initierar en ny instans av klassen [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) med den angivna mittpunkten och radien.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | Mittpunkten av det valda området. |
| radie | int | Radie för det valda området. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Hämtar gränserna, i pixlar, för denna mask.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Skapar ett nytt objekt som är en kopia av den aktuella instansen.

**Returns:**
java.lang.Object - Ett nytt objekt som är en kopia av den här instansen.
