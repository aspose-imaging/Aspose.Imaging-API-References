---
title: "GifImage.Filter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تطبيق مرشح محدد على المنطقة المحددة من الصورة لتعزيز جودتها البصرية أو تعديل مظهرها حسب الرغبة. تقوم هذه الطريقة بمعالجة البكسلات داخل المستطيل المحدد بشكل انتقائي، مما يسمح بإجراء تعديلات مستهدفة مع الحفاظ على سلامة بيانات الصورة المحيطة."
type: docs
weight: 300
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/filter/
---
## GifImage.Filter method

طبق مرشحًا محددًا على المنطقة المخصصة من الصورة، معززًا جودتها البصرية أو معدلاً مظهرها حسب الرغبة. تقوم هذه الطريقة بمعالجة البكسلات داخل المستطيل المحدد بشكل انتقائي، مما يسمح بإجراء تعديلات مستهدفة مع الحفاظ على سلامة بيانات الصورة المحيطة.

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |
| الخيارات | FilterOptionsBase | الخيارات. |

## أمثلة

المثال التالي يطبق أنواعًا مختلفة من المرشحات على صورة GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // طبق مرشحًا متوسطًا بحجم مستطيل 5 على الصورة بالكامل.
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    gifImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // طبق مرشح تنعيم ثنائي الاتجاه بحجم نواة 5 على الصورة بالكامل.
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    gifImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // طبق مرشح Gauss-Wiener بنصف قطر 5 وقيمة تنعيم 4.0 على الصورة بالكامل.
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // طبق مرشح حركة وينر بطول 5، قيمة تنعيم 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // طبق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    gifImage.Filter(gifImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    gifImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


