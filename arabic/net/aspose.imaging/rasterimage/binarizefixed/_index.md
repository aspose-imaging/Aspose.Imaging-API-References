---
title: "RasterImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحويل ثنائي لصورة بعتبة محددة مسبقًا"
type: docs
weight: 250
url: /ar/net/aspose.imaging/rasterimage/binarizefixed/
---
## RasterImage.BinarizeFixed method

تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

```csharp
public virtual void BinarizeFixed(byte threshold)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | بايت | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا ستكون 0. |

## أمثلة

المثال التالي يحول صورة نقطية إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة عتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


