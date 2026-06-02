---
title: "RasterImage.GetPixel"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تحصل على بكسل من الصورة."
type: docs
weight: 360
url: /ar/net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

يحصل على بكسل صورة.

```csharp
public Color GetPixel(int x, int y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | موقع البكسل على المحور x. |
| y | Int32 | موقع البكسل على المحور y. |

### قيمة الإرجاع

لون البكسل للموقع المحدد.

## أمثلة

المثال التالي يحمل صورة نقطية ويحصل على لون بكسل عشوائي.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على لون البكسل العلوي الأيسر في الصورة.
    Color color = rasterImage.GetPixel(0, 0);

    // احصل على قيم مكونات اللون الفردية
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### انظر أيضًا

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


