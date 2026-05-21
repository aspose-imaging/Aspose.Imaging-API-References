---
title: "SvgRasterizationOptions.ScaleX"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية SvgRasterizationOptions. تحصل أو تعين مقياس x"
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/svgrasterizationoptions/scalex/
---
## SvgRasterizationOptions.ScaleX property

الحصول أو تعيين مقياس x.

```csharp
public float ScaleX { get; set; }
```

### Property Value

الـ مقياس x.

## أمثلة

يوضح هذا المثال كيفية تحميل صورة SVG من ملف وتحويلها إلى PNG باستخدام خيارات مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // من أجل تحويل SVG إلى نقطية نحتاج إلى تحديد خيارات التحويل النقطي.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // تعيين اللون الافتراضي لخلفية صورة. القيمة الافتراضية هي الأبيض.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // تعيين حجم الصفحة
    rasterizationOptions.PageSize = svgImage.Size;

    // يتم تطبيق مضاد التعرج على الخطوط والمنحنيات وحواف المناطق المملوءة.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // يتم رسم كل حرف باستخدام صورة البتات المضادة للتعرج للرمز دون إرشاد.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // قلل حجم الصورة 10 مرات، أي أن حجم الإخراج سيكون 10٪ من الحجم الأصلي.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // حفظ إلى ملف PNG
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### انظر أيضًا

* class [SvgRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


