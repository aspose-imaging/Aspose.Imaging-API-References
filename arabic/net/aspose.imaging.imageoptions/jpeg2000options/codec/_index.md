---
title: "Jpeg2000Options.Codec"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية Jpeg2000Options. يحصل أو يعيّن برنامج الترميز JPEG2000"
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/jpeg2000options/codec/
---
## Jpeg2000Options.Codec property

يحصل أو يعيّن برنامج الترميز JPEG2000

```csharp
public Jpeg2000Codec Codec { get; set; }
```

### Property Value

برنامج الترميز JPEG2000

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG وحفظها إلى JPEG2000 مع الخيارات المطلوبة.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
    saveOptions.Irreversible = true;

    // JP2 هو تنسيق \"الحاوية\" لتدفقات JPEG 2000.
    // J2K هو بيانات مضغوطة خام، بدون غلاف.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // احفظ إلى ملف
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 مع الخيارات المطلوبة وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
createOptions.Irreversible = true;

// JP2 هو تنسيق \"الحاوية\" لتدفقات JPEG 2000.
// J2K هو بيانات مضغوطة خام، بدون غلاف.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// إنشاء صورة JPEG2000 بحجم 100x100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // احفظ إلى ملف
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### انظر أيضًا

* enum [Jpeg2000Codec](../../../aspose.imaging.fileformats.jpeg2000/jpeg2000codec/)
* class [Jpeg2000Options](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpeg2000options/)
* assembly [Aspose.Imaging](../../../)


