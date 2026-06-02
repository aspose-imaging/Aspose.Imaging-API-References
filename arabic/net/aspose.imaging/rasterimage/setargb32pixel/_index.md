---
title: "RasterImage.SetArgb32Pixel"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تعيين بكسل ARGB 32‑بت للصورة في الموضع المحدد"
type: docs
weight: 620
url: /ar/net/aspose.imaging/rasterimage/setargb32pixel/
---
## RasterImage.SetArgb32Pixel method

يضبط بكسل صورة ARGB 32 بت للموقع المحدد.

```csharp
public void SetArgb32Pixel(int x, int y, int argb32Color)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | موقع البكسل على المحور x. |
| y | Int32 | موقع البكسل على المحور y. |
| argb32Color | Int32 | بكسل ARGB 32‑بت للموضع المحدد. |

## أمثلة

المثال التالي يحمل صورة نقطية، ويحدد لون بكسل عشوائي.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // يحدد لون البكسل العلوي الأيسر.
    rasterImage.SetArgb32Pixel(0, 0, Aspose.Imaging.Color.Aqua.ToArgb());

    // طريقة أخرى هي تمرير نسخة من Aspose.Imaging.Color مباشرةً
    rasterImage.SetPixel(0, 0, Aspose.Imaging.Color.Aqua);
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


