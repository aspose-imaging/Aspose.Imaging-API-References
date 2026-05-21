---
title: "الفئة GaussianDeconvolutionFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageFilters.FilterOptions.GaussianDeconvolutionFilterOptions. خيارات مرشح فك الالتفاف باستخدام تمويه غاوسي"
type: docs
weight: 10050
url: /ar/net/aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/
---
## GaussianDeconvolutionFilterOptions class

خيارات مرشح فك الالتفاف باستخدام التشويش الغاوسي.

```csharp
public abstract class GaussianDeconvolutionFilterOptions : DeconvolutionFilterOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GaussianDeconvolutionFilterOptions](gaussiandeconvolutionfilteroptions/)(int, double) | يقوم بإنشاء نسخة جديدة من الفئة `GaussianDeconvolutionFilterOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | يحصل أو يعيّن السطوع. النطاق الموصى به 1 - 1.5 القيمة الافتراضية = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`DeconvolutionFilterOptions`](../deconvolutionfilteroptions/) في وضع التدرج الرمادي. إرجاع وضع التدرج الرمادي أو وضع RGB. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
| virtual [Kernel](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/kernel/) { get; } | يحصل على النواة. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/radius/) { get; set; } | يحصل على نصف قطر نواة Gausseian ISquareConvolutionKernel. |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/sigma/) { get; set; } | يحصل على سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/size/) { get; set; } | يحصل على حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | يحصل أو يعيّن نسبة الإشارة إلى الضوضاء (SNR). النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |

### انظر أيضًا

* class [DeconvolutionFilterOptions](../deconvolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


