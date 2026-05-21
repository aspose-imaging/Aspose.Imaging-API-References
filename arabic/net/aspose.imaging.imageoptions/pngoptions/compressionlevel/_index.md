---
title: "PngOptions.CompressionLevel"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngOptions. تحصل أو تعيّن مستوى ضغط PngImage في النطاق من 0 إلى 9. كلما ارتفعت القيمة، كلما كان الضغط أكثر كفاءة."
type: docs
weight: 40
url: /ar/net/aspose.imaging.imageoptions/pngoptions/compressionlevel/
---
## PngOptions.CompressionLevel property

تحصل أو تعيّن مستوى ضغط [`PngImage`](../../../aspose.imaging.fileformats.png/pngimage/) في النطاق من 0-9. كلما ارتفعت القيمة - كلما كان الضغط أكثر كفاءة.

```csharp
public int CompressionLevel { get; set; }
```

## أمثلة

يوضح المثال التالي كيفية ضغط صورة PNG باستخدام اللون المفهرس مع لوحة ألوان الأنسب.

```csharp
[C#]

// يحمّل صورة PNG
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // استخدم نوع اللون المفهرس.
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // استخدم أقصى ضغط.
         CompressionLevel = 9,
      // احصل على أقرب لوحة ألوان 8-بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة بلوحة ألوان
         // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // يجب أن يتم تقليل حجم ملف الإخراج بشكل كبير.
```

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


