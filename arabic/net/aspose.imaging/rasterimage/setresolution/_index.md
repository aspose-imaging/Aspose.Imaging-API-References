---
title: "RasterImage.SetResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة RasterImage. تعيين الدقة لهذه RasterImage"
type: docs
weight: 650
url: /ar/net/aspose.imaging/rasterimage/setresolution/
---
## RasterImage.SetResolution method

تعيين الدقة لهذه [`RasterImage`](../).

```csharp
public virtual void SetResolution(double dpiX, double dpiY)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | Double | الدقة الأفقية، بوحدة النقاط في البوصة، للـ [`RasterImage`](../). |
| dpiY | Double | الدقة العمودية، بوحدة النقاط في البوصة، للـ [`RasterImage`](../). |

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لصورة نقطية.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على الدقة الأفقية والعمودية للصورة
    double horizontalResolution = rasterImage.HorizontalResolution;
    double verticalResolution = rasterImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        rasterImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", rasterImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", rasterImage.VerticalResolution);
    }

    // قد يبدو الإخراج هكذا:
    // الدقة الأفقية، بوحدة البكسل في البوصة: 300
    // الدقة العمودية، بوحدة البكسل في البوصة: 300
    // تعيين قيم الدقة إلى 96 نقطة في البوصة
    // الدقة الأفقية، بوحدة البكسل في البوصة: 96
    // الدقة العمودية، بوحدة البكسل في البوصة: 96
}
```

### انظر أيضًا

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


