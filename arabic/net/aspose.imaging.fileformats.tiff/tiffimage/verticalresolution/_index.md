---
title: "TiffImage.VerticalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TiffImage. الوصول إلى الدقة العمودية للصورة المحددة بوحدات البكسل لكل بوصة، مما يتيح تعديلات دقيقة وتحسينات في العرض. استخدم بيانات الصورة الأساسية بسهولة لتبسيط سير عمل معالجة الصور، وضمان جودة وأداء فائقين في تطبيقاتك"
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.tiff/tiffimage/verticalresolution/
---
## TiffImage.VerticalResolution property

الوصول إلى الدقة العمودية لـ [`Image`](../../../aspose.imaging/image/) المحددة بوحدات البكسل لكل بوصة، مما يتيح تعديلات دقيقة وتحسينات في العرض. استخدم بيانات الصورة الأساسية بسهولة لتبسيط سير عمل معالجة الصور، وضمان جودة وأداء فائقين في تطبيقاتك.

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

الدقة العمودية.

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


