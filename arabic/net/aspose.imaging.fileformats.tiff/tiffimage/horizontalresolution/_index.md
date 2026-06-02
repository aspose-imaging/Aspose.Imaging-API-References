---
title: "TiffImage.HorizontalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffImage. استرجع الدقة الأفقية للصورة المحددة بوحدات البكسل لكل بوصة لتسهيل الضبط الدقيق وقدرات العرض. وصول سهل إلى بيانات التعريف الأساسية للصورة مما يعزز سير عمل معالجة الصور المبسط لتجارب مستخدم محسنة"
type: docs
weight: 70
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution/
---
## TiffImage.HorizontalResolution property

استرجع الدقة الأفقية للصورة المحددة [`Image`](../../../aspose.imaging/image/) بوحدات البكسل لكل بوصة، لتسهيل الضبط الدقيق وقدرات العرض. وصول سهل إلى بيانات التعريف الأساسية للصورة، مما يعزز سير عمل معالجة الصور المبسط لتجارب مستخدم محسنة.

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

الدقة الأفقية.

## ملاحظات

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 96 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة معًا في استدعاء واحد.

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لصورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // الحصول على الدقة الأفقية والعمودية لـ TiffImage.
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### انظر أيضًا

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


