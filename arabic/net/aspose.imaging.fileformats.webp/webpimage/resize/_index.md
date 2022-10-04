---
title: Resize
second_title: Aspose.Imaging لمرجع NET API
description: يغير حجم الصورة.
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

يغير حجم الصورة.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

### أمثلة

يقوم هذا المثال بتحميل صورة WEBP وتغيير حجمها باستخدام طرق تغيير الحجم المختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // قم بالزيادة بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // تصغير بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // قم بالارتقاء بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // تصغير بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ في PNG مع الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

يغير حجم الصورة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| settings | ImageResizeSettings | إعدادات تغيير الحجم. |

### أنظر أيضا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->