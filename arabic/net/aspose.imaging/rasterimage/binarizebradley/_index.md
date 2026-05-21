---
title: "RasterImage.BinarizeBradley"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحويل صورة إلى ثنائية باستخدام خوارزمية عتبة التكيف لبرايدلي باستخدام عتبة الصورة المتكاملة"
type: docs
weight: 240
url: /ar/net/aspose.imaging/rasterimage/binarizebradley/
---
## BinarizeBradley(double, int) {#binarizebradley_1}

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة.

```csharp
public virtual void BinarizeBradley(double brightnessDifference, int windowSize)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | Int32 | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

## أمثلة

المثال التالي يحول صورة نقطية إلى ثنائية باستخدام خوارزمية عتبة التكيف لبرايدلي مع حجم النافذة المحدد. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حوّل الصورة إلى ثنائية مع فرق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    rasterImage.BinarizeBradley(5, 10);
    rasterImage.Save(dir + "sample.BinarizeBradley5_10x10.png");
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## BinarizeBradley(double) {#binarizebradley}

تحويل الصورة إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرايدلي باستخدام عتبة الصورة المتكاملة.

```csharp
public virtual void BinarizeBradley(double brightnessDifference)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | Double | فرق السطوع بين البكسل ومتوسط نافذة s × s من البكسلات المتمركزة حول هذا البكسل. |

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


