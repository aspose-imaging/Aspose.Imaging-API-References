---
title: "Clase AdaptiveWhiteStretchFilterOptions"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---

**Summary:** Provides options for configuring the Adaptive White Stretch filter.<br/>            Allows customization of histogram stretch parameters to enhance the white level<br/>            and improve the readability of faint-text or low-contrast document images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AdaptiveWhiteStretchFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale)](#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1) | Inicializa una nueva instancia de la clase [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| high_percentile | int | r | Obtiene el percentil superior para el cálculo del punto blanco.<br/>            Los valores de píxel por encima de este percentil se consideran blancos durante el estiramiento. |
| is_grayscale | bool | r | Obtiene un valor que indica si el filtro opera en modo escala de grises. |
| low_percentile | int | r | Obtiene el percentil inferior para el cálculo del punto negro.<br/>            Los valores de píxel por debajo de este percentil se consideran negros durante el estiramiento. |
| max_scale | float | r | Obtiene la escala máxima de brillo permitida.<br/>            El estiramiento real no superará este factor, para evitar un brillo excesivo. |
| target_white | int | r | Obtiene el valor blanco objetivo que el estiramiento pretende alcanzar. |


### Constructor: AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) {#AdaptiveWhiteStretchFilterOptions_is_grayscale_low_percentile_high_percentile_target_white_max_scale_1}


```
 AdaptiveWhiteStretchFilterOptions(is_grayscale, low_percentile, high_percentile, target_white, max_scale) 
```

Inicializa una nueva instancia de la clase [AdaptiveWhiteStretchFilter](/imaging/python-net/aspose.imaging.imagefilters/adaptivewhitestretchfilter/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| is_grayscale | bool | Indica si el filtro debe operar en modo escala de grises. |
| low_percentile | int | Percentil inferior para el punto negro (p. ej. 10). |
| high_percentile | int | Percentil superior para el punto blanco (p. ej. 90). |
| target_white | int | Valor blanco objetivo (p. ej. 240). |
| max_scale | float | Escala máxima de brillo permitida (p. ej. 1.7). |

