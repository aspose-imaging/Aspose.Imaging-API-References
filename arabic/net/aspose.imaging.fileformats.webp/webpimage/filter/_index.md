---
title: "WebPImage.Filter"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WebPImage. تصفية المحتوى داخل المستطيل المحدد بتطبيق مرشح معالجة صور مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات أو تحويلات مستهدفة داخل تطبيقك."
type: docs
weight: 180
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/filter/
---
## WebPImage.Filter method

تصفية المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صورة مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور لتحقيق تحسينات أو تحويلات مستهدفة داخل تطبيقك.

```csharp
public override void Filter(Rectangle rectangle, FilterOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المستطيل | Rectangle | المستطيل. |
| الخيارات | FilterOptionsBase | الخيارات. |

## أمثلة

المثال التالي يطبق أنواعًا مختلفة من المرشحات على صورة WEBP.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // طبق مرشحًا متوسطًا بحجم مستطيل 5 على الصورة بالكامل.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MedianFilterOptions(5));
    webpImage.Save(dir + "sample.MedianFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // طبق مرشح تنعيم ثنائي الاتجاه بحجم نواة 5 على الصورة بالكامل.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.BilateralSmoothingFilterOptions(5));
    webpImage.Save(dir + "sample.BilateralSmoothingFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.GaussianBlurFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // طبق مرشح Gauss-Wiener بنصف قطر 5 وقيمة تنعيم 4.0 على الصورة بالكامل.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.GaussWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // طبق مرشح حركة وينر بطول 5، قيمة تنعيم 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.Save(dir + "sample.MotionWienerFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // طبق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    webpImage.Filter(webpImage.Bounds, new Aspose.Imaging.ImageFilters.FilterOptions.SharpenFilterOptions(5, 4.0));
    webpImage.Save(dir + "sample.SharpenFilter.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [FilterOptionsBase](../../../aspose.imaging.imagefilters.filteroptions/filteroptionsbase/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


