---
title: "ApngImage.RemoveAllFrames"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ApngImage. امسح مجموعة الإطارات الخاصة بك بإزالة جميع الإطارات باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إعادة تعيين أو تجديد الرسوم المتحركة الخاصة بهم"
type: docs
weight: 250
url: /ar/net/aspose.imaging.fileformats.apng/apngimage/removeallframes/
---
## ApngImage.RemoveAllFrames method

امسح مجموعة الإطارات الخاصة بك بإزالة جميع الإطارات باستخدام هذه الطريقة البديهية. مثالي للمطورين الذين يرغبون في إعادة ضبط أو تحديث رسومهم المتحركة.

```csharp
public void RemoveAllFrames()
```

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

* class [ApngImage](../)
* namespace [Aspose.Imaging.FileFormats.Apng](../../apngimage/)
* assembly [Aspose.Imaging](../../../)


