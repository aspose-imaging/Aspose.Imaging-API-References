---
title: BinarizeOtsu
second_title: Aspose.Imaging لمرجع NET API
description: ثنائية الصورة مع عتبة Otsu
type: docs
weight: 240
url: /ar/net/aspose.imaging/rasterimage/binarizeotsu/
---
## RasterImage.BinarizeOtsu method

ثنائية الصورة مع عتبة Otsu

```csharp
public virtual void BinarizeOtsu()
```

### أمثلة

يقوم المثال التالي بترميز صورة نقطية باستخدام عتبة Otsu. تحتوي الصور الثنائية على لونين فقط - أبيض وأسود.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // قم بتثبيط الصورة باستخدام عتبة Otsu.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### أنظر أيضا

* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
