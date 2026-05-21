---
title: "DjvuImage.Filter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تطبيق فلاتر على منطقة مستطيلة محددة داخل الصورة لتحسين مظهرها أو تعديلها. من خلال استهداف مناطق معينة تسمح هذه الطريقة بإجراء تعديلات دقيقة مثل التشويش أو الشحذ أو تطبيق تأثيرات فنية لتحقيق النتائج البصرية المطلوبة. ضبط الفلاتر بدقة على المناطق المختارة يمكن المستخدمين من تخصيص جمالية الصورة، تحسين الوضوح، وإنشاء تأثيرات فنية مخصصة لتفضيلاتهم."
type: docs
weight: 240
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/filter/
---
## DjvuImage.Filter method

طبق الفلاتر على منطقة مستطيلة محددة داخل الصورة لتحسين أو تعديل مظهرها. من خلال استهداف مناطق معينة، تسمح هذه الطريقة بإجراء تعديلات دقيقة، مثل التشويش، أو الشحذ، أو تطبيق تأثيرات فنية، لتحقيق النتائج البصرية المطلوبة. يتيح ضبط الفلاتر على المناطق المختارة للمستخدمين تخصيص جمالية الصورة، تحسين الوضوح، وإنشاء تأثيرات فنية تتناسب مع تفضيلاتهم.

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |
| الخيارات | FilterOptionsBase | الخيارات. |

## أمثلة

المثال التالي يطبق أنواعًا مختلفة من الفلاتر على صورة DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // طبق مرشحًا متوسطًا بحجم مستطيل 5 على الصورة بالكامل.
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    djvuImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // طبق مرشح تنعيم ثنائي الاتجاه بحجم نواة 5 على الصورة بالكامل.
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    djvuImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // طبق مرشح Gauss-Wiener بنصف قطر 5 وقيمة تنعيم 4.0 على الصورة بالكامل.
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // طبق مرشح حركة وينر بطول 5، قيمة تنعيم 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // طبق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    djvuImage.Filter(djvuImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    djvuImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


