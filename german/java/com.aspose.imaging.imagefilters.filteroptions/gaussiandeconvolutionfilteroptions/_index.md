---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Deconvolution-Filteroptionen mittels Gaußscher Unschärfe."
type: docs
weight: 20
url: /de/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Die Deconvolution-Filteroptionen mittels Gaußscher Unschärfe.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liefert die Größe des Gauß‑Kernels. |
| [setSize(int value)](#setSize-int-) | Die Größe des Gaußschen Kernels. |
| [getSigma()](#getSigma--) | Liefert das Sigma des Gauß‑Kernels (Glättung). |
| [setSigma(double value)](#setSigma-double-) | Der gaußsche Kernel‑Sigma (Glättung). |
| [getRadius()](#getRadius--) | Gibt den Radius des Gausseian ISquareConvolutionKernel zurück. |
| [setRadius(int value)](#setRadius-int-) | Der Radius des Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Liefert die Größe des gaußschen Kernels. Muss ein positiver, von Null verschiedener, ungerader Wert sein.

**Returns:**
int - die Größe des gaußschen Kernels.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Die Größe des gaußschen Kernels. Muss ein positiver, von Null verschiedener, ungerader Wert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Größe des gaußschen Kernels. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Liefert den gaußschen Kernel‑Sigma (Glättung). Muss ein positiver, von Null verschiedener Wert sein.

**Returns:**
double - der gaußsche Kernel‑Sigma (Glättung).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Der gaußsche Kernel‑Sigma (Glättung). Muss ein positiver, von Null verschiedener Wert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double | der gaußsche Kernel‑Sigma (Glättung). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Gibt den Radius des Gausseian ISquareConvolutionKernel zurück.

**Returns:**
int - der Radius des Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Der Radius des Gausseian ISquareConvolutionKernel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Radius des Gausseian ISquareConvolutionKernel. |

