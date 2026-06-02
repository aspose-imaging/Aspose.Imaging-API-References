---
title: "فئة DeconvolutionFilterOptions"
type: docs
weight: 70
url: /ar/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---

**Summary:** Deconvolution Filter Options, abstract class

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_1) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [DeconvolutionFilterOptions(kernel)](#DeconvolutionFilterOptions_kernel_2) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| السطوع | float | r/w | يحصل أو يضبط السطوع.<br/>            النطاق الموصى به 1 - 1.5<br/>            القيمة الافتراضية = 1.15 |
| grayscale | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) في وضع التدرج الرمادي.<br/>            إرجاع وضع التدرج الرمادي أو وضع RGB. |
| is_partial_loaded | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
| kernel_data | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | r | يحصل على النواة. |
| snr | float | r/w | يحصل أو يضبط SNR (نسبة الإشارة إلى الضوضاء)<br/>            النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_complex(kernel)](#create_with_complex_kernel_1) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |
| [create_with_double(kernel)](#create_with_double_kernel_2) | ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/). |


### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_1}


```
 DeconvolutionFilterOptions(kernel) 
```

ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| نواة | float[] | النواة. |

### Constructor: DeconvolutionFilterOptions(kernel) {#DeconvolutionFilterOptions_kernel_2}


```
 DeconvolutionFilterOptions(kernel) 
```

ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | النواة. |

### Method: create_with_complex(kernel)  [static] {#create_with_complex_kernel_1}


```
 create_with_complex(kernel) 
```

ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| kernel | [Complex[]](/imaging/python-net/aspose.imaging.imagefilters.complexutils/complex/) | نواة Complex[] . |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


### Method: create_with_double(kernel)  [static] {#create_with_double_kernel_2}


```
 create_with_double(kernel) 
```

ينشئ مثيلاً جديداً من الفئة [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| نواة | float[] | نواة double[] . |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) |  |


