---
title: BitsPerPixel
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على أو تعيين عدد بتات الصورة لكل بكسل.
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/bmpoptions/bitsperpixel/
---
## BmpOptions.BitsPerPixel property

الحصول على أو تعيين عدد بتات الصورة لكل بكسل.

```csharp
public int BitsPerPixel { get; set; }
```

### Property_Value

عدد بتات الصورة لكل بكسل.

### أمثلة

يقوم المثال التالي بتحميل صورة BMP وحفظها مرة أخرى في BMP باستخدام خيارات حفظ متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // إنشاء BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
    saveOptions.BitsPerPixel = 8;

    // قم بتعيين أقرب لوحة ألوان 8 بت تغطي العدد الأقصى لوحدات البكسل للصورة ، بحيث تكون الصورة ذات لوحة الألوان
    // يكاد لا يمكن تمييزه بصريًا عن غير المنقول.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // حفظ بدون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // اضبط الدقة الأفقية والعمودية على 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

يُنشئ المثال التالي صورة BMP ذات تدرج رمادي متدرج ثم يحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// حفظ في ملف
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
createOptions.BitsPerPixel = 8;

// قم بتعيين لوحة الألوان القياسية ذات التدرج الرمادي 8 بت والتي تغطي جميع ألوان التدرج الرمادي.
// إذا كانت الصورة المعالجة تحتوي على ألوان ذات تدرج رمادي فقط ، فإن نسختها الملونة
// لا يمكن تمييزه بصريًا عن غير المنقول.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// حفظ بدون ضغط.
// يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// اضبط الدقة الأفقية والعمودية على 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// قم بإنشاء صورة BMP بحجم 100 × 100 بكسل واحفظها في ملف.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // املأ الصورة بتدرج الرمادي
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

يوضح المثال التالي كيفية نقل صورة BMP إلى منصات نقالة لتقليل حجم الإخراج.

```csharp
[C#]

// قم بإنشاء صورة BMP 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العلوية إلى الزاوية اليمنى السفلية للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الصورة بأكملها بفرشاة التدرج الخطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // احصل على أقرب لوحة ألوان 8 بت تغطي أكبر عدد ممكن من وحدات البكسل ، بحيث تكون الصورة ملوّنة
    // يكاد لا يمكن تمييزه بصريًا عن غير المنقول.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // تحتوي اللوحة 8 بت على 256 لونًا بحد أقصى.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// يبدو الإخراج كالتالي:
// حجم الصورة باليت هو 11078 بايت.
// حجم الصورة غير المصقول هو 40054 بايت.
```

### أنظر أيضا

* class [BmpOptions](../../bmpoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../bmpoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
