---
title: "MagicWandSettings"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Una classe di impostazioni di selezione magic wand."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Una classe di impostazioni di selezione magic wand.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Inizializza una nuova istanza della classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Inizializza una nuova istanza della classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Restituisce i limiti dell'area per il lavoro dell'algoritmo. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Imposta i limiti dell'area per il lavoro dell'algoritmo. |
| [getPoint()](#getPoint--) | Restituisce il punto di riferimento per il lavoro dell'algoritmo. |
| [getThreshold()](#getThreshold--) | Restituisce il livello di tolleranza per il confronto del colore dei pixel. |
| [setThreshold(int value)](#setThreshold-int-) | Imposta il livello di tolleranza per il confronto del colore dei pixel. |
| [getContiguousMode()](#getContiguousMode--) | Restituisce un valore che indica se la bacchetta magica definirà solo pixel contigui. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Imposta un valore che indica se la bacchetta magica definirà solo pixel contigui. |
| [getDirectionalMode()](#getDirectionalMode--) | Ottiene la modalità dell'algoritmo di ricerca flood fill: ricerca a quattro o otto direzioni. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Imposta la modalità dell'algoritmo di ricerca flood fill: ricerca a quattro o otto direzioni. |
| [getColorCompareMode()](#getColorCompareMode--) | Ottiene l'algoritmo di confronto dei colori. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Imposta l'algoritmo di confronto dei colori. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Ottiene l'algoritmo personalizzato di confronto dei colori se `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) è impostato su [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Imposta l'algoritmo personalizzato di confronto dei colori se `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) è impostato su [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Crea una nuova maschera usando lo strumento magic wand basata sul tono e sul colore del pixel (120, 100) con soglia personalizzata pari a 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Applica la maschera all'immagine
            .apply();

    // Salva l'immagine con l'opzione di tipo colore di trasparenza forzata
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
    // Crea una nuova maschera usando lo strumento magic wand basata sul tono e sul colore del pixel (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Unisci la maschera esistente con quella specificata creata dallo strumento magic wand
            .union(new MagicWandSettings(416, 387))
            // Inverti la maschera esistente
            .invert()
            // Sottrai la maschera specificata creata dallo strumento magic wand con soglia specificata dalla maschera esistente
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Sottrai quattro maschere rettangolari specificate dalla maschera esistente una alla volta
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Sfuma la maschera con le impostazioni specificate
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Applica la maschera all'immagine
            .apply();

    // Salva immagine
    image.save(outputFilePath);
}

```

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Inizializza una nuova istanza della classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Il punto di riferimento. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Inizializza una nuova istanza della classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La coordinata x del punto di riferimento. |
| y | int | La coordinata y del punto di riferimento. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Restituisce i limiti dell'area per il lavoro dell'algoritmo.

Valore: Il rettangolo che rappresenta i limiti dell'area di interesse.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Imposta i limiti dell'area per il lavoro dell'algoritmo.

Valore: Il rettangolo che rappresenta i limiti dell'area di interesse.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | i limiti dell'area per il lavoro dell'algoritmo. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Restituisce il punto di riferimento per il lavoro dell'algoritmo.

Valore: Il valore `Point`.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Restituisce il livello di tolleranza per il confronto del colore dei pixel.

Valore: La soglia per il confronto dei colori.

**Returns:**
int - il livello di tolleranza per il confronto del colore dei pixel.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Imposta il livello di tolleranza per il confronto del colore dei pixel.

Valore: La soglia per il confronto dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il livello di tolleranza per il confronto del colore dei pixel. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Restituisce un valore che indica se la bacchetta magica definirà solo pixel contigui.

Valore: `true` se l'elemento è abilitato; altrimenti, `false`. Il valore predefinito è `true`.

**Returns:**
boolean - un valore che indica se la bacchetta magica definirà solo pixel contigui.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Imposta un valore che indica se la bacchetta magica definirà solo pixel contigui.

Valore: `true` se l'elemento è abilitato; altrimenti, `false`. Il valore predefinito è `true`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se la bacchetta magica definirà solo pixel contigui. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Ottiene la modalità dell'algoritmo di ricerca flood fill: ricerca a quattro o otto direzioni.

Valore: La modalità dell'algoritmo di ricerca flood fill.

**Returns:**
int - la modalità dell'algoritmo di ricerca flood fill: ricerca a quattro o otto direzioni.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Imposta la modalità dell'algoritmo di ricerca flood fill: ricerca a quattro o otto direzioni.

Valore: La modalità dell'algoritmo di ricerca flood fill.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la modalità dell'algoritmo di ricerca flood fill: ricerca a quattro o otto direzioni. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Ottiene l'algoritmo di confronto dei colori.

Valore: La modalità di confronto dei colori.

**Returns:**
int - l'algoritmo di confronto dei colori.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Imposta l'algoritmo di confronto dei colori.

Valore: La modalità di confronto dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | l'algoritmo di confronto dei colori. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Ottiene l'algoritmo personalizzato di confronto dei colori se `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) è impostato su [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Valore: il delegato di confronto colore.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Imposta l'algoritmo personalizzato di confronto dei colori se `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) è impostato su [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Valore: il delegato di confronto colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | l'algoritmo di confronto colore personalizzato se `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) è impostato su [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

