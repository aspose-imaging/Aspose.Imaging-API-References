---
title: "RasterCachedImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا"
type: docs
weight: 80
url: /ar/net/aspose.imaging/rastercachedimage/binarizefixed/
---
## RasterCachedImage.BinarizeFixed method

تحويل الصورة إلى ثنائية باستخدام عتبة محددة مسبقًا

```csharp
public override void BinarizeFixed(byte threshold)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | بايت | قيمة العتبة. إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا ستكون 0. |

## أمثلة

المثال التالي يحول صورة مخزنة بنظام raster إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة عتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


