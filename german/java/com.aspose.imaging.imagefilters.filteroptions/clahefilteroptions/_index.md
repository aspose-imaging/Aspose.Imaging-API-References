---
title: "ClaheFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt Optionen zum Konfigurieren des Contrast-Limited Adaptive Histogram Equalization CLAHE-Filters bereit."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Bietet Optionen zur Konfiguration des Contrast-Limited Adaptive Histogram Equalization (CLAHE)-Filters.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Initialisiert eine neue Instanz der [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions)-Klasse mit den angegebenen Parametern. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Gibt einen Wert zurück, der angibt, ob der Filter im Graustufenmodus arbeitet. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Gibt die Anzahl der Kacheln in horizontaler Richtung zurück. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Gibt die Anzahl der Kacheln in vertikaler Richtung zurück. |
| [getClipLimit()](#getClipLimit--) | Gibt den Schwellenwert für die Kontrastbegrenzung zurück. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Initialisiert eine neue Instanz der [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions)-Klasse mit den angegebenen Parametern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| isGrayscale | boolean | Gibt an, ob der Filter im Graustufenmodus arbeiten soll. |
| tilesNumberHorizontal | int | Anzahl der Kacheln horizontal. Standardwert ist 8. |
| tilesNumberVertical | int | Anzahl der Kacheln vertikal. Standardwert ist 8. |
| clipLimit | double | Schwellenwert für die Kontrastbegrenzung. Standardwert ist 4,0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Gibt einen Wert zurück, der angibt, ob der Filter im Graustufenmodus arbeitet.

**Returns:**
boolean – ein Wert, der angibt, ob der Filter im Graustufenmodus arbeitet.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Gibt die Anzahl der Kacheln in horizontaler Richtung zurück. Bestimmt, in wie viele Regionen das Bild horizontal für die lokale Kontrastangleichung unterteilt wird.

**Returns:**
int – die Anzahl der Kacheln in horizontaler Richtung.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Gibt die Anzahl der Kacheln in vertikaler Richtung zurück. Bestimmt, in wie viele Regionen das Bild vertikal für die lokale Kontrastangleichung unterteilt wird.

**Returns:**
int – die Anzahl der Kacheln in vertikaler Richtung.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Gibt den Schwellenwert für die Kontrastbegrenzung zurück. Höhere Werte ermöglichen mehr Kontrast; niedrigere Werte begrenzen die Verstärkung, um Rauschen zu vermeiden.

**Returns:**
double – der Schwellenwert für die Kontrastbegrenzung.
