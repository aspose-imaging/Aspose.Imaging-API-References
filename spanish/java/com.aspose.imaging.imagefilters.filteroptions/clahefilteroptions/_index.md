---
title: "ClaheFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Proporciona opciones para configurar el filtro CLAHE de Ecualización Adaptativa de Histograma con Limitación de Contraste."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Proporciona opciones para configurar el filtro Contrast-Limited Adaptive Histogram Equalization (CLAHE).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Inicializa una nueva instancia de la clase [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) con los parámetros especificados. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Obtiene un valor que indica si el filtro funciona en modo escala de grises. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Obtiene el número de mosaicos en la dirección horizontal. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Obtiene el número de mosaicos en la dirección vertical. |
| [getClipLimit()](#getClipLimit--) | Obtiene el umbral de limitación de contraste. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Inicializa una nueva instancia de la clase [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) con los parámetros especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isGrayscale | boolean | Indica si el filtro debe operar en modo escala de grises. |
| tilesNumberHorizontal | int | Número de mosaicos horizontalmente. El valor predeterminado es 8. |
| tilesNumberVertical | int | Número de mosaicos verticalmente. El valor predeterminado es 8. |
| clipLimit | double | Umbral de limitación de contraste. El valor predeterminado es 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Obtiene un valor que indica si el filtro funciona en modo escala de grises.

**Returns:**
boolean - un valor que indica si el filtro funciona en modo escala de grises.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Obtiene el número de mosaicos en la dirección horizontal. Determina cuántas regiones se divide la imagen horizontalmente para la ecualización local de contraste.

**Returns:**
int - el número de mosaicos en la dirección horizontal.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Obtiene el número de mosaicos en la dirección vertical. Determina cuántas regiones se divide la imagen verticalmente para la ecualización local de contraste.

**Returns:**
int - el número de mosaicos en la dirección vertical.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Obtiene el umbral de limitación de contraste. Los valores más altos permiten más contraste; los valores más bajos limitan la mejora para evitar la amplificación de ruido.

**Returns:**
double - el umbral de limitación de contraste.
