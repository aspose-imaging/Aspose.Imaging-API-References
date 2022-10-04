---
title: Resize
second_title: Aspose.Imaging لمرجع NET API
description: يغير حجم الصورة.
type: docs
weight: 380
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/resize/
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

يقوم هذا المثال بتحميل صورة GIF وتغيير حجمها باستخدام طرق مختلفة لتغيير الحجم.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قم بالزيادة بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قم بالارتقاء بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.FileFormats.Gif.GifImage image = (Aspose.Imaging.FileFormats.Gif.GifImage)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

### أنظر أيضا

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
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

### أمثلة

يقوم هذا المثال بتحميل صورة GIF وتغيير حجمها باستخدام إعدادات تغيير الحجم المختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// الخوارزمية التكيفية القائمة على الوظيفة المنطقية الموزونة والمختلطة واستيفاء lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// مرشح صغير مستطيل
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// عدد الألوان في اللوحة.
resizeSettings.EntriesCount = 256;

// لا يتم استخدام تكميم اللون
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// الطريقة الإقليدية
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.Image image = (Aspose.Imaging.Image)Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // تصغير بمقدار مرتين باستخدام إعادة التشكيل التكيفية.
    gifImage.Resize(image.Width / 2, image.Height / 2, resizeSettings);

    // حفظ في PNG
    gifImage.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings)
* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->