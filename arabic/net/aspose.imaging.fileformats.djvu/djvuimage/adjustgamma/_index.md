---
title: "DjvuImage.AdjustGamma"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة DjvuImage. تصحيح جاما خصيصًا لقنوات الأحمر والأخضر والأزرق يتضمن تعديل سطوع كل مكون لوني بشكل منفصل. من خلال تطبيق معاملات جاما مختلفة على قنوات RGB يمكنك ضبط السطوع والتباين العام للصورة بدقة. تضمن هذه التقنية تمثيلًا لونيًا صحيحًا وتحسن جودة الصورة البصرية عبر مختلف أجهزة العرض"
type: docs
weight: 170
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

تصحيح جاما، خاصةً لقنوات الأحمر والأخضر والأزرق، يتضمن ضبط سطوع كل مكوّن لوني بشكل منفصل. من خلال تطبيق معاملات جاما مختلفة على قنوات RGB، يمكنك ضبط السطوع والتباين الكلي للصورة بدقة. تضمن هذه التقنية تمثيلًا دقيقًا للألوان وتحسين جودة الصورة البصرية عبر مختلف أجهزة العرض.

```csharp
public override void AdjustGamma(float gamma)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gamma | فردي | معامل جاما للقنوات الحمراء والخضراء والزرقاء |

## أمثلة

المثال التالي يقوم بتصحيح غاما لصورة DJVU.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // اضبط معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    djvuImage.AdjustGamma(2.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

يتم تطبيق تصحيح الجاما على الصورة باستخدام معلمات قابلة للتخصيص لقنوات الأحمر والأخضر والأزرق، مما يسمح بضبط دقيق لتوازن الألوان والسطوع. تعزز هذه الطريقة جودة الصورة من خلال ضبط تمثيل الألوان بدقة، مما يضمن عرضًا مثاليًا عبر مختلف أجهزة العرض. يؤدي تعديل قيم الجاما لكل قناة إلى تحسين توازن الألوان والجاذبية البصرية.

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | فردي | معامل جاما للقناة الحمراء |
| gammaGreen | فردي | معامل جاما للقناة الخضراء |
| gammaBlue | فردي | معامل جاما للقناة الزرقاء |

## أمثلة

المثال التالي يقوم بتصحيح غاما لصورة DJVU مع تطبيق معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // اضبط معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    djvuImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


