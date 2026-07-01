---
title: "ConvolutionFilterOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات مرشح الالتفاف."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.IConvolutionKernel
```
public class ConvolutionFilterOptions extends FilterOptionsBase implements IConvolutionKernel
```

خيارات مرشح الالتفاف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ConvolutionFilterOptions(double[][] kernel)](#ConvolutionFilterOptions-double-----) | ينشئ مثيلًا جديدًا للفئة [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) مع factor == 1 و bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor)](#ConvolutionFilterOptions-double-----double-) | ينشئ مثيلًا جديدًا للفئة [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) مع bias == 0. |
| [ConvolutionFilterOptions(double[][] kernel, double factor, int bias)](#ConvolutionFilterOptions-double-----double-int-) | ينشئ مثيلًا جديدًا للفئة [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getKernel()](#getKernel--) | يحصل على النواة. |
| [getFactor()](#getFactor--) | يحصل على العامل. |
| [setFactor(double value)](#setFactor-double-) | يضبط العامل. |
| [getBias()](#getBias--) | يحصل على الانحياز. |
| [setBias(int value)](#setBias-int-) | يضبط الانحياز. |
| [getIgnoreAlpha()](#getIgnoreAlpha--) | يحصل على قيمة تشير إلى ما إذا كان [ignore alpha]. |
| [setIgnoreAlpha(boolean value)](#setIgnoreAlpha-boolean-) | يضبط قيمة تشير إلى ما إذا كان [ignore alpha]. |
| [getBordersProcessing()](#getBordersProcessing--) | يحصل على قيمة تشير إلى ما إذا كان [borders processing]. |
| [setBordersProcessing(boolean value)](#setBordersProcessing-boolean-) | يضبط قيمة تشير إلى ما إذا كان [borders processing]. |
### ConvolutionFilterOptions(double[][] kernel) {#ConvolutionFilterOptions-double-----}
```
public ConvolutionFilterOptions(double[][] kernel)
```


ينشئ مثيلًا جديدًا للفئة [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) مع factor == 1 و bias == 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نواة | double[][] | نواة الالتفاف لاتجاه المحور X. |

### ConvolutionFilterOptions(double[][] kernel, double factor) {#ConvolutionFilterOptions-double-----double-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor)
```


ينشئ مثيلًا جديدًا للفئة [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions) مع bias == 0.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نواة | double[][] | نواة الالتفاف لاتجاه المحور X. |
| العامل | double | العامل. |

### ConvolutionFilterOptions(double[][] kernel, double factor, int bias) {#ConvolutionFilterOptions-double-----double-int-}
```
public ConvolutionFilterOptions(double[][] kernel, double factor, int bias)
```


ينشئ مثيلًا جديدًا للفئة [ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| نواة | double[][] | نواة الالتفاف لاتجاه المحور X. |
| العامل | double | العامل. |
| التحيز | int | قيمة الانحياز. |

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


يحصل على النواة.

**Returns:**
double[][] - النواة.
### getFactor() {#getFactor--}
```
public final double getFactor()
```


يحصل على العامل.

**Returns:**
double - العامل.
### setFactor(double value) {#setFactor-double-}
```
public final void setFactor(double value)
```


يضبط العامل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | double | العامل. |

### getBias() {#getBias--}
```
public final int getBias()
```


يحصل على الانحياز.

القيمة: الانحياز.

**Returns:**
int - الانحياز.
### setBias(int value) {#setBias-int-}
```
public final void setBias(int value)
```


يضبط الانحياز.

القيمة: الانحياز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الانحياز. |

### getIgnoreAlpha() {#getIgnoreAlpha--}
```
public final boolean getIgnoreAlpha()
```


يحصل على قيمة تشير إلى ما إذا كان [ignore alpha].

القيمة: `true` إذا كان [ignore alpha]؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان [ignore alpha].
### setIgnoreAlpha(boolean value) {#setIgnoreAlpha-boolean-}
```
public final void setIgnoreAlpha(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [ignore alpha].

القيمة: `true` إذا كان [ignore alpha]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان [ignore alpha]. |

### getBordersProcessing() {#getBordersProcessing--}
```
public final boolean getBordersProcessing()
```


يحصل على قيمة تشير إلى ما إذا كان [borders processing].

القيمة: `true` إذا كان [borders processing]؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هناك [معالجة الحدود].
### setBordersProcessing(boolean value) {#setBordersProcessing-boolean-}
```
public final void setBordersProcessing(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [borders processing].

القيمة: `true` إذا كان [borders processing]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان هناك [معالجة الحدود]. |

