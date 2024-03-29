---
title: SetArgb32Pixel
second_title: Aspose.Imaging لمرجع NET API
description: يضبط صورة ARGB بكسل 32 بت للوضع المحدد.
type: docs
weight: 550
url: /ar/net/aspose.imaging/rasterimage/setargb32pixel/
---
## RasterImage.SetArgb32Pixel method

يضبط صورة ARGB بكسل 32 بت للوضع المحدد.

```csharp
public void SetArgb32Pixel(int x, int y, int argb32Color)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Int32 | موقع البكسل x. |
| y | Int32 | موقع البكسل ص. |
| argb32Color | Int32 | 32 بت ARGB بكسل للوضع المحدد. |

### أمثلة

يقوم المثال التالي بتحميل صورة نقطية ، ويضبط لون البكسل العشوائي.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // يعين لون البكسل العلوي الأيسر.
    rasterImage.SetArgb32Pixel(0, 0, Aspose.Imaging.Color.Aqua.ToArgb());

    // طريقة أخرى هي تمرير مثيل من Aspose.Imaging.Color مباشرة
    rasterImage.SetPixel(0, 0, Aspose.Imaging.Color.Aqua);
}
```

### أنظر أيضا

* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
