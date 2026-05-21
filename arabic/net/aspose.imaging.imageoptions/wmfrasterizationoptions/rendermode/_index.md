---
title: "WmfRasterizationOptions.RenderMode"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية WmfRasterizationOptions. تحصل أو تعين وضع عرض WMF"
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/wmfrasterizationoptions/rendermode/
---
## WmfRasterizationOptions.RenderMode property

يحصل أو يضبط وضع العرض لـ WMF.

```csharp
public WmfRenderMode RenderMode { get; set; }
```

### Property Value

وضع عرض WMF.

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

### انظر أيضًا

* enum [WmfRenderMode](../../../aspose.imaging.fileformats.wmf/wmfrendermode/)
* class [WmfRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../wmfrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


