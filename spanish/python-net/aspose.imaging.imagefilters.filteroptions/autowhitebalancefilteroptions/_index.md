---
title: "Clase AutoWhiteBalanceFilterOptions"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Inicializa una nueva instancia de la clase [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| low_percentile | int | r | El percentil bajo para el punto negro, usado para la protección de sombras (predeterminado: 3). |
| max_scale | float | r | Obtiene el factor máximo de escala para cada canal.<br/>            Restringe la amplificación de cualquier canal para evitar cambios de color excesivos. |
| protected_dark_offset | int | r | Desplazamiento desde el percentil bajo por debajo del cual los píxeles oscuros no se estiran (protección). |
| target_high_percentile | int | r | Obtiene el percentil alto objetivo para el estiramiento de contraste.<br/>            Determina qué percentil de brillo se asignará al valor objetivo. |
| target_value | int | r | Obtiene el valor objetivo para el percentil alto.<br/>            Este valor se utilizará como referencia blanca para el estiramiento de contraste. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Inicializa una nueva instancia de la clase [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| low_percentile | int | El percentil bajo para el punto negro, usado para la protección de sombras (predeterminado: 3). |
| target_high_percentile | int | El percentil alto objetivo para el estiramiento de contraste (valor predeterminado 97). |
| target_value | int | El valor objetivo para el percentil alto (valor predeterminado 255). |
| max_scale | float | El factor máximo de escala para cada canal (valor predeterminado 1.4f). |
| protected_dark_offset | int | Desplazamiento desde el percentil bajo por debajo del cual los píxeles oscuros no se estiran (protección). |

