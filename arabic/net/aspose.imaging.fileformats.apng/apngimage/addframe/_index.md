---
title: "ApngImage.AddFrame"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ApngImage. أضف بسهولة إطارًا جديدًا إلى نهاية مجموعة الإطارات الخاصة بك باستخدام هذه الطريقة البسيطة. مثالية للمطورين الذين يرغبون في توسيع مجموعة إطاراتهم ديناميكيًا للرسوم المتحركة ذات الصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية."
type: docs
weight: 80
url: /ar/net/aspose.imaging.fileformats.apng/apngimage/addframe/
---
## AddFrame() {#addframe}

أضف إطارًا جديدًا بسهولة إلى نهاية مجموعة الإطارات الخاصة بك باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في توسيع مجموعة إطاراتهم ديناميكيًا للرسوم المتحركة ذات الصور متعددة الإطارات. سيتم إنشاء إطار جديد وفقًا لحجم الصورة الحالية.

```csharp
public ApngFrame AddFrame()
```

### قيمة الإرجاع

الإطار APNG الجديد الذي تم إنشاؤه.

### انظر أيضًا

* class [ApngFrame](../../apngframe/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddFrame(RasterImage) {#addframe_1}

قم بتوسيع مجموعة إطاراتك بسهولة بإضافة إطار جديد إلى النهاية باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يسعون لتعزيز رسومهم المتحركة للصور متعددة الإطارات ديناميكيًا. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

```csharp
public void AddFrame(RasterImage frameImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| frameImage | RasterImage | صورة الإطار. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | frameImage هو null. |

## أمثلة

يوضح المثال التالي كيفية إنشاء صورة APNG من صورة نقطية صفحة واحدة أخرى.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // يمكن تعيين الوقت الافتراضي لإطار الصورة هناك: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // جارٍ التنظيف لأن الصورة تحتوي على إطار واحد افتراضيًا
        apngImage.RemoveAllFrames();

        // إضافة الإطار الأول
        apngImage.AddFrame(sourceImage);

        // إضافة إطارات وسطية
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // إضافة الإطار الأخير
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)

---

## AddFrame(RasterImage, uint) {#addframe_2}

قم بتوسيع مجموعة إطاراتك بسلاسة عن طريق إلحاق إطار جديد باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إثراء رسومهم المتحركة للصور متعددة الإطارات. سيتم ملء محتويات الإطار الجديد من الصورة المحددة.

```csharp
public void AddFrame(RasterImage frameImage, uint frameTime)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| frameImage | RasterImage | صورة الإطار. |
| frameTime | UInt32 | مدة الإطار، بالمللي ثانية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | frameImage هو null. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


