---
title: "Jpeg2000Image.HorizontalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية Jpeg2000Image. تسمح لك هذه الخاصية باسترجاع أو تعديل الدقة الأفقية لـ RasterImage مقاسة بالبكسل لكل بوصة (PPI). يمكن أن يؤثر ضبط هذه الدقة على حجم وجودة الصورة عند طباعتها أو عرضها. من خلال ضبط الدقة الأفقية يمكن للمستخدمين تحسين الصورة لأجهزة الإخراج أو التطبيقات المحددة، مما يضمن أفضل نتائج بصرية ممكنة."
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/horizontalresolution/
---
## Jpeg2000Image.HorizontalResolution property

تسمح لك هذه الخاصية باسترجاع أو تعديل الدقة الأفقية لـ [`RasterImage`](../../../aspose.imaging/rasterimage/)، مقاسة بالبكسل لكل بوصة (PPI). يمكن أن يؤثر ضبط هذه الدقة على حجم وجودة الصورة عند طباعتها أو عرضها. من خلال ضبط الدقة الأفقية، يمكن للمستخدمين تحسين الصورة لأجهزة الإخراج أو التطبيقات المحددة، مما يضمن أفضل نتائج بصرية ممكنة.

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

الدقة الأفقية.

## ملاحظات

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة معًا في استدعاء واحد.

## أمثلة

يوضح المثال التالي كيفية ضبط الدقة الأفقية/العمودية لصورة JPEG2000.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jp2"))
{
    Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image)image;

    // احصل على الدقة الأفقية والعمودية لـ Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.HorizontalResolution;
    double verticalResolution = jpeg2000Image.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpeg2000Image.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpeg2000Image.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpeg2000Image.VerticalResolution);
    }
}
```

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


