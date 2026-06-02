---
title: "EmfRasterizationOptions.RenderMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية EmfRasterizationOptions. يحصل أو يضبط وضع العرض"
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/emfrasterizationoptions/rendermode/
---
## EmfRasterizationOptions.RenderMode property

يحصل أو يضبط وضعية العرض.

```csharp
public EmfRenderMode RenderMode { get; set; }
```

### Property Value

وضع العرض.

## أمثلة

يوضح هذا المثال كيفية تحميل صورة EMF من ملف وتحويلها إلى SVG باستخدام EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // سيتم تحويل النص إلى أشكال.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // لون خلفية سطح الرسم.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // حجم الصفحة.
    rasterizationOptions.PageSize = emfImage.Size;

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // عيّن الهامش الأفقي
    rasterizationOptions.BorderX = 50;

    // تعيين الهامش العمودي
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### انظر أيضًا

* enum [EmfRenderMode](../../../aspose.imaging.fileformats.emf/emfrendermode/)
* class [EmfRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../emfrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


