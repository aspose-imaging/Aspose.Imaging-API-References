---
title: "TiffImage.Resize"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة TiffImage. قم بتغيير حجم الصورة وفقًا لنوع التحجيم المحدد لتسهيل تعديل أبعاد الصورة بمرونة مع الحفاظ على نسبة العرض إلى الارتفاع أو تطبيق خوارزميات تحجيم محددة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق تحكم دقيق في عمليات تغيير الحجم داخل تطبيقك."
type: docs
weight: 330
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

غيّر حجم الصورة وفقًا لنوع تغيير الحجم المحدد، مما يسهل تعديل أبعاد الصورة بمرونة مع الحفاظ على نسبة العرض إلى الارتفاع أو تطبيق خوارزميات تحجيم محددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحكم دقيق في عمليات تغيير الحجم داخل تطبيقك.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

## أمثلة

هذا المثال يحمل صورة TIFF ويعيد تحجيمها باستخدام طرق تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Tiff.TiffImage image = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

اضبط حجم الصورة بناءً على الإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق عمليات تغيير حجم مخصصة وفقًا لمتطلبات تطبيقك المحددة.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | Int32 | العرض الجديد. |
| newHeight | Int32 | الارتفاع الجديد. |
| الإعدادات | ImageResizeSettings | إعدادات التحجيم. |

## أمثلة

هذا المثال يحمل صورة TIFF ويعيد تحجيمها باستخدام إعدادات تحجيم مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة النسبية الموزونة والمختلطة وتداخل lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// المرشح المستطيل الصغير
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// عدد الألوان في لوحة الألوان.
resizeSettings.EntriesCount = 256;

// لم يتم استخدام تقليل الألوان
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// الطريقة الإقليدية
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
    tiffImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // حفظ إلى PNG
    tiffImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


