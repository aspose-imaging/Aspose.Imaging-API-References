---
title: "FeatheringSettings"
second_title: "Aspose.Imaging för Java API-referens"
description: "En fjädringsinställningsklass."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

En fjädringsinställningsklass.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Initierar en ny instans av klassen [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar fjädringsstorleken. |
| [setSize(int value)](#setSize-int-) | Ställer in fjädringsstorleken. |
| [getMode()](#getMode--) | Hämtar fjädringsalgoritmens läge. |
| [setMode(int value)](#setMode-int-) | Ställer in fjädringsalgoritmens läge. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Förena den befintliga masken med den angivna som skapats av magiskt stav-verktyg
            .union(new MagicWandSettings(416, 387))
            // Invertera den befintliga masken
            .invert()
            // Subtrahera den angivna masken skapad av magiskt stav-verktyg med specificerad tröskel från den befintliga
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Subtrahera fyra angivna rektangelmasker från den befintliga masken en efter en
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Mjukgör masken med angivna inställningar
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden
    image.save(outputFilePath);
}

```

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Initierar en ny instans av klassen [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar fjädringsstorleken.

Värde: Storleken på fjädringspenseln i pixlar.

**Returns:**
int - fjädringsstorleken.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Ställer in fjädringsstorleken.

Värde: Storleken på fjädringspenseln i pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | fjädringsstorleken. |

### getMode() {#getMode--}
```
public final int getMode()
```


Hämtar fjädringsalgoritmens läge.

Värde: Fjädringsalgoritmens läge.

**Returns:**
int - fjädringsalgoritmens läge.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Ställer in fjädringsalgoritmens läge.

Värde: Fjädringsalgoritmens läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | läget för fjädringsalgoritmen. |

