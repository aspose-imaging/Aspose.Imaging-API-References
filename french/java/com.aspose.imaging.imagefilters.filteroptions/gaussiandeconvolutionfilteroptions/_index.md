---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options du filtre de déconvolution utilisant le flou gaussien."
type: docs
weight: 20
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Les options du filtre de déconvolution utilisant le flou gaussien.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Obtient la taille du noyau gaussien. |
| [setSize(int value)](#setSize-int-) | La taille du noyau gaussien. |
| [getSigma()](#getSigma--) | Obtient le sigma du noyau gaussien (lissage). |
| [setSigma(double value)](#setSigma-double-) | Le Gaussian kernel sigma (lissage). |
| [getRadius()](#getRadius--) | Obtient le rayon du Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Le rayon du Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Obtient la taille du Gaussian kernel. Doit être une valeur impaire positive non nulle.

**Returns:**
int - la taille du Gaussian kernel.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


La taille du Gaussian kernel. Doit être une valeur impaire positive non nulle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la taille du Gaussian kernel. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Obtient le Gaussian kernel sigma (lissage). Doit être une valeur positive non nulle.

**Returns:**
double - le Gaussian kernel sigma (lissage).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Le Gaussian kernel sigma (lissage). Doit être une valeur positive non nulle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | le Gaussian kernel sigma (lissage). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Obtient le rayon du Gausseian ISquareConvolutionKernel.

**Returns:**
int - le rayon du Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Le rayon du Gausseian ISquareConvolutionKernel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le rayon du Gausseian ISquareConvolutionKernel. |

