---
title: "TiffImage.ResizeWidthProportionally"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. ضبط عرض الصورة مع الحفاظ على نسبة الأبعاد لضمان تغيير الحجم بشكل متناسب للحصول على عرض بصري مثالي. استخدم هذه الطريقة لتغيير حجم الصور ديناميكيًا داخل تطبيقك، مما يسهل عرضًا متسقًا وجذابًا عبر مختلف سياقات العرض."
type: docs
weight: 360
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/
---
## TiffImage.ResizeWidthProportionally method

اضبط عرض الصورة مع الحفاظ على نسبة العرض إلى الارتفاع، مما يضمن تغيير حجم نسبي لتقديم بصري مثالي. استخدم هذه الطريقة لتكبير الصور ديناميكيًا داخل تطبيقك، مما يسهل عرضًا ثابتًا وجذابًا عبر مختلف سياقات العرض.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يحمل صورة TIFF ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد العرض فقط، ويتم حساب الارتفاع تلقائيًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // حفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


