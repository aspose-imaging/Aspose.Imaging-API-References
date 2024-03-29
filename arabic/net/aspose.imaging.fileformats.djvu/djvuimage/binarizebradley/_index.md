---
title: BinarizeBradley
second_title: Aspose.Imaging لمرجع NET API
description: ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة
type: docs
weight: 180
url: /ar/net/aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/
---
## DjvuImage.BinarizeBradley method

ثنائية الصورة باستخدام خوارزمية العتبة التكيفية لبرادلي باستخدام عتبة الصورة المتكاملة

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة sxs للبكسل تتمحور حول هذا البكسل. |
| windowSize | Int32 | حجم نافذة sxs للبكسل المتمركز حول هذا البكسل |

### أمثلة

يقوم المثال التالي بترميز صورة DJVU باستخدام خوارزمية برادلي التكيفية مع حجم النافذة المحدد. تحتوي الصور الثنائية على لونين فقط - أبيض وأسود.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // Binarize الصورة بفارق سطوع 5. السطوع هو اختلاف بين البكسل ومتوسط نافذة 10 x 10 من البكسل تتمحور حول هذا البكسل.
    djvuImage.BinarizeBradley(5, 10);
    djvuImage.Save(dir + "sample.BinarizeBradley5_10x10.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [DjvuImage](../../djvuimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
