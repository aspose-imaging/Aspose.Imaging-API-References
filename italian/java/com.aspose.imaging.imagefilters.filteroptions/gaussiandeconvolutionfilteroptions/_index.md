---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni del filtro di deconvoluzione usando la sfocatura gaussiana."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Le opzioni del filtro di deconvoluzione usando la sfocatura gaussiana.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene la dimensione del kernel Gaussian. |
| [setSize(int value)](#setSize-int-) | La dimensione del kernel gaussiano. |
| [getSigma()](#getSigma--) | Ottiene la sigma del kernel Gaussian (smussatura). |
| [setSigma(double value)](#setSigma-double-) | Il Gaussian kernel sigma (smussatura). |
| [getRadius()](#getRadius--) | Restituisce il raggio di Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Il raggio di Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Ottiene la dimensione del kernel Gaussian. Deve essere un valore dispari positivo diverso da zero.

**Returns:**
int - la dimensione del kernel Gaussian.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


La dimensione del kernel Gaussian. Deve essere un valore dispari positivo diverso da zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la dimensione del kernel Gaussian. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Ottiene il sigma del kernel Gaussian (smussatura). Deve essere un valore positivo diverso da zero.

**Returns:**
double - il sigma del kernel Gaussian (smussatura).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Il sigma del kernel Gaussian (smussatura). Deve essere un valore positivo diverso da zero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | il sigma del kernel Gaussian (smussatura). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Restituisce il raggio di Gausseian ISquareConvolutionKernel.

**Returns:**
int - il raggio di Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Il raggio di Gausseian ISquareConvolutionKernel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il raggio di Gausseian ISquareConvolutionKernel. |

