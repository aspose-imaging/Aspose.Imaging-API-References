---
title: "الفئة BilateralSmoothingFilterOptions"
second_title: "Aspose.Imaging for .NET API Reference"
description: "فئة Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions. خيارات مرشح التنعيم الثنائي"
type: docs
weight: 9970
url: /ar/net/aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
## BilateralSmoothingFilterOptions class

خيارات مرشح التنعيم الثنائي.

```csharp
public class BilateralSmoothingFilterOptions : FilterOptionsBase
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions/#constructor)() | يقوم بتهيئة نسخة جديدة من الفئة `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions](bilateralsmoothingfilteroptions/#constructor_1)(int) | يقوم بتهيئة نسخة جديدة من الفئة `BilateralSmoothingFilterOptions`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorfactor/) { get; set; } | يحصل أو يعيّن معامل اللون. |
| [ColorPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/colorpower/) { get; set; } | يحصل أو يعيّن قوة اللون. |
| [Size](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/size/) { get; set; } | يحصل أو يعيّن حجم النواة. |
| [SpatialFactor](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialfactor/) { get; set; } | يحصل أو يعيّن معامل الفضاء. |
| [SpatialPower](../../aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/spatialpower/) { get; set; } | يحصل أو يضبط القدرة المكانية. |

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

* class [FilterOptionsBase](../filteroptionsbase/)
* namespace [Aspose.Imaging.ImageFilters.FilterOptions](../../aspose.imaging.imagefilters.filteroptions/)
* assembly [Aspose.Imaging](../../)


