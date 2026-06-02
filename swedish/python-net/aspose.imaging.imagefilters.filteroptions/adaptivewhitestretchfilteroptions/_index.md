---
title: "AdaptiveWhiteStretchFilterOptions klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Initierar en ny instans av [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| high_percentile | int | r | Hämtar den övre percentilen för beräkning av vitpunkt.<br/>            Pixelfärden över denna percentil betraktas som vit under utsträckning. |
| is_grayscale | bool | r | Hämtar ett värde som indikerar om filtret körs i gråskaleläge. |
| low_percentile | int | r | Hämtar den lägre percentilen för beräkning av svartpunkt.<br/>            Pixelfärden under denna percentil betraktas som svart under utsträckning. |
| max_scale | float | r | Hämtar den maximala tillåtna ljusstyrkes‑skalan.<br/>            Den faktiska utsträckningen kommer inte att överstiga denna faktor, för att undvika över‑ljusning. |
| target_white | int | r | Hämtar mål‑vitvärdet som utsträckningen syftar till att uppnå. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Initierar en ny instans av [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_grayscale | bool | Anger om filtret ska köras i gråskaleläge. |
| low_percentile | int | Lägre percentil för svartpunkt (t.ex. 10). |
| high_percentile | int | Övre percentil för vitpunkt (t.ex. 90). |
| target_white | int | Mål‑vitvärde (t.ex. 240). |
| max_scale | float | Maximalt tillåten ljusstyrkes‑skala (t.ex. 1.7). |

