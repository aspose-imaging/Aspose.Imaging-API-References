---
title: "ClaheFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tillhandahåller alternativ för att konfigurera Contrast-Limited Adaptive Histogram Equalization CLAHE-filtret."
type: docs
weight: 14
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Tillhandahåller alternativ för att konfigurera Contrast-Limited Adaptive Histogram Equalization (CLAHE)-filtret.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Initierar en ny instans av klassen [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) med de angivna parametrarna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Hämtar ett värde som indikerar om filtret körs i gråskala. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Hämtar antalet rutor i horisontell riktning. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Hämtar antalet rutor i vertikal riktning. |
| [getClipLimit()](#getClipLimit--) | Hämtar tröskelvärdet för kontrastbegränsning. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Initierar en ny instans av klassen [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) med de angivna parametrarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| isGrayscale | boolean | Indikerar om filtret ska köras i gråskala. |
| tilesNumberHorizontal | int | Antal rutor horisontellt. Standard är 8. |
| tilesNumberVertical | int | Antal rutor vertikalt. Standard är 8. |
| clipLimit | double | Tröskelvärde för kontrastbegränsning. Standard är 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Hämtar ett värde som indikerar om filtret körs i gråskala.

**Returns:**
boolean - ett värde som indikerar om filtret körs i gråskala.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Hämtar antalet rutor i horisontell riktning. Bestämmer hur många regioner bilden delas in i horisontellt för lokal kontrastequalisering.

**Returns:**
int - antalet rutor i horisontell riktning.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Hämtar antalet rutor i vertikal riktning. Bestämmer hur många regioner bilden delas in i vertikalt för lokal kontrastequalisering.

**Returns:**
int - antalet rutor i vertikal riktning.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Hämtar tröskelvärdet för kontrastbegränsning. Högre värden ger mer kontrast; lägre värden begränsar förbättringen för att förhindra brusförstärkning.

**Returns:**
double - tröskelvärdet för kontrastbegränsning.
