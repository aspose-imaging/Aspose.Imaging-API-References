---
title: "GifImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تحويل الصورة إلى ثنائية باستخدام عتبة Otsu هو أسلوب يُستخدم لتحديد القيمة المثلى للعتبة تلقائياً لتحويل صورة تدرج رمادي إلى صورة ثنائية. تحسب خوارزمية عتبة Otsu العتبة التي تقلل من التباين داخل الفئة للسطوع البكسلي في الفئتين الناتجتين: المقدمة والخلفية. هذه التقنية مفيدة خصوصاً عندما تكون قيمة العتبة المثلى غير معروفة وتحتاج إلى تحديدها بشكل تكيفي بناءً على مدرج ترددات الصورة."
type: docs
weight: 260
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/binarizeotsu/
---
## GifImage.BinarizeOtsu method

تحويل الصورة إلى ثنائية باستخدام عتبة أوتو هو طريقة تُستخدم لتحديد قيمة العتبة المثلى تلقائيًا لتحويل صورة رمادية إلى صورة ثنائية. تحسب خوارزمية عتبة أوتو العتبة التي تقلل من التباين داخل الفئات لبكسلات الصورة في الفئتين الناتجتين (المقدمة والخلفية). تكون هذه التقنية مفيدة بشكل خاص عندما تكون قيمة العتبة المثلى غير معروفة وتحتاج إلى تحديدها بشكل تكيفي بناءً على مخطط ترددات الصورة.

```csharp
public override void BinarizeOtsu()
```

## أمثلة

المثال التالي يحول صورة GIF إلى صورة ثنائية باستخدام عتبة Otsu. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // صنّف الصورة باستخدام عتبة Otsu.
    gifImage.BinarizeOtsu();
    gifImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


