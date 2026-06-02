---
title: "IImageMask"
second_title: "Aspose.Imaging för Java API-referens"
description: "Beskriver en mask."
type: docs
weight: 18
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Beskriver en mask.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSource()](#getSource--) | Hämtar källbilden som används för att skapa denna mask, om den finns. |
| [getWidth()](#getWidth--) | Hämtar bredden, i pixlar, för denna mask. |
| [getHeight()](#getHeight--) | Hämtar höjden, i pixlar, för denna mask. |
| [getBounds()](#getBounds--) | Hämtar gränserna, i pixlar, för denna mask. |
| [getSelectionBounds()](#getSelectionBounds--) | Hämtar gränserna för den valda delen av masken, i pixlar. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Kontrollerar om den angivna pixeln är ogenomskinlig. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Kontrollerar om den angivna pixeln är transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Hämtar opaciteten för den angivna pixeln med byteprecision. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Hämtar källbilden som används för att skapa denna mask, om den finns.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Hämtar bredden, i pixlar, för denna mask.

**Returns:**
int - bredden, i pixlar, för den här masken.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Hämtar höjden, i pixlar, för denna mask.

**Returns:**
int - höjden, i pixlar, för den här masken.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Hämtar gränserna, i pixlar, för denna mask.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Hämtar gränserna för den valda delen av masken, i pixlar.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
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
public abstract boolean isTransparent(int x, int y)
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
public abstract byte getByteOpacity(int x, int y)
```


Hämtar opaciteten för den angivna pixeln med byteprecision.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för pixeln. |
| y | int | Y-koordinaten för pixeln. |

**Returns:**
byte - Bytevärde som representerar opaciteten för den angivna pixeln.
