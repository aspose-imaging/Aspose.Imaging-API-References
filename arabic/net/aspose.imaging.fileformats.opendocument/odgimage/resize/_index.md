---
title: "OdgImage.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة OdgImage. تساعد هذه الطريقة المطورين على تغيير حجم الصور برمجياً. من خلال استدعاء هذه الدالة يمكنك تعديل أبعاد الصور ديناميكياً لتلبية المتطلبات أو القيود المحددة داخل تطبيقاتهم."
type: docs
weight: 50
url: /ar/net/aspose.imaging.fileformats.opendocument/odgimage/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

تساعد هذه الطريقة المطورين على تغيير حجم الصور برمجياً. من خلال استدعاء هذه الدالة، يمكنك تعديل أبعاد الصور ديناميكياً لتلبية المتطلبات أو القيود المحددة داخل تطبيقاتهم.

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
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

تسهل هذه الطريقة تعديل حجم الصورة مع تحكم دقيق في عرض وارتفاع ومعلمات نوع التغيير. يمكنك تحديد الأبعاد المطلوبة واختيار من بين خوارزميات أو أنواع تغيير الحجم المختلفة لتحقيق أفضل النتائج وفقاً لمتطلبات التطبيق.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يحمل صورة ODG متعددة الصفحات ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.OpenDocument.OdgImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [OdgImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odgimage/)
* assembly [Aspose.Imaging](../../../)


