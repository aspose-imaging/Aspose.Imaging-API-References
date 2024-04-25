---
title: FilterType
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على أو تحديد نوع المرشح المستخدم أثناء عملية حفظ ملف png.
type: docs
weight: 50
url: /ar/aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

الحصول على أو تحديد نوع المرشح المستخدم أثناء عملية حفظ ملف png.

```csharp
public PngFilterType FilterType { get; set; }
```

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG بالخيارات المحددة ، وتعبئتها بألوان متدرجة خطية وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// عدد البتات لكل قناة لون
createOptions.BitDepth = 8;

// كل بكسل عبارة عن ثلاثية (حمراء ، خضراء ، زرقاء) متبوعة بمكون ألفا.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// الحد الأقصى لمستوى الضغط.
createOptions.CompressionLevel = 9;

// يسمح استخدام المرشحات بضغط الصور ذات الدرجة اللونية المستمرة بشكل أكثر فعالية.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// استخدم التحميل التدريجي
createOptions.Progressive = true;

// إنشاء صورة PNG مع معلمات مخصصة.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بتدرج شبه شفاف.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // حفظ في ملف.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

يوضح المثال التالي كيف تؤثر أنواع المرشحات المختلفة على حجم صورة PNG الناتجة.

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
        // تعيين نوع عامل التصفية
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

// قد يبدو الإخراج كالتالي:
// نوع المرشح هو لا شيء ، وحجم صورة الإخراج هو 116845 بايت.
// نوع المرشح لأعلى ، وحجم صورة الإخراج هو 86360 بايت.
// نوع المرشح فرعي ، وحجم صورة الإخراج 94907 بايت.
// نوع المرشح هو Paeth ، وحجم صورة الإخراج هو 86403 بايت.
// نوع المرشح هو متوسط ، وحجم صورة الإخراج هو 89956 بايت.
// نوع المرشح متكيف ، وحجم صورة الإخراج 97248 بايت.
```

يوضح المثال التالي كيفية حفظ صورة بتنسيق PNG باستخدام خيارات متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

// أنشئ صورة PNG بحجم 100 × 100 بكسل.
// يمكنك أيضًا تحميل صورة بأي تنسيق مدعوم من ملف أو دفق.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بالتدرج اللوني الأزرق الشفاف.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // التحميل التدريجي.
    saveOptions.Progressive = true;

    // اضبط الدقة الأفقية والعمودية على 96 بكسل لكل بوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // كل بكسل عبارة عن ثلاثية (حمراء ، خضراء ، زرقاء) متبوعة بألفا.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // تعيين الحد الأقصى لمستوى الضغط.
    saveOptions.CompressionLevel = 9;

    // هذا هو أفضل ضغط ، لكنه أبطأ وقت تنفيذ.
    // التصفية التكيفية تعني أن عملية الحفظ ستختار مرشحًا أكثر قابلية للتغير لكل صف بيانات.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // عدد البتات لكل قناة.
    saveOptions.BitDepth = 8;

    // حفظ في ملف.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### أنظر أيضا

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../pngoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
