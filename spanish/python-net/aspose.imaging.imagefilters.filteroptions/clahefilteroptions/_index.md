---
title: "Clase ClaheFilterOptions"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Inicializa una nueva instancia de la clase [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            con los parámetros especificados. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| clip_limit | float | r | Obtiene el umbral de limitación de contraste.<br/>            Valores más altos permiten más contraste; valores más bajos limitan la mejora para evitar la amplificación del ruido. |
| is_grayscale | bool | r | Obtiene un valor que indica si el filtro opera en modo escala de grises. |
| tiles_number_horizontal | int | r | Obtiene el número de mosaicos en la dirección horizontal.<br/>            Determina cuántas regiones se divide la imagen horizontalmente para la ecualización de contraste local. |
| tiles_number_vertical | int | r | Obtiene el número de mosaicos en la dirección vertical.<br/>            Determina cuántas regiones se divide la imagen verticalmente para la ecualización de contraste local. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Inicializa una nueva instancia de la clase [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            con los parámetros especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| is_grayscale | bool | Indica si el filtro debe operar en modo escala de grises. |
| tiles_number_horizontal | int | Número de mosaicos horizontalmente. El valor predeterminado es 8. |
| tiles_number_vertical | int | Número de mosaicos verticalmente. El valor predeterminado es 8. |
| clip_limit | float | Umbral de limitación de contraste. El valor predeterminado es 4.0. |

