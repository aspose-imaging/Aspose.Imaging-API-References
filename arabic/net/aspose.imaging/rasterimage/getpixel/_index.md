---
title: GetPixel
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على بكسل صورة .
type: docs
weight: 330
url: /ar/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

الحصول على بكسل صورة .

```csharp
public Color GetPixel(int x, int y)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| x | Int32 | موقع البكسل x. |
| y | Int32 | موقع البكسل ص. |

### قيمة الإرجاع

لون البكسل للموقع المحدد.

### أمثلة

يقوم المثال التالي بتحميل صورة نقطية ويحصل على لون بكسل عشوائي.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على لون البكسل العلوي الأيسر للصورة.
    Color color = rasterImage.GetPixel(0, 0);

    // الحصول على قيم مكونات اللون الفردية
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### أنظر أيضا

* struct [Color](../../color)
* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->