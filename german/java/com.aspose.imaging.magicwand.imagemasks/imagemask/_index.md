---
title: "ImageMask"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Beschreibt eine binäre Bildmaske."
type: docs
weight: 16
url: /de/java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

Beschreibt eine binäre Bildmaske.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Umwandeln von `mask` zu einer [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask). |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Invertiert die Maske. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Vereinigung von zwei Masken. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Subtrahiere die zweite Maske von der ersten. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Schnittmenge von zwei Masken. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Exklusive Disjunktion von zwei Masken. |
| [getSource()](#getSource--) | Gibt das Quellbild zurück, das zur Erstellung dieser Maske verwendet wurde, falls vorhanden. |
| [getWidth()](#getWidth--) | Gibt die Breite dieser Maske in Pixeln zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe dieser Maske in Pixeln zurück. |
| [getBounds()](#getBounds--) | Gibt die Begrenzungen dieser Maske in Pixeln zurück. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Ermittelt die Opazität des angegebenen Pixels. |
| [inflate(int size)](#inflate-int-) | Vergrößert diese Maske um den angegebenen Betrag. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Beschneidet die Maske mit der angegebenen Größe. |
| [crop(int width, int height)](#crop-int-int-) | Beschneidet die Maske mit der angegebenen Breite und Höhe. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet die Maske mit dem angegebenen Rechteck zu. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Überprüft, ob das angegebene Pixel undurchsichtig ist. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Überprüft, ob das angegebene Pixel transparent ist. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Ermittelt die Opazität des angegebenen Pixels mit Byte-Präzision. |
| [getFeathered()](#getFeathered--) | Ermittelt Graustufenmaske mit dem Rand verwischt nach den Standardeinstellungen. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | Ermittelt Graustufenmaske mit dem Rand verwischt nach den angegebenen Einstellungen. |
| [apply()](#apply--) | Wendet die aktuelle Maske auf die [RasterImage](../../com.aspose.imaging/rasterimage)-Quelle an, falls vorhanden. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Wendet die aktuelle Maske auf die angegebene [RasterImage](../../com.aspose.imaging/rasterimage) an. |
| [invert()](#invert--) | Ermittelt die Inversion der aktuellen Maske. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ermittelt die Vereinigung der aktuellen Maske mit der bereitgestellten. |
| [union()](#union--) | Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen. |
| [subtract()](#subtract--) | Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf die Quelle der aktuellen Maske angewendet wurde, subtrahiert von der Maske. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf die Quelle der aktuellen Maske angewendet wurde, subtrahiert von der Maske. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde, subtrahiert von der aktuellen Maske. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde, subtrahiert von der aktuellen Maske. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ermittelt die Schnittmenge der aktuellen Maske mit der bereitgestellten. |
| [intersect()](#intersect--) | Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit der bereitgestellten. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf die Quelle der Maske angewendet wurde. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde. |

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

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


Umwandeln von `mask` zu einer [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Der Maskenwert. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


Invertiert die Maske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die zu invertierende Maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


Vereinigung von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die erste Maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die zweite Maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


Subtrahiere die zweite Maske von der ersten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die erste Maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die zweite Maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


Schnittmenge von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die erste Maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die zweite Maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


Exklusive Disjunktion von zwei Masken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die erste Maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Die zweite Maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
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
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
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
public abstract ImageMask inflate(int size)
```


Vergrößert diese Maske um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Größe | int | Der Betrag, um diese Maske aufzublähen. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


Beschneidet die Maske mit der angegebenen Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Die angegebene Größe. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


Beschneidet die Maske mit der angegebenen Breite und Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die angegebene Breite. |
| Höhe | int | Die angegebene Höhe. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


Schneidet die Maske mit dem angegebenen Rechteck zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das angegebene Rechteck. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
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
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


Ermittelt Graustufenmaske mit dem Rand verwischt nach den Standardeinstellungen.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


Ermittelt Graustufenmaske mit dem Rand verwischt nach den angegebenen Einstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | Weichzeichnungs‑Einstellungen. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


Wendet die aktuelle Maske auf die [RasterImage](../../com.aspose.imaging/rasterimage)-Quelle an, falls vorhanden.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Erstellen Sie eine neue Maske mit dem Magic‑Wand‑Tool basierend auf Ton und Farbe des Pixels (120, 100) mit einem benutzerdefinierten Schwellenwert von 150.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Maske auf das Bild anwenden.
            .apply();

    // Bild mit erzwungenem Transparenzfarbtyp‑Option speichern.
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Wendet die aktuelle Maske auf die angegebene [RasterImage](../../com.aspose.imaging/rasterimage) an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild, auf das die Maske angewendet wird. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


Ermittelt die Inversion der aktuellen Maske.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

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

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


Ermittelt die Vereinigung der aktuellen Maske mit der bereitgestellten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Bereitgestellte Maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


Ermittelt die Vereinigung der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


Ermittelt die Subtraktion der bereitgestellten Maske von der aktuellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Bereitgestellte Maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf die Quelle der aktuellen Maske angewendet wurde, subtrahiert von der Maske.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf die Quelle der aktuellen Maske angewendet wurde, subtrahiert von der Maske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde, subtrahiert von der aktuellen Maske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


Ermittelt das Ergebnis der Zauberstab-Auswahl, die auf das bereitgestellte Bild angewendet wurde, subtrahiert von der aktuellen Maske.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


Ermittelt die Schnittmenge der aktuellen Maske mit der bereitgestellten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Bereitgestellte Maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab-Auswahl, die auf die Quelle der Maske angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


Ermittelt die Schnittmenge der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


Ermittelt die exklusive Disjunktion der aktuellen Maske mit der bereitgestellten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Bereitgestellte Maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf die Quelle der Maske angewendet wurde.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf die Quelle der Maske angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


Ermittelt die exklusive Disjunktion der aktuellen Maske mit dem Ergebnis der Zauberstab‑Auswahl, die auf das bereitgestellte Bild angewendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Bild für den Zauberstab. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Zauberstab‑Einstellungen. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
