---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones del filtro de deconvolución usando desenfoque gaussiano."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Las opciones del filtro de deconvolución usando desenfoque gaussiano.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene el tamaño del núcleo gaussiano. |
| [setSize(int value)](#setSize-int-) | El tamaño del kernel gaussiano. |
| [getSigma()](#getSigma--) | Obtiene la sigma del núcleo gaussiano (suavizado). |
| [setSigma(double value)](#setSigma-double-) | El sigma del kernel gaussiano (suavizado). |
| [getRadius()](#getRadius--) | Obtiene el radio de Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | El radio de Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene el tamaño del kernel gaussiano. Debe ser un valor impar positivo distinto de cero.

**Returns:**
int - el tamaño del kernel gaussiano.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


El tamaño del kernel gaussiano. Debe ser un valor impar positivo distinto de cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tamaño del kernel gaussiano. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Obtiene el sigma del kernel gaussiano (suavizado). Debe ser un valor positivo distinto de cero.

**Returns:**
double - el sigma del kernel gaussiano (suavizado).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


El sigma del kernel gaussiano (suavizado). Debe ser un valor positivo distinto de cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | el sigma del kernel gaussiano (suavizado). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Obtiene el radio de Gausseian ISquareConvolutionKernel.

**Returns:**
int - el radio de Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


El radio de Gausseian ISquareConvolutionKernel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el radio de Gausseian ISquareConvolutionKernel. |

