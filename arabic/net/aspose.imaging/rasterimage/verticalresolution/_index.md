---
title: VerticalResolution
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على أو تحديد الدقة الرأسية  بالبكسل في البوصة  لهذاRasterImageaspose.imaging/rasterimage .
type: docs
weight: 170
url: /ar/net/aspose.imaging/rasterimage/verticalresolution/
---
## RasterImage.VerticalResolution property

الحصول على أو تحديد الدقة الرأسية ، بالبكسل في البوصة ، لهذا[`RasterImage`](../../rasterimage) .

```csharp
public virtual double VerticalResolution { get; set; }
```

### Property_Value

الدقة الرأسية.

### ملاحظات

لاحظ افتراضيًا أن هذه القيمة هي دائمًا 96 نظرًا لأن الأنظمة الأساسية المختلفة لا يمكنها إرجاع دقة الشاشة. يمكنك التفكير في استخدام طريقة SetResolution لتحديث قيم الدقة في مكالمة واحدة.

### أمثلة

يوضح المثال التالي كيفية تعيين الدقة الأفقية / الرأسية للصورة النقطية.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // احصل على دقة أفقية وعمودية للصورة
    double horizontalResolution = rasterImage.HorizontalResolution;
    double verticalResolution = rasterImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // استخدم طريقة SetResolution لتحديث قيم الدقة في مكالمة واحدة.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        rasterImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", rasterImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", rasterImage.VerticalResolution);
    }

    // قد يبدو الإخراج كالتالي:
    // الدقة الأفقية بالبكسل في البوصة: 300
    // الدقة الرأسية ، بالبكسل في البوصة: 300
    // ضبط قيم الدقة على 96 نقطة في البوصة
    // الدقة الأفقية ، بالبكسل في البوصة: 96
    // الدقة الرأسية ، بالبكسل في البوصة: 96
}
```

### أنظر أيضا

* class [RasterImage](../../rasterimage)
* مساحة الاسم [Aspose.Imaging](../../rasterimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
