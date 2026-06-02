---
title: "GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gaussian bulanıklaştırma kullanan dekonvolüsyon filtre seçenekleri."
type: docs
weight: 20
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

Gaussian bulanıklaştırma kullanan dekonvolüsyon filtre seçenekleri.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSize()](#getSize--) | Gauss çekirdeği boyutunu alır. |
| [setSize(int value)](#setSize-int-) | Gauss çekirdeği boyutu. |
| [getSigma()](#getSigma--) | Gauss çekirdeği sigma (yumuşatma) değerini alır. |
| [setSigma(double value)](#setSigma-double-) | Gaussian çekirdek sigma (düzleştirme). |
| [getRadius()](#getRadius--) | Gausseian ISquareConvolutionKernel'in yarıçapını alır. |
| [setRadius(int value)](#setRadius-int-) | Gausseian ISquareConvolutionKernel'in yarıçapı. |
### getSize() {#getSize--}
```
public final int getSize()
```


Gaussian çekirdek boyutunu alır. Pozitif, sıfırdan farklı ve tek bir değer olmalıdır.

**Returns:**
int - Gaussian çekirdek boyutu.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Gaussian çekirdek boyutu. Pozitif, sıfırdan farklı ve tek bir değer olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Gaussian çekirdek boyutu. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


Gaussian çekirdek sigma (düzleştirme) alır. Pozitif, sıfırdan farklı bir değer olmalıdır.

**Returns:**
double - Gaussian çekirdek sigma (düzleştirme).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


Gaussian çekirdek sigma (düzleştirme). Pozitif, sıfırdan farklı bir değer olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Gaussian çekirdek sigma (düzleştirme). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


Gausseian ISquareConvolutionKernel'in yarıçapını alır.

**Returns:**
int - Gausseian ISquareConvolutionKernel'in yarıçapı.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Gausseian ISquareConvolutionKernel'in yarıçapı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Gausseian ISquareConvolutionKernel'in yarıçapı. |

