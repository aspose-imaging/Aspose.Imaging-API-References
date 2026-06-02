---
title: "تعداد DitheringMethod"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.DitheringMethod تعداد. طريقة التلطيف"
type: docs
weight: 850
url: /ar/net/aspose.imaging/ditheringmethod/
---
## DitheringMethod enumeration

طريقة التمويه.

```csharp
public enum DitheringMethod
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| ThresholdDithering | `0` | تلطيـف العتبة. أبسط وأسرع خوارزمية تلطيـف. |
| FloydSteinbergDithering | `1` | تلطيـف Floyd-Steinberg. خوارزمية تلطيـف أكثر تعقيدًا، تستخدم قيم شدة الجيران الأقرب. |

## أمثلة

المثال التالي يحمل صورة نقطية ويجري تلطيـف العتبة و Floyd باستخدام عمق لوحة ألوان مختلف.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتمويه العتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.Save(dir + "sample.ThresholdDithering4.png");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتمويه فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة كلما ارتفت الجودة وحجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان بدقة 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    rasterImage.Dither(Aspose.Imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.Save(dir + "sample.FloydSteinbergDithering1.png");
}
```

### انظر أيضًا

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


