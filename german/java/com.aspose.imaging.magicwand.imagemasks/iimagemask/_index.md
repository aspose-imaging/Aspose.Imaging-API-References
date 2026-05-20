---
title: "IImageMask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt eine Maske."
type: docs
weight: 18
url: /de/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Beschreibt eine Maske.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSource()](#getSource--) | Gibt das Quellbild zurück, das zur Erstellung dieser Maske verwendet wurde, falls vorhanden. |
| [getWidth()](#getWidth--) | Gibt die Breite dieser Maske in Pixeln zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe dieser Maske in Pixeln zurück. |
| [getBounds()](#getBounds--) | Gibt die Begrenzungen dieser Maske in Pixeln zurück. |
| [getSelectionBounds()](#getSelectionBounds--) | Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Überprüft, ob das angegebene Pixel undurchsichtig ist. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Überprüft, ob das angegebene Pixel transparent ist. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Ermittelt die Opazität des angegebenen Pixels mit Byte-Präzision. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Gibt das Quellbild zurück, das zur Erstellung dieser Maske verwendet wurde, falls vorhanden.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gibt die Breite dieser Maske in Pixeln zurück.

**Returns:**
int – die Breite dieser Maske in Pixeln.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gibt die Höhe dieser Maske in Pixeln zurück.

**Returns:**
int – die Höhe dieser Maske in Pixeln.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Gibt die Begrenzungen dieser Maske in Pixeln zurück.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


Überprüft, ob das angegebene Pixel undurchsichtig ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns:**
boolean – true, wenn das angegebene Pixel undurchsichtig ist; andernfalls false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


Überprüft, ob das angegebene Pixel transparent ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns:**
boolean – true, wenn das angegebene Pixel transparent ist; andernfalls false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


Ermittelt die Opazität des angegebenen Pixels mit Byte-Präzision.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns:**
byte – Byte‑Wert, der die Opazität des angegebenen Pixels darstellt.
