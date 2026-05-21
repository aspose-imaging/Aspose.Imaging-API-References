---
title: "SvgOptions.TextAsShapes"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية SvgOptions. يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال"
type: docs
weight: 50
url: /ar/net/aspose.imaging.imageoptions/svgoptions/textasshapes/
---
## SvgOptions.TextAsShapes property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال.

```csharp
public bool TextAsShapes { get; set; }
```

### Property Value

`true` إذا تم تحويل كل النص إلى أشكال SVG في التحويل؛ وإلا، `false`.

## أمثلة

يوضح هذا المثال كيفية تحميل صورة WMF من ملف وتحويلها إلى SVG باستخدام WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // سيتم تحويل النص إلى أشكال.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // لون خلفية سطح الرسم.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // حجم الصفحة.
    rasterizationOptions.PageSize = wmfImage.Size;

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

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

* class [SvgOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgoptions/)
* assembly [Aspose.Imaging](../../../)


