---
title: "PngOptions.BitDepth"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngOptions. يحصل أو يضبط قيم عمق البت في النطاق 1 2 4 8 16."
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/pngoptions/bitdepth/
---
## PngOptions.BitDepth property

يحصل أو يعيّن قيم عمق البت في النطاق 1، 2، 4، 8، 16.

انتبه إلى الحدود التالية:

يدعم IndexedColor عمق البت 1، 2، 4، 8.

يدعم Grayscale و GrayscaleWithAlpha عمق البت 8.

يدعم Truecolor، TruecolorWithAlpha عمق البت 8، 16.

```csharp
public byte BitDepth { get; set; }
```

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG مع الخيارات المحددة، تعبئتها بألوان تدرج خطي وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// عدد البتات لكل قناة لون.
createOptions.BitDepth = 8;

// كل بكسل هو ثلاثية (أحمر، أخضر، أزرق) تليها مكوّن ألفا.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// أقصى مستوى للضغط.
createOptions.CompressionLevel = 9;

// استخدام الفلاتر يسمح بضغط الصور ذات النغمات المستمرة بشكل أكثر فعالية.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// استخدام التحميل التدريجي.
createOptions.Progressive = true;

// إنشاء صورة PNG بمعلمات مخصصة.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // تعبئة الصورة بتدرج شبه شفاف.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // احفظ إلى ملف.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

المثال التالي يوضح كيفية حفظ صورة بتنسيق PNG باستخدام خيارات مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
// يمكنك أيضًا تحميل صورة بأي تنسيق مدعوم من ملف أو تدفق.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بالتدرج الأزرق الشفاف.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // تحميل تدريجي.
    saveOptions.Progressive = true;

    // عيّن الدقة الأفقية والعمودية إلى 96 بكسل لكل بوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // كل بكسل هو ثلاثية (أحمر، أخضر، أزرق) تليها ألفا.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // عيّن أعلى مستوى للضغط.
    saveOptions.CompressionLevel = 9;

    // هذا هو أفضل ضغط، لكنه أبطأ زمن تنفيذ.
    // الترشيح التكيفي يعني أن عملية الحفظ ستختار الفلتر الأنسب لكل صف بيانات.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // عدد البتات لكل قناة.
    saveOptions.BitDepth = 8;

    // احفظ إلى ملف.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### انظر أيضًا

* class [PngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../pngoptions/)
* assembly [Aspose.Imaging](../../../)


