---
title: "PngOptions.FilterType"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية PngOptions. تحصل أو تعيّن نوع الفلتر المستخدم أثناء عملية حفظ ملف png"
type: docs
weight: 40
url: /ar/net/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

يحصل أو يعيّن نوع الفلتر المستخدم أثناء عملية حفظ ملف png.

```csharp
public PngFilterType FilterType { get; set; }
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

المثال التالي يوضح كيف تؤثر أنواع الفلاتر المختلفة على حجم صورة PNG الناتجة.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // عيّن نوع الفلتر
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//قد يبدو الإخراج هكذا:
//نوع الفلتر هو None، حجم الصورة الناتجة هو 116845 بايت.
//نوع الفلتر هو Up، حجم الصورة الناتجة هو 86360 بايت.
//نوع الفلتر هو Sub، حجم الصورة الناتجة هو 94907 بايت.
//نوع الفلتر هو Paeth، حجم الصورة الناتجة هو 86403 بايت.
//نوع الفلتر هو Avg، حجم الصورة الناتجة هو 89956 بايت.
//نوع الفلتر هو Adaptive، حجم الصورة الناتجة هو 97248 بايت.
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

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype/)
* class [PngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../pngoptions/)
* assembly [Aspose.Imaging](../../../)


