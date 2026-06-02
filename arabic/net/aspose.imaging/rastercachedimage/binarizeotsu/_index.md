---
title: "RasterCachedImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterCachedImage. تحويل صورة إلى ثنائية باستخدام عتبة Otsu."
type: docs
weight: 90
url: /ar/net/aspose.imaging/rastercachedimage/binarizeotsu/
---
## RasterCachedImage.BinarizeOtsu method

تحويل الصورة إلى ثنائية باستخدام عتبة Otsu

```csharp
public override void BinarizeOtsu()
```

## أمثلة

المثال التالي يحول صورة مخزنة مؤقتًا إلى ثنائية باستخدام عتبة Otsu. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // صنّف الصورة باستخدام عتبة Otsu.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### انظر أيضًا

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


