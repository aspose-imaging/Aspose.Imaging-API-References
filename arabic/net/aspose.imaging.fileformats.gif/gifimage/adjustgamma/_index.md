---
title: "GifImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة GifImage. تحسين جودة الصورة عن طريق تطبيق تصحيح جاما. تقوم هذه الطريقة بضبط جاما اللون للصورة لتحقيق وضوح بصري مثالي. إنها تعدل قيمة الجاما لكل بكسل مما يؤدي إلى تحسين تجسيد الألوان والمظهر العام للصورة."
type: docs
weight: 230
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

حسّن جودة الصورة بتطبيق تصحيح جاما. تقوم هذه الطريقة بضبط جاما اللون للصورة لتحقيق وضوح بصري أمثل. إنها تعدل قيمة الجاما لكل بكسل، مما ينتج عنه تحسين في تجسيد الألوان ومظهر الصورة العام.

```csharp
public override void AdjustGamma(float gamma)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gamma | فردي | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

## أمثلة

المثال التالي يقوم بتطبيق تصحيح جاما على صورة GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // اضبط معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    gifImage.AdjustGamma(2.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

تطبيق تصحيح جاما على الصورة يضيف تعديلًا غير خطي لقيم البكسل، معززًا أو مخفضًا السطوع بناءً على المعاملات المحددة للقنوات الحمراء والخضراء والزرقاء. تساعد هذه الطريقة على ضبط توازن اللون وإضاءة الصورة بدقة، مما يحسن مظهرها العام وجودتها البصرية.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | فردي | معامل جاما للقناة الحمراء |
| gammaGreen | فردي | معامل جاما للقناة الخضراء |
| gammaBlue | فردي | معامل جاما للقناة الزرقاء |

## أمثلة

المثال التالي يقوم بتطبيق تصحيح جاما على صورة GIF باستخدام معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // اضبط معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    gifImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


