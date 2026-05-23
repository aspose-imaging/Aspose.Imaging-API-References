---
title: "AdaptiveWhiteStretchFilterOptions Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Initialisiert eine neue Instanz der Klasse [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| high_percentile | int | r | Ermittelt das obere Perzentil für die Berechnung des Weißpunkts.<br/>            Pixelwerte über diesem Perzentil werden beim Stretching als Weiß betrachtet. |
| is_grayscale | bool | r | Gibt einen Wert zurück, der angibt, ob der Filter im Graustufenmodus arbeitet. |
| low_percentile | int | r | Ermittelt das untere Perzentil für die Berechnung des Schwarzpunkts.<br/>            Pixelwerte unter diesem Perzentil werden beim Stretching als Schwarz betrachtet. |
| max_scale | float | r | Ermittelt die maximal zulässige Helligkeitsskala.<br/>            Das tatsächliche Stretching überschreitet diesen Faktor nicht, um Überbelichtung zu vermeiden. |
| target_white | int | r | Ermittelt den Ziel‑Weißwert, den das Stretching erreichen soll. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Initialisiert eine neue Instanz der Klasse [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| is_grayscale | bool | Gibt an, ob der Filter im Graustufenmodus arbeiten soll. |
| low_percentile | int | Unteres Perzentil für den Schwarzpunkt (z. B. 10). |
| high_percentile | int | Oberes Perzentil für den Weißpunkt (z. B. 90). |
| target_white | int | Ziel‑Weißwert (z. B. 240). |
| max_scale | float | Maximal zulässige Helligkeitsskala (z. B. 1.7). |

