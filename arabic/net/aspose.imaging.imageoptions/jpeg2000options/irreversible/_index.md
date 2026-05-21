---
title: "Jpeg2000Options.Irreversible"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية Jpeg2000Options. تحصل أو تعين قيمة تشير إلى ما إذا كان سيتم استخدام DWT غير العكسي 97 true أو استخدام ضغط DWT غير الفاقد 53 بشكل افتراضي"
type: docs
weight: 50
url: /ar/net/aspose.imaging.imageoptions/jpeg2000options/irreversible/
---
## Jpeg2000Options.Irreversible property

يحصل أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخدام DWT غير العكسي 9-7 (true) أو استخدام ضغط DWT غير الفاقد 5-3 (الافتراضي).

```csharp
public bool Irreversible { get; set; }
```

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

* class [Jpeg2000Options](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpeg2000options/)
* assembly [Aspose.Imaging](../../../)


