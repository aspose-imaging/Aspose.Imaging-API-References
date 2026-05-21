---
title: "RasterImage.BinarizeOtsu"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحويل الصورة إلى ثنائية باستخدام عتبة أوتسو"
type: docs
weight: 260
url: /ar/net/aspose.imaging/rasterimage/binarizeotsu/
---
## RasterImage.BinarizeOtsu method

تحويل الصورة إلى ثنائية باستخدام عتبة Otsu

```csharp
public virtual void BinarizeOtsu()
```

## أمثلة

المثال التالي يحول صورة نقطية إلى ثنائية باستخدام عتبة أوتسو. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // صنّف الصورة باستخدام عتبة Otsu.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


