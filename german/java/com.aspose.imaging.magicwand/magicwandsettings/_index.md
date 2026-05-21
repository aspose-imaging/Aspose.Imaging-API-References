---
title: "MagicWandSettings"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eine Klasse für Magic‑Wand‑Auswahleinstellungen."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Eine Klasse für Magic‑Wand‑Auswahleinstellungen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Initialisiert eine neue Instanz der [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) Klasse. |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Initialisiert eine neue Instanz der [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Liefert die Grenzen des Bereichs für die Algorithmus‑Ausführung. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Setzt die Grenzen des Bereichs für die Algorithmus‑Ausführung. |
| [getPoint()](#getPoint--) | Liefert den Referenzpunkt für die Algorithmus‑Ausführung. |
| [getThreshold()](#getThreshold--) | Liefert den Toleranzwert für den Farbvergleich von Pixeln. |
| [setThreshold(int value)](#setThreshold-int-) | Setzt den Toleranzwert für den Farbvergleich von Pixeln. |
| [getContiguousMode()](#getContiguousMode--) | Liefert einen Wert, der angibt, ob magic wand nur zusammenhängende Pixel definiert. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Legt einen Wert fest, der angibt, ob der Magic Wand nur zusammenhängende Pixel definiert. |
| [getDirectionalMode()](#getDirectionalMode--) | Liefert den Modus des Flood-Fill-Suchalgorithmus: vier- oder acht Richtungs-Suche. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Legt den Modus des Flood-Fill-Suchalgorithmus fest: vier- oder acht Richtungs-Suche. |
| [getColorCompareMode()](#getColorCompareMode--) | Liefert den Algorithmus, wie Farben verglichen werden. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Legt den Algorithmus fest, wie Farben verglichen werden. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Liefert den benutzerdefinierten Farbabgleich-Algorithmus, wenn `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) auf [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom) gesetzt ist. |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Legt den benutzerdefinierten Farbabgleich-Algorithmus fest, wenn `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) auf [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom) gesetzt ist. |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

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

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Initialisiert eine neue Instanz der [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Der Referenzpunkt. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Initialisiert eine neue Instanz der [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des Referenzpunkts. |
| y | int | Die y-Koordinate des Referenzpunkts. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Liefert die Grenzen des Bereichs für die Algorithmus‑Ausführung.

Wert: Das Rechteck, das die Grenzen des Interessengebiets darstellt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Setzt die Grenzen des Bereichs für die Algorithmus‑Ausführung.

Wert: Das Rechteck, das die Grenzen des Interessengebiets darstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | die Grenzen des Bereichs für die Algorithmusarbeit. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Liefert den Referenzpunkt für die Algorithmus‑Ausführung.

Wert: Der `Point`-Wert.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Liefert den Toleranzwert für den Farbvergleich von Pixeln.

Wert: Der Schwellenwert für den Farbabgleich.

**Returns:**
int – die Toleranzstufe für den Farbvergleich von Pixeln.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Setzt den Toleranzwert für den Farbvergleich von Pixeln.

Wert: Der Schwellenwert für den Farbabgleich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Toleranzstufe für den Farbvergleich von Pixeln. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Liefert einen Wert, der angibt, ob magic wand nur zusammenhängende Pixel definiert.

Wert: `true`, wenn das Element aktiviert ist; andernfalls `false`. Der Standardwert ist `true`.

**Returns:**
boolean – ein Wert, der angibt, ob der Magic Wand nur zusammenhängende Pixel definiert.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Legt einen Wert fest, der angibt, ob der Magic Wand nur zusammenhängende Pixel definiert.

Wert: `true`, wenn das Element aktiviert ist; andernfalls `false`. Der Standardwert ist `true`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob der Magic Wand nur zusammenhängende Pixel definiert. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Liefert den Modus des Flood-Fill-Suchalgorithmus: vier- oder acht Richtungs-Suche.

Wert: Der Modus des Flood-Fill-Suchalgorithmus.

**Returns:**
int – der Modus des Flood-Fill-Suchalgorithmus: vier- oder acht Richtungs-Suche.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Legt den Modus des Flood-Fill-Suchalgorithmus fest: vier- oder acht Richtungs-Suche.

Wert: Der Modus des Flood-Fill-Suchalgorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Modus des Flood-Fill-Suchalgorithmus: vier- oder acht Richtungs-Suche. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Liefert den Algorithmus, wie Farben verglichen werden.

Wert: Der Farbvergleichsmodus.

**Returns:**
int – der Algorithmus, wie Farben verglichen werden.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Legt den Algorithmus fest, wie Farben verglichen werden.

Wert: Der Farbvergleichsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Algorithmus, wie Farben verglichen werden. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Liefert den benutzerdefinierten Farbabgleich-Algorithmus, wenn `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) auf [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom) gesetzt ist.

Wert: Der Farbvergleich-Delegat.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Legt den benutzerdefinierten Farbabgleich-Algorithmus fest, wenn `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) auf [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom) gesetzt ist.

Wert: Der Farbvergleich-Delegat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | der benutzerdefinierte Farbvergleich-Algorithmus, wenn `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) auf [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom) gesetzt ist. |

