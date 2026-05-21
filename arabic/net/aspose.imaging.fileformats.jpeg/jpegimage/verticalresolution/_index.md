---
title: "JpegImage.VerticalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية JpegImage. تدير هذه الخاصية الدقة العمودية المعبر عنها بالبكسل لكل بوصة لصورة RasterImage المرتبطة. تعديل هذه الدقة يؤثر على حجم وجودة الصورة عند طباعتها أو عرضها بحجم مادي ثابت. من خلال ضبط هذه الخاصية تتحكم في كثافة تجميع بكسلات الصورة عمودياً مما يؤثر على وضوحها الحاد بشكل عام."
type: docs
weight: 160
url: /ar/net/aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution/
---
## JpegImage.VerticalResolution property

تدير هذه الخاصية الدقة العمودية، المعبر عنها بالبكسل لكل بوصة، للـ [`RasterImage`](../../../aspose.imaging/rasterimage/). تعديل هذه الدقة يؤثر على حجم وجودة الصورة عند طباعتها أو عرضها بحجم مادي ثابت. من خلال ضبط هذه الخاصية، تتحكم في كثافة تجميع بكسلات الصورة عمودياً، مما يؤثر على وضوحها الحاد بشكل عام.

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

الدقة العمودية.

## ملاحظات

ملاحظة: بشكل افتراضي تكون هذه القيمة دائمًا 72 لأن الأنظمة المختلفة لا يمكنها إرجاع دقة الشاشة. قد ترغب في استخدام طريقة SetResolution لتحديث قيمتي الدقة معًا في استدعاء واحد.

## أمثلة

المثال التالي يوضح كيفية ضبط الدقة الأفقية/العمودية لصورة JPEG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)image;

    // احصل على الدقة الأفقية والعمودية لـ BmpImage
    double horizontalResolution = jpegImage.HorizontalResolution;
    double verticalResolution = jpegImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpegImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpegImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpegImage.VerticalResolution);
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

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


