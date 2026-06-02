---
title: "RasterImage.Filter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تصفي المستطيل المحدد"
type: docs
weight: 300
url: /ar/net/aspose.imaging/rasterimage/filter/
---
## RasterImage.Filter method

يفلتر المستطيل المحدد.

```csharp
public virtual void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |
| الخيارات | FilterOptionsBase | الخيارات. |

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

* struct [Rectangle](../../rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


