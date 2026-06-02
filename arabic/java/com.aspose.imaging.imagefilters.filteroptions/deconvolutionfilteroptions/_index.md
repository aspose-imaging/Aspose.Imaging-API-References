---
title: "DeconvolutionFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة مجردة Deconvolution Filter Options"
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IComplexConvolutionKernel
```
public class DeconvolutionFilterOptions extends FilterOptionsBase implements IComplexConvolutionKernel
```

خيارات مرشح فك الالتفاف، فئة مجردة
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DeconvolutionFilterOptions(double[][] kernel)](#DeconvolutionFilterOptions-double-----) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
| [DeconvolutionFilterOptions(Complex[][] kernel)](#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getKernel()](#getKernel--) | يحصل على النواة. |
| [getSnr()](#getSnr--) | يحصل أو يضبط قيمة SNR (نسبة الإشارة إلى الضوضاء) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |
| [setSnr(double value)](#setSnr-double-) | يحصل أو يضبط قيمة SNR (نسبة الإشارة إلى الضوضاء) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |
| [getBrightness()](#getBrightness--) | يحصل أو يضبط السطوع. |
| [setBrightness(double value)](#setBrightness-double-) | يحصل أو يضبط السطوع. |
| [getGrayscale()](#getGrayscale--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `DeconvolutionFilterOptions` بالأبيض والأسود. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `DeconvolutionFilterOptions` بالأبيض والأسود. |
| [isPartialLoaded()](#isPartialLoaded--) | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
### DeconvolutionFilterOptions(double[][] kernel) {#DeconvolutionFilterOptions-double-----}
```
public DeconvolutionFilterOptions(double[][] kernel)
```


ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نواة | double[][] | النواة. |

### DeconvolutionFilterOptions(Complex[][] kernel) {#DeconvolutionFilterOptions-com.aspose.imaging.imagefilters.complexutils.Complex-----}
```
public DeconvolutionFilterOptions(Complex[][] kernel)
```


ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| kernel | [Complex\[\]](../../com.aspose.imaging.imagefilters.complexutils/complex) | النواة. |

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


يحصل على النواة.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - النواة.
### getSnr() {#getSnr--}
```
public double getSnr()
```


يحصل أو يضبط قيمة SNR (نسبة الإشارة إلى الضوضاء) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007

القيمة: الـ SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


يحصل أو يضبط قيمة SNR (نسبة الإشارة إلى الضوضاء) النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007

القيمة: الـ SNR.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


يحصل أو يعيّن السطوع. النطاق الموصى به 1 - 1.5 القيمة الافتراضية = 1.15

القيمة: السطوع.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


يحصل أو يعيّن السطوع. النطاق الموصى به 1 - 1.5 القيمة الافتراضية = 1.15

القيمة: السطوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `DeconvolutionFilterOptions` بالأبيض والأسود. إرجاع وضع الأبيض والأسود أو وضع RGB.

القيمة: `true` إذا كان بالأبيض والأسود؛ وإلا `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا `DeconvolutionFilterOptions` بالأبيض والأسود. إرجاع وضع الأبيض والأسود أو وضع RGB.

القيمة: `true` إذا كان بالأبيض والأسود؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً.

القيمة: `true` إذا كان هذا الكائن محملاً جزئياً؛ وإلا `false`.

**Returns:**
boolean
