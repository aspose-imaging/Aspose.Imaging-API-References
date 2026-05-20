---
title: "RectangleMask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt eine Rechteckmaske."
type: docs
weight: 17
url: /de/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Beschreibt eine Rechteckmaske.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Initialisiert eine neue Instanz der [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) Klasse mit dem angegebenen linken oberen Punkt, Breite und Höhe. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Initialisiert eine neue Instanz der [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) Klasse mit dem angegebenen Rechteck. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ermittelt die Opazität des angegebenen Pixels. |
| [inflate(int size)](#inflate-int-) | Vergrößert diese Maske um den angegebenen Betrag. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet die Maske mit dem angegebenen Rechteck zu. |
| [deepClone()](#deepClone--) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Erstellen Sie eine neue Maske mit dem Magic‑Wand‑Tool basierend auf Ton und Farbe des Pixels (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Vereinen Sie die vorhandene Maske mit der angegebenen, die vom Magic‑Wand‑Tool erstellt wurde.
            .union(new MagicWandSettings(416, 387))
            // Invertieren Sie die vorhandene Maske.
            .invert()
            // Subtrahieren Sie die angegebene, vom Magic‑Wand‑Tool erstellte Maske mit dem angegebenen Schwellenwert von der vorhandenen Maske.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtrahieren Sie vier angegebene Rechteckmasken nacheinander von der vorhandenen Maske.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Weichzeichnen Sie die Maske mit den angegebenen Einstellungen.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Maske auf das Bild anwenden.
            .apply();

    // Bild speichern.
    image.save(outputFilePath);
}

```

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Initialisiert eine neue Instanz der [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) Klasse mit dem angegebenen linken oberen Punkt, Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des linken oberen Punkts des ausgewählten Bereichs. |
| y | int | Die y‑Koordinate des linken oberen Punkts des ausgewählten Bereichs. |
| Breite | int | Breite des ausgewählten Bereichs. |
| Höhe | int | Höhe des ausgewählten Bereichs. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Initialisiert eine neue Instanz der [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) Klasse mit dem angegebenen Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Ausgewählter Bereich als Rechteck angegeben. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns:**
java.lang.Object - Ein neues Objekt, das eine Kopie dieser Instanz ist.
