---
title: "EmptyImageMask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt eine leere nicht‑abstrakte Maske."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Beschreibt eine leere nicht‑abstrakte Maske.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Initialisiert eine neue Instanz der [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) Klasse mit der angegebenen Breite und Höhe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ermittelt die Opazität des angegebenen Pixels. |
| [inflate(int size)](#inflate-int-) | Vergrößert diese Maske um den angegebenen Betrag. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet die Maske mit dem angegebenen Rechteck zu. |
| [deepClone()](#deepClone--) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Initialisiert eine neue Instanz der [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) Klasse mit der angegebenen Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Breite der Maske. |
| Höhe | int | Höhe der Maske. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns:**
java.lang.Object - Ein neues Objekt, das eine Kopie dieser Instanz ist.
