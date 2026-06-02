---
title: "DjvuImage.ResizeHeightProportionally"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تسمح طريقة ResizeHeightProportionally بتعديل ارتفاع صورتك مع الحفاظ على نسبة العرض إلى الارتفاع. هذا يضمن بقاء صورتك على نسبها الأصلية، مما يمنع التشويه ويحافظ على سلامتها البصرية. سواءً كنت تُحسّن الصور لصفحات الويب أو التطبيقات المحمولة أو الوسائط المطبوعة، فإن هذه الطريقة تضمن أن تبدو صورك بأفضل شكل عبر مختلف المنصات والأجهزة."
type: docs
weight: 270
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/
---
## DjvuImage.ResizeHeightProportionally method

تتيح لك طريقة `ResizeHeightProportionally` ضبط ارتفاع صورتك مع الحفاظ على نسبة أبعادها. يضمن ذلك بقاء الصورة على نسبها، مما يمنع التشويه ويحافظ على سلامتها البصرية. سواءً كنت تُحسّن الصور لصفحات الويب، أو تطبيقات الهواتف المحمولة، أو الوسائط المطبوعة، فإن هذه الطريقة تضمن أن تبدو صورك بأفضل شكل عبر مختلف المنصات والأجهزة.

```csharp
public override void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يحمل صورة DJVU ويعيد تحجيمها بنسبة مئوية باستخدام طرق تحجيم مختلفة. يتم تحديد الارتفاع فقط، ويُحسب العرض تلقائيًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


