---
title: "CircleMask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt eine Kreismaske."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Beschreibt eine Kreismaske.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Initialisiert eine neue Instanz der [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask)-Klasse mit dem angegebenen Mittelpunkt und Radius. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Initialisiert eine neue Instanz der [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask)-Klasse mit dem angegebenen Mittelpunkt und Radius. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Gibt die Begrenzungen dieser Maske in Pixeln zurück. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ermittelt die Opazität des angegebenen Pixels. |
| [inflate(int size)](#inflate-int-) | Vergrößert diese Maske um den angegebenen Betrag. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet die Maske mit dem angegebenen Rechteck zu. |
| [deepClone()](#deepClone--) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Initialisiert eine neue Instanz der [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask)-Klasse mit dem angegebenen Mittelpunkt und Radius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Mittelpunktes des ausgewählten Bereichs. |
| y | int | Die y‑Koordinate des Mittelpunktes des ausgewählten Bereichs. |
| radius | int | Radius des ausgewählten Bereichs. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Initialisiert eine neue Instanz der [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask)-Klasse mit dem angegebenen Mittelpunkt und Radius.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | Der Mittelpunkt des ausgewählten Bereichs. |
| radius | int | Radius des ausgewählten Bereichs. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Gibt die Begrenzungen dieser Maske in Pixeln zurück.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Ermittelt die Opazität des angegebenen Pixels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns:**
boolean – true, wenn das angegebene Pixel undurchsichtig ist; andernfalls false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Vergrößert diese Maske um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Der Betrag, um diese Maske aufzublähen. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Schneidet die Maske mit dem angegebenen Rechteck zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das angegebene Rechteck. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns:**
java.lang.Object - Ein neues Objekt, das eine Kopie dieser Instanz ist.
