---
title: "WebPImage.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة WebPImage. تغيير حجم الصورة وضبط أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. دمج هذه الطريقة في سير عمل معالجة الصور الخاصة بك لتكبير أو تصغير الصور ديناميكيًا لتلبية متطلبات العرض أو التخزين المختلفة داخل تطبيقك."
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

تغيير حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. دمج هذه الطريقة في سير عمل معالجة الصور لتكبير الصور ديناميكيًا لتتناسب مع متطلبات العرض أو التخزين المختلفة داخل تطبيقك.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يحمل صورة WEBP ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Webp.WebPImage image = (Aspose.Imaging.FileFormats.Webp.WebPImage)Aspose.Imaging.Image.Load(dir + "sample.webp"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

تغيير حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تعديل حجم مخصصة وفقًا لمتطلبات تطبيقك المحددة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات التحجيم. |

### انظر أيضًا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


