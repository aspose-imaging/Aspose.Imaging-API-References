---
title: SharpenFilterOptions
second_title: Aspose.Imaging لمرجع NET API
description: خيارات مرشح Sharpen
type: docs
weight: 9810
url: /ar/net/aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
## SharpenFilterOptions class

خيارات مرشح Sharpen

```csharp
public class SharpenFilterOptions : ConvolutionFilterOptions
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SharpenFilterOptions](sharpenfilteroptions#constructor)() | يقوم بتهيئة مثيل جديد لملف[`SharpenFilterOptions`](../sharpenfilteroptions)class. بالإعدادات الافتراضية . |
| [SharpenFilterOptions](sharpenfilteroptions#constructor_1)(int, double) | يقوم بتهيئة مثيل جديد لملف[`SharpenFilterOptions`](../sharpenfilteroptions) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Bias](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/bias) { get; set; } | الحصول على التحيز أو تعيينه . |
| [Factor](../../aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions/factor) { get; set; } | الحصول على العامل أو تعيينه . |
| [Sigma](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/sigma) { get; set; } | الحصول على أو تعيين سيجما . |
| [Size](../../aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/size) { get; set; } | الحصول على الحجم أو تحديده. |

### أمثلة

يطبق المثال التالي أنواعًا مختلفة من المرشحات على صورة نقطية.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    rasterImage.Save(dir + "sample.MedianFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتطبيق مرشح تجانس ثنائي بحجم نواة 5 على الصورة بأكملها.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    rasterImage.Save(dir + "sample.BilateralSmoothingFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتطبيق مرشح Gaussian blur بنصف قطر 5 وقيمة سيجما 4.0 على الصورة بأكملها.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussianBlurFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتطبيق مرشح Gauss-Wiener بنصف قطر 5 وقيمة سلسة 4.0 للصورة بأكملها.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.GaussWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتطبيق مرشح wiener للحركة بطول 5 ، وقيمة سلسة 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.Save(dir + "sample.MotionWienerFilter.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتطبيق مرشح حاد بحجم نواة 5 وقيمة سيجما 4.0 على الصورة بأكملها.
    rasterImage.Filter(rasterImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    rasterImage.Save(dir + "sample.SharpenFilter.png");
}
```

### أنظر أيضا

* class [ConvolutionFilterOptions](../convolutionfilteroptions)
* مساحة الاسم [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->