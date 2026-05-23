---
title: "ClaheFilterOptions Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Initialisiert eine neue Instanz der [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) Klasse<br/>            mit den angegebenen Parametern. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| clip_limit | float | r | Gibt den Schwellenwert für die Kontrastbegrenzung zurück.<br/>            Höhere Werte erlauben mehr Kontrast; niedrigere Werte begrenzen die Verstärkung, um eine Rauschverstärkung zu verhindern. |
| is_grayscale | bool | r | Gibt einen Wert zurück, der angibt, ob der Filter im Graustufenmodus arbeitet. |
| tiles_number_horizontal | int | r | Gibt die Anzahl der Kacheln in horizontaler Richtung zurück.<br/>            Bestimmt, in wie viele Regionen das Bild horizontal für die lokale Kontrastangleichung unterteilt wird. |
| tiles_number_vertical | int | r | Gibt die Anzahl der Kacheln in vertikaler Richtung zurück.<br/>            Bestimmt, in wie viele Regionen das Bild vertikal für die lokale Kontrastangleichung unterteilt wird. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Initialisiert eine neue Instanz der [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) Klasse<br/>            mit den angegebenen Parametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_grayscale | bool | Gibt an, ob der Filter im Graustufenmodus arbeiten soll. |
| tiles_number_horizontal | int | Anzahl der Kacheln horizontal. Standardwert ist 8. |
| tiles_number_vertical | int | Anzahl der Kacheln vertikal. Standardwert ist 8. |
| clip_limit | float | Grenzwert für die Kontrastbegrenzung. Standardwert ist 4,0. |

