---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging för Java API-referens"
description: "Deconvolution-filteralternativen som använder Gaussian blur."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Deconvolution-filteralternativen som använder Gaussian blur.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar den Gaussiska kärnans storlek. |
| [setSize(int value)](#setSize-int-) | Den gaussiska kärnans storlek. |
| [getSigma()](#getSigma--) | Hämtar den Gaussiska kärnans sigma (utjämning). |
| [setSigma(double value)](#setSigma-double-) | Den Gaussiska kärnans sigma (utjämning). |
| [getRadius()](#getRadius--) | Hämtar radien för Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | Radien för Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


Hämtar den Gaussiska kärnans storlek. Måste vara ett positivt, icke‑noll, udda värde.

**Returns:**
int - den Gaussiska kärnans storlek.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Den Gaussiska kärnans storlek. Måste vara ett positivt, icke‑noll, udda värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | den Gaussiska kärnans storlek. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Hämtar den Gaussiska kärnans sigma (utjämning). Måste vara ett positivt, icke‑noll värde.

**Returns:**
double - den Gaussiska kärnans sigma (utjämning).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Den Gaussiska kärnans sigma (utjämning). Måste vara ett positivt, icke‑noll värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | den Gaussiska kärnans sigma (utjämning). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Hämtar radien för Gausseian ISquareConvolutionKernel.

**Returns:**
int – radien för Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Radien för Gausseian ISquareConvolutionKernel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | radien för Gausseian ISquareConvolutionKernel. |

