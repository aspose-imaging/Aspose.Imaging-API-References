---
title: "AdaptiveWhiteStretchFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Proporciona opciones para configurar el filtro Adaptive White Stretch."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Proporciona opciones para configurar el filtro Adaptive White Stretch. Permite personalizar los parámetros de estiramiento del histograma para mejorar el nivel de blanco y aumentar la legibilidad de textos tenues o imágenes de documentos con bajo contraste.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Inicializa una nueva instancia de la clase AdaptiveWhiteStretchFilter. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Inicializa una nueva instancia de la clase AdaptiveWhiteStretchFilter. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Obtiene un valor que indica si el filtro funciona en modo escala de grises. |
| [getLowPercentile()](#getLowPercentile--) | Obtiene el percentil inferior para el cálculo del punto negro. |
| [getHighPercentile()](#getHighPercentile--) | Obtiene el percentil superior para el cálculo del punto blanco. |
| [getTargetWhite()](#getTargetWhite--) | Obtiene el valor blanco objetivo que el estiramiento pretende alcanzar. |
| [getMaxScale()](#getMaxScale--) | Obtiene la escala de brillo máxima permitida. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Inicializa una nueva instancia de la clase AdaptiveWhiteStretchFilter.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Inicializa una nueva instancia de la clase AdaptiveWhiteStretchFilter.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isGrayscale | boolean | Indica si el filtro debe operar en modo escala de grises. |
| lowPercentile | int | Percentil inferior para el punto negro (p. ej. 10). |
| highPercentile | int | Percentil superior para el punto blanco (p. ej. 90). |
| targetWhite | int | Valor blanco objetivo (p. ej. 240). |
|  | maxScale | float | Escala máxima de brillo permitida (p. ej. 1.7). |

--------------------

El algoritmo estira el histograma de modo que el percentil blanco se acerque a `targetWhite`, pero sin exceder `maxScale` para evitar un brillo excesivo. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Obtiene un valor que indica si el filtro funciona en modo escala de grises.

**Returns:**
boolean - un valor que indica si el filtro funciona en modo escala de grises.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Obtiene el percentil inferior para el cálculo del punto negro. Los valores de píxel por debajo de este percentil se consideran negros durante el estiramiento.

**Returns:**
int - el percentil inferior para el cálculo del punto negro.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Obtiene el percentil superior para el cálculo del punto blanco. Los valores de píxel por encima de este percentil se consideran blancos durante el estiramiento.

**Returns:**
int - el percentil superior para el cálculo del punto blanco.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Obtiene el valor blanco objetivo que el estiramiento pretende alcanzar.

**Returns:**
int - el valor blanco objetivo que el estiramiento pretende lograr.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Obtiene la escala máxima de brillo permitida. El estiramiento real no superará este factor, para evitar un brillo excesivo.

**Returns:**
float - la escala máxima de brillo permitida.
