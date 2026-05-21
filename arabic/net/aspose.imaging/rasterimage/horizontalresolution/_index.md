---
title: "RasterImage.HorizontalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية RasterImage. تحصل أو تعين الدقة الأفقية بوحدات البكسل لكل بوصة لهذه الـ RasterImage"
type: docs
weight: 30
url: /ar/net/aspose.imaging/rasterimage/horizontalresolution/
---
## RasterImage.HorizontalResolution property

تحصل أو تعين الدقة الأفقية، بوحدات البكسل لكل بوصة، لهذه [`RasterImage`](../).

```csharp
public virtual double HorizontalResolution { get; set; }
```

### Property Value

الدقة الأفقية.

## ملاحظات

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة معًا في استدعاء واحد.

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


