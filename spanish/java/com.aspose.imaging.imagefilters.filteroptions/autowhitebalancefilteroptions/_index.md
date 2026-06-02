---
title: "AutoWhiteBalanceFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Proporciona opciones de configuración para el filtro Auto White Balance."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Proporciona opciones de configuración para el filtro Auto White Balance. Permite ajustar los parámetros de estiramiento de contraste y el escalado de canales para mejorar la apariencia de las imágenes digitales.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Inicializa una nueva instancia de la clase [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Obtiene el percentil alto objetivo para el estiramiento de contraste. |
| [getTargetValue()](#getTargetValue--) | Obtiene el valor objetivo para el percentil alto. |
| [getMaxScale()](#getMaxScale--) | Obtiene el factor máximo de escalado para cada canal. |
| [getLowPercentile()](#getLowPercentile--) | El percentil bajo para el punto negro, usado para la protección de sombras (predeterminado: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Desplazamiento desde el percentil bajo por debajo del cual los píxeles oscuros no se estiran (protección). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Inicializa una nueva instancia de la clase [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lowPercentile | int | El percentil bajo para el punto negro, usado para la protección de sombras (predeterminado: 3). |
| targetHighPercentile | int | El percentil alto objetivo para el estiramiento de contraste (predeterminado 97). |
| targetValue | int | El valor objetivo para el percentil alto (valor predeterminado 255). |
| maxScale | float | El factor máximo de escala para cada canal (valor predeterminado 1.4f). |
| protectedDarkOffset | int | Desplazamiento desde el percentil bajo por debajo del cual los píxeles oscuros no se estiran (protección). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Obtiene el percentil alto objetivo para el estiramiento de contraste. Determina qué percentil de brillo se mapeará al valor objetivo.

**Returns:**
int - el percentil alto objetivo para el estiramiento de contraste.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Obtiene el valor objetivo para el percentil alto. Este valor se utilizará como referencia blanca para el estiramiento de contraste.

**Returns:**
int - el valor objetivo para el percentil alto.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Obtiene el factor máximo de escala para cada canal. Restringe la amplificación de cualquier canal para evitar cambios de color excesivos.

**Returns:**
float - el factor máximo de escala para cada canal.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


El percentil bajo para el punto negro, usado para la protección de sombras (predeterminado: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Desplazamiento desde el percentil bajo por debajo del cual los píxeles oscuros no se estiran (protección).

**Returns:**
int
