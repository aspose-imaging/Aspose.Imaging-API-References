---
title: "GaussianDeconvolutionFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات مرشح فك الالتفاف باستخدام الضبابية الغاوسية."
type: docs
weight: 20
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions
```
public abstract class GaussianDeconvolutionFilterOptions extends DeconvolutionFilterOptions implements IGaussianBlurOptions
```

خيارات مرشح فك الالتفاف باستخدام الضبابية الغاوسية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على حجم نواة Gaussian. |
| [setSize(int value)](#setSize-int-) | حجم نواة Gaussian. |
| [getSigma()](#getSigma--) | يحصل على سيغما نواة Gaussian (التنعيم). |
| [setSigma(double value)](#setSigma-double-) | معامل سيغما لنواة Gaussian (التنعيم). |
| [getRadius()](#getRadius--) | يحصل على نصف قطر Gausseian ISquareConvolutionKernel. |
| [setRadius(int value)](#setRadius-int-) | نصف قطر Gausseian ISquareConvolutionKernel. |
### getSize() {#getSize--}
```
public final int getSize()
```


يحصل على حجم نواة Gaussian. يجب أن يكون قيمة موجبة غير صفرية وفردية.

**Returns:**
int - حجم نواة Gaussian.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


حجم نواة Gaussian. يجب أن يكون قيمة موجبة غير صفرية وفردية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | حجم نواة Gaussian. |

### getSigma() {#getSigma--}
```
public final double getSigma()
```


يحصل على سيغما نواة Gaussian (التنعيم). يجب أن يكون قيمة موجبة غير صفرية.

**Returns:**
double - سيغما نواة Gaussian (التنعيم).
### setSigma(double value) {#setSigma-double-}
```
public final void setSigma(double value)
```


سيغما نواة Gaussian (التنعيم). يجب أن يكون قيمة موجبة غير صفرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | سيغما نواة Gaussian (التنعيم). |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


يحصل على نصف قطر Gausseian ISquareConvolutionKernel.

**Returns:**
int - نصف قطر Gausseian ISquareConvolutionKernel.
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


نصف قطر Gausseian ISquareConvolutionKernel.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نصف قطر Gausseian ISquareConvolutionKernel. |

