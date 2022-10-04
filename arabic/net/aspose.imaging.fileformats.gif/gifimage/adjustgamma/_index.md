---
title: AdjustGamma
second_title: Aspose.Imaging لمرجع NET API
description: تصحيح جاما لصورة .
type: docs
weight: 250
url: /ar/net/aspose.imaging.fileformats.gif/gifimage/adjustgamma/
---
## AdjustGamma(float) {#adjustgamma}

تصحيح جاما لصورة .

```csharp
public override void AdjustGamma(float gamma)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| gamma | Single | جاما لمعامل القنوات الأحمر والأخضر والأزرق |

### أمثلة

ينفذ المثال التالي تصحيح غاما لصورة GIF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // تعيين معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    gifImage.AdjustGamma(2.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

---

## AdjustGamma(float, float, float) {#adjustgamma_1}

تصحيح جاما لصورة .

```csharp
public override void AdjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| gammaRed | Single | معامل جاما للقناة الحمراء |
| gammaGreen | Single | معامل جاما للقناة الخضراء |
| gammaBlue | Single | معامل جاما للقناة الزرقاء |

### أمثلة

ينفذ المثال التالي تصحيح جاما لصورة GIF بتطبيق معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // تعيين معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    gifImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [GifImage](../../gifimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->