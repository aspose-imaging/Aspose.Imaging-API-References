---
title: "Classe AdaptiveWhiteStretchFilterOptions"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Initialise une nouvelle instance de la classe [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| high_percentile | int | r | Obtient le percentile supérieur pour le calcul du point blanc.<br/>            Les valeurs de pixel au-dessus de ce percentile sont considérées comme blanches pendant l'étirement. |
| is_grayscale | bool | r | Obtient une valeur indiquant si le filtre fonctionne en mode niveaux de gris. |
| low_percentile | int | r | Obtient le percentile inférieur pour le calcul du point noir.<br/>            Les valeurs de pixel en dessous de ce percentile sont considérées comme noires pendant l'étirement. |
| max_scale | float | r | Obtient l'échelle de luminosité maximale autorisée.<br/>            L'étirement réel ne dépassera pas ce facteur, afin d'éviter un éclaircissement excessif. |
| target_white | int | r | Obtient la valeur blanche cible que l'étirement vise à atteindre. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Initialise une nouvelle instance de la classe [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| is_grayscale | bool | Indique si le filtre doit fonctionner en mode niveaux de gris. |
| low_percentile | int | Percentile inférieur pour le point noir (par ex. 10). |
| high_percentile | int | Percentile supérieur pour le point blanc (par ex. 90). |
| target_white | int | Valeur blanche cible (par ex. 240). |
| max_scale | float | Échelle de luminosité maximale autorisée (par ex. 1.7). |

