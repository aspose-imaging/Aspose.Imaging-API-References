---
title: "ImageGrayscaleMask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt eine Graustufen‑Bildmaske."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

Beschreibt eine Graustufen‑Bildmaske.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | Initialisiert eine neue Instanz der [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) Klasse mit der angegebenen Breite und Höhe. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | Initialisiert eine neue Instanz der [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) Klasse mit der Größe des angegebenen vorhandenen [RasterImage](../../com.aspose.imaging/rasterimage). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSource()](#getSource--) | Gibt das Quellbild zurück, das zur Erstellung dieser Maske verwendet wurde, falls vorhanden. |
| [getWidth()](#getWidth--) | Gibt die Breite dieser Maske in Pixeln zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe dieser Maske in Pixeln zurück. |
| [getBounds()](#getBounds--) | Gibt die Begrenzungen dieser Maske in Pixeln zurück. |
| [getSelectionBounds()](#getSelectionBounds--) | Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ermittelt die Opazität des angegebenen Pixels. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | Setzt die Deckkraft des angegebenen Pixels. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Überprüft, ob das angegebene Pixel undurchsichtig ist. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Überprüft, ob das angegebene Pixel transparent ist. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Ermittelt die Opazität des angegebenen Pixels mit Byte-Präzision. |
| [deepClone()](#deepClone--) | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
| [apply()](#apply--) | Wendet die aktuelle Maske auf die [RasterImage](../../com.aspose.imaging/rasterimage)-Quelle an, falls vorhanden. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Wendet die aktuelle Maske auf die angegebene [RasterImage](../../com.aspose.imaging/rasterimage) an. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Beschneidet die Maske mit der angegebenen Größe. |
| [crop(int width, int height)](#crop-int-int-) | Beschneidet die Maske mit der angegebenen Breite und Höhe. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet die Maske mit dem angegebenen Rechteck zu. |
| [invert()](#invert--) | Ermittelt die Inversion der aktuellen Maske. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Vereinigung von zwei Masken. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Ermittelt die Schnittmenge der aktuellen Maske mit der bereitgestellten. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit der bereitgestellten. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Invertiert die Maske. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Vereinigung von zwei Masken. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Subtrahiere die zweite Maske von der ersten. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Schnittmenge von zwei Masken. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Exklusive Disjunktion von zwei Masken. |

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

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


Initialisiert eine neue Instanz der [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) Klasse mit der angegebenen Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Breite der Maske. |
| Höhe | int | Höhe der Maske. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


Initialisiert eine neue Instanz der [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) Klasse mit der Größe des angegebenen vorhandenen [RasterImage](../../com.aspose.imaging/rasterimage). Das angegebene [RasterImage](../../com.aspose.imaging/rasterimage) wird als Quellbild gespeichert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Quellbild. |

### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Gibt das Quellbild zurück, das zur Erstellung dieser Maske verwendet wurde, falls vorhanden.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gibt die Breite dieser Maske in Pixeln zurück.

**Returns:**
int – die Breite dieser Maske in Pixeln.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gibt die Höhe dieser Maske in Pixeln zurück.

**Returns:**
int – die Höhe dieser Maske in Pixeln.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Gibt die Begrenzungen dieser Maske in Pixeln zurück.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


Gibt die Begrenzungen des ausgewählten Teils der Maske in Pixeln zurück.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


Ermittelt die Opazität des angegebenen Pixels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. Wert: Byte-Wert; 0 wenn transparent; 255 wenn undurchsichtig. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


Setzt die Deckkraft des angegebenen Pixels.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. Wert: Byte-Wert; 0 wenn transparent; 255 wenn undurchsichtig. |
| Wert | byte | die Deckkraft des angegebenen Pixels. |

### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
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
public final boolean isTransparent(int x, int y)
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
public final byte getByteOpacity(int x, int y)
```


Ermittelt die Opazität des angegebenen Pixels mit Byte-Präzision.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate des Pixels. |
| y | int | Die y‑Koordinate des Pixels. |

**Returns:**
byte – Byte‑Wert, der die Opazität des angegebenen Pixels darstellt.
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist.

**Returns:**
java.lang.Object - Ein neues Objekt, das eine Kopie dieser Instanz ist.
### apply() {#apply--}
```
public final void apply()
```


Wendet die aktuelle Maske auf die [RasterImage](../../com.aspose.imaging/rasterimage)-Quelle an, falls vorhanden.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Wendet die aktuelle Maske auf die angegebene [RasterImage](../../com.aspose.imaging/rasterimage) an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild, auf das die Maske angewendet wird. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


Beschneidet die Maske mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Die angegebene Größe. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


Beschneidet die Maske mit der angegebenen Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die angegebene Breite. |
| Höhe | int | Die angegebene Höhe. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


Schneidet die Maske mit dem angegebenen Rechteck zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das angegebene Rechteck. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


Ermittelt die Inversion der aktuellen Maske.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


Vereinigung von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Bereitgestellte Maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Bereitgestellte Maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


Ermittelt die Schnittmenge der aktuellen Maske mit der bereitgestellten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Bereitgestellte Maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


Ermittelt die exklusive Disjunktion der aktuellen Maske mit der bereitgestellten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Bereitgestellte Maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


Invertiert die Maske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die zu invertierende Maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Vereinigung von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die erste Maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die zweite Maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Subtrahiere die zweite Maske von der ersten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die erste Maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die zweite Maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Schnittmenge von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die erste Maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die zweite Maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Exklusive Disjunktion von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die erste Maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Die zweite Maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
