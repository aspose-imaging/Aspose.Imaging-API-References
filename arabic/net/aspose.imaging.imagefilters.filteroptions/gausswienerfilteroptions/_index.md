---
title: "الفئة GaussWienerFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions. خيارات مرشح غاوس واينر لإزالة تشويش الصورة"
type: docs
weight: 10030
url: /ar/net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
## GaussWienerFilterOptions class

خيارات مرشح Gauss Wiener لإزالة تشويش الصورة.

```csharp
public class GaussWienerFilterOptions : GaussianDeconvolutionFilterOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GaussWienerFilterOptions](gausswienerfilteroptions/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `GaussWienerFilterOptions`. |
| [GaussWienerFilterOptions](gausswienerfilteroptions/#constructor_1)(int, double) | يقوم بتهيئة نسخة جديدة من الفئة `GaussWienerFilterOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Brightness](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/brightness/) { get; set; } | يحصل أو يعيّن السطوع. النطاق الموصى به 1 - 1.5 القيمة الافتراضية = 1.15 |
| [Grayscale](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/grayscale/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا [`DeconvolutionFilterOptions`](../deconvolutionfilteroptions/) في وضع التدرج الرمادي. إرجاع وضع التدرج الرمادي أو وضع RGB. |
| [IsPartialLoaded](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/ispartialloaded/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل محملاً جزئياً. |
| override [Kernel](../../aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/kernel/) { get; } | يحصل على النواة. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/radius/) { get; set; } | يحصل على نصف قطر نواة Gausseian ISquareConvolutionKernel. |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/sigma/) { get; set; } | يحصل على سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions/size/) { get; set; } | يحصل على حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية. |
| [Snr](../../aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/snr/) { get; set; } | يحصل أو يعيّن نسبة الإشارة إلى الضوضاء (SNR). النطاق الموصى به 0.002 - 0.009، القيمة الافتراضية = 0.007 |

## أمثلة

المثال التالي يطبق أنواعًا مختلفة من الفلاتر على صورة نقطية.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // طبق مرشحًا متوسطًا بحجم مستطيل 5 على الصورة بالكامل.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // طبق مرشح تنعيم ثنائي الاتجاه بحجم نواة 5 على الصورة بالكامل.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // طبق مرشح Gauss-Wiener بنصف قطر 5 وقيمة تنعيم 4.0 على الصورة بالكامل.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // طبق مرشح حركة وينر بطول 5، قيمة تنعيم 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // طبق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### انظر أيضًا

* class [GaussianDeconvolutionFilterOptions](../gaussiandeconvolutionfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


