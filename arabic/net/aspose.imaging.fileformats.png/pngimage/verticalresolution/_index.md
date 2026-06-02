---
title: "PngImage.VerticalResolution"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngImage. توفر الوصول إلى الدقة العمودية للصورة. يمكن للمطورين استخدام هذه الخاصية لاسترجاع أو تعديل إعداد الدقة الذي يحدد عدد البكسلات لكل بوصة (PPI) على المحور العمودي للصورة."
type: docs
weight: 140
url: /ar/net/aspose.imaging.fileformats.png/pngimage/verticalresolution/
---
## PngImage.VerticalResolution property

يوفر إمكانية الوصول إلى الدقة العمودية للصورة. يمكن للمطورين استخدام هذه الخاصية لاسترجاع أو تعديل إعداد الدقة، والذي يشير إلى عدد البكسلات لكل بوصة (PPI) على المحور العمودي للصورة.

```csharp
public override double VerticalResolution { get; set; }
```

## أمثلة

يوضح المثال التالي كيفية تعيين الدقة الأفقية/العمودية لصورة PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

    // احصل على الدقة الأفقية والعمودية لـ PngImage.
    double horizontalResolution = pngImage.HorizontalResolution;
    double verticalResolution = pngImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة الاثنين في استدعاء واحد.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        pngImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", pngImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", pngImage.VerticalResolution);
    }
}
```

### انظر أيضًا

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


