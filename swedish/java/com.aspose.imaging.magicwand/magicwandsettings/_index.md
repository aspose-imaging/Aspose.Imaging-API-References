---
title: "MagicWandSettings"
second_title: "Aspose.Imaging för Java API-referens"
description: "En klass för inställningar av Magic Wand-markering."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

En klass för inställningar av Magic Wand-markering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Initierar en ny instans av klassen [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Initierar en ny instans av klassen [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Hämtar gränserna för området för algoritmarbetet. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Ställer in gränserna för området för algoritmarbetet. |
| [getPoint()](#getPoint--) | Hämtar referenspunkten för algoritmarbetet. |
| [getThreshold()](#getThreshold--) | Hämtar toleransnivån för färgjämförelse av pixlar. |
| [setThreshold(int value)](#setThreshold-int-) | Ställer in toleransnivån för färgjämförelse av pixlar. |
| [getContiguousMode()](#getContiguousMode--) | Hämtar ett värde som indikerar om magic wand endast kommer att definiera sammanhängande pixlar. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Ställer in ett värde som anger om magic wand bara definierar sammanhängande pixlar. |
| [getDirectionalMode()](#getDirectionalMode--) | Hämtar läget för flood fill-sökalgoritmen: fyra‑av‑åtta‑riktning‑sökning. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Ställer in läget för flood fill-sökalgoritmen: fyra‑av‑åtta‑riktning‑sökning. |
| [getColorCompareMode()](#getColorCompareMode--) | Hämtar algoritmen för hur färger jämförs. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Ställer in algoritmen för hur färger jämförs. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Hämtar den anpassade färgjämförelsealgoritmen om `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) är inställd på [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Ställer in den anpassade färgjämförelsealgoritmen om `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) är inställd på [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom). |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Skapa en ny mask med magiskt stav-verktyg baserat på ton och färg för pixel (120, 100) med anpassad tröskel lika med 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Applicera masken på bilden
            .apply();

    // Spara bilden med tvingad transparensfärgstyp‑alternativ
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

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Initierar en ny instans av klassen [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Referenspunkten. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Initierar en ny instans av klassen [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | x-koordinaten för referenspunkten. |
| y | int | y-koordinaten för referenspunkten. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Hämtar gränserna för området för algoritmarbetet.

Värde: Rektangeln som representerar gränserna för intresseområdet.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Ställer in gränserna för området för algoritmarbetet.

Värde: Rektangeln som representerar gränserna för intresseområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | gränserna för området för algoritmens arbete. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Hämtar referenspunkten för algoritmarbetet.

Värde: `Point`‑värdet.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Hämtar toleransnivån för färgjämförelse av pixlar.

Värde: Tröskeln för färgjämförelse.

**Returns:**
int – toleransnivån för pixelns färgjämförelse.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Ställer in toleransnivån för färgjämförelse av pixlar.

Värde: Tröskeln för färgjämförelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | toleransnivån för pixelns färgjämförelse. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Hämtar ett värde som indikerar om magic wand endast kommer att definiera sammanhängande pixlar.

Värde: `true` om elementet är aktiverat; annars `false`. Standardvärdet är `true`.

**Returns:**
boolean – ett värde som anger om magic wand bara definierar sammanhängande pixlar.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Ställer in ett värde som anger om magic wand bara definierar sammanhängande pixlar.

Värde: `true` om elementet är aktiverat; annars `false`. Standardvärdet är `true`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som anger om magic wand bara definierar sammanhängande pixlar. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Hämtar läget för flood fill-sökalgoritmen: fyra‑av‑åtta‑riktning‑sökning.

Värde: Läget för flood fill-sökalgoritmen.

**Returns:**
int – läget för flood fill-sökalgoritmen: fyra‑av‑åtta‑riktning‑sökning.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Ställer in läget för flood fill-sökalgoritmen: fyra‑av‑åtta‑riktning‑sökning.

Värde: Läget för flood fill-sökalgoritmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | läget för flood fill-sökalgoritmen: fyra‑av‑åtta‑riktning‑sökning. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Hämtar algoritmen för hur färger jämförs.

Värde: Färgjämförelseläget.

**Returns:**
int – algoritmen för hur färger jämförs.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Ställer in algoritmen för hur färger jämförs.

Värde: Färgjämförelseläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | algoritmen för hur färger jämförs. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Hämtar den anpassade färgjämförelsealgoritmen om `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) är inställd på [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom).

Värde: Färgjämförelsedelegaten.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Ställer in den anpassade färgjämförelsealgoritmen om `ColorCompareMode`(\\#getColorCompareMode.getColorCompareMode/\\#setColorCompareMode(int).setColorCompareMode(int)) är inställd på [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\\#Custom).

Värde: Färgjämförelsedelegaten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | den anpassade färgjämförelsealgoritmen om `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) är inställd på [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

