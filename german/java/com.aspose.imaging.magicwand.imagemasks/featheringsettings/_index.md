---
title: "FeatheringSettings"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Eine Klasse für Federungseinstellungen."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

Eine Klasse für Federungseinstellungen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Initialisiert eine neue Instanz der [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Ermittelt die Weichzeichnungsgröße. |
| [setSize(int value)](#setSize-int-) | Setzt die Weichzeichnungsgröße. |
| [getMode()](#getMode--) | Ermittelt den Modus des Weichzeichnungsalgorithmus. |
| [setMode(int value)](#setMode-int-) | Setzt den Modus des Weichzeichnungsalgorithmus. |

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

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Initialisiert eine neue Instanz der [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) Klasse.

### getSize() {#getSize--}
```
public final int getSize()
```


Ermittelt die Weichzeichnungsgröße.

Wert: Die Größe des Weichzeichnungs‑Pinsels in Pixeln.

**Returns:**
int - die Weichzeichnungsgröße.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Setzt die Weichzeichnungsgröße.

Wert: Die Größe des Weichzeichnungs‑Pinsels in Pixeln.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Weichzeichnungsgröße. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ermittelt den Modus des Weichzeichnungsalgorithmus.

Wert: Der Modus des Weichzeichnungsalgorithmus.

**Returns:**
int - der Modus des Weichzeichnungsalgorithmus.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Setzt den Modus des Weichzeichnungsalgorithmus.

Wert: Der Modus des Weichzeichnungsalgorithmus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Federungsalgorithmus-Modus. |

