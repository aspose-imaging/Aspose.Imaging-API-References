---
title: ResizeHeightProportionally
second_title: Aspose.Imaging لمرجع NET API
description: يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم .
type: docs
weight: 210
url: /ar/net/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

يغير حجم الارتفاع بشكل متناسب. الافتراضيNearestNeighbourResample يستخدم .

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newHeight | Int32 | الارتفاع الجديد. |

### أنظر أيضا

* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

يغير حجم الارتفاع بشكل متناسب .

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newHeight | Int32 | الارتفاع الجديد. |
| resizeType | ResizeType | نوع تغيير الحجم. |

### أمثلة

يقوم هذا المثال بتحميل الصورة وتغيير حجمها بشكل متناسب باستخدام طرق مختلفة لتغيير الحجم. يتم تحديد الارتفاع فقط ، ويتم حساب العرض تلقائيًا.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قم بالزيادة بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة تشكيل أقرب الجوار.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // قم بالارتقاء بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // تصغير بمقدار مرتين باستخدام إعادة التشكيل Bilinear.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

استخدام قناع مقطعي لتسريع عملية التجزئة

```csharp
[C#]

// إخفاء خيارات التصدير
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// استخدم تجميع GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// سيكون لون backgroung شفافًا.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // تصغير حجم الصورة لتسريع عملية التجزئة
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // إنشاء مثيل لفئة ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (شرائح).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // الحصول على القناع الأمامي
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // قم بزيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على مقطع أمامي
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### أنظر أيضا

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

يغير حجم الارتفاع بشكل متناسب .

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| newHeight | Int32 | الارتفاع الجديد. |
| settings | ImageResizeSettings | إعدادات تغيير حجم الصورة. |

### أنظر أيضا

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
