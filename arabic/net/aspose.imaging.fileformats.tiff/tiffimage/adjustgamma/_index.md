---
title: AdjustGamma
second_title: Aspose.Imaging لمرجع NET API
description: تصحيح جاما لصورة .
type: docs
weight: 190
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/
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

ينفذ المثال التالي تصحيح جاما لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // تعيين معامل جاما للقنوات الحمراء والخضراء والزرقاء.
    tiffImage.AdjustGamma(2.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
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

ينفذ المثال التالي تصحيح جاما لصورة TIFF بتطبيق معاملات مختلفة لمكونات اللون.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // تعيين معاملات جاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    tiffImage.AdjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.Save(dir + "sample.AdjustGamma.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [TiffImage](../../tiffimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
