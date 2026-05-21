---
title: "الفئة SharpenFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions. خيارات الفلتر لتقوية الحدة"
type: docs
weight: 10100
url: /ar/net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
## SharpenFilterOptions class

خيارات مرشح التحسين.

```csharp
public class SharpenFilterOptions : GaussianBlurFilterOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SharpenFilterOptions](sharpenfilteroptions/#constructor)() | يقوم بإنشاء نسخة جديدة من الفئة `SharpenFilterOptions`. |
| [SharpenFilterOptions](sharpenfilteroptions/#constructor_1)(int, double) | يقوم بإنشاء نسخة جديدة من الفئة `SharpenFilterOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Bias](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bias/) { get; set; } | يحصل أو يعيّن الانحياز. |
| [BordersProcessing](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bordersprocessing/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم معالجة [borders processing]. |
| [Factor](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/factor/) { get; set; } | يحصل أو يعيّن العامل. |
| [IgnoreAlpha](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/ignorealpha/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يتم [ignore alpha]. |
| override [Kernel](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/kernel/) { get; } | يحصل على النواة. |
| [Radius](../../aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/radius/) { get; set; } | يحصل على نصف قطر نواة Gausseian ISquareConvolutionKernel. |
| override [Sigma](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/sigma/) { get; set; } | يحصل على سيغما نواة Gaussian (التنعيم). يجب أن تكون قيمة موجبة غير صفرية. |
| override [Size](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/size/) { get; set; } | يحصل على حجم نواة Gaussian. يجب أن تكون قيمة موجبة غير صفرية وفردية. |

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

* class [GaussianBlurFilterOptions](../gaussianblurfilteroptions/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


