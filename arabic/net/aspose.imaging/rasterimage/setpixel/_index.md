---
title: "RasterImage.SetPixel"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تعيين بكسل صورة للموقع المحدد"
type: docs
weight: 640
url: /ar/net/aspose.imaging/rasterimage/setpixel/
---
## RasterImage.SetPixel method

يضبط بكسل الصورة للموقع المحدد.

```csharp
public void SetPixel(int x, int y, Color color)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | موقع البكسل على المحور x. |
| y | Int32 | موقع البكسل على المحور y. |
| لون | لون | لون البكسل للموقع المحدد. |

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

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


