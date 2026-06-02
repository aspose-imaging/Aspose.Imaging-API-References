---
title: "BmpOptions.BitsPerPixel"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية BmpOptions. تحصل أو تعين عدد البتات لكل بكسل في الصورة"
type: docs
weight: 20
url: /ar/net/aspose.imaging.imageoptions/bmpoptions/bitsperpixel/
---
## BmpOptions.BitsPerPixel property

يحصل أو يضبط عدد البتات لكل بكسل في الصورة.

```csharp
public int BitsPerPixel { get; set; }
```

### Property Value

عدد البتات لكل بكسل في الصورة.

## أمثلة

المثال التالي يحمل صورة BMP ويحفظها مرة أخرى كـ BMP باستخدام خيارات حفظ مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // إنشاء BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // استخدم 8 بتات لكل بكسل لتقليل حجم صورة الإخراج.
    saveOptions.BitsPerPixel = 8;

    // حدد أقرب لوحة ألوان 8‑bit التي تغطي الحد الأقصى من بكسلات الصورة، بحيث تكون الصورة مُلوَّنة بلوحة ألوان
    // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // احفظ دون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

المثال التالي ينشئ صورة BMP بتدرج رمادي مُلوَّنة بلوحة ألوان ثم يحفظها إلى ملف

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// احفظ إلى ملف
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// استخدم 8 بتات لكل بكسل لتقليل حجم صورة الإخراج.
createOptions.BitsPerPixel = 8;

// حدد لوحة ألوان تدرج رمادي قياسية 8‑bit التي تغطي جميع ألوان التدرج الرمادي.
// إذا كانت الصورة المعالجة تحتوي فقط على ألوان تدرج رمادي، فإن نسختها المُلوَّنة بلوحة ألوان
// تكون غير قابلة للتمييز بصريًا عن نسخة غير مُلوَّنة بلوحة ألوان.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// احفظ دون ضغط.
// يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// أنشئ صورة BMP بحجم 100 × 100 بكسل واحفظها إلى ملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // املأ الصورة بتدرج رمادي
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

المثال التالي يوضح كيفية تلوين صورة BMP بلوحة ألوان لتقليل حجم الناتج.

```csharp
[C#]

// أنشئ صورة BMP بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الصورة بالكامل بفرشاة التدرج الخطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // احصل على أقرب لوحة ألوان 8-بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة بلوحة ألوان
    // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // لوحة الألوان 8‑bit تحتوي على ما لا يزيد عن 256 لونًا.
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

// الإخراج يبدو هكذا:
// حجم الصورة الملونة باللوحة هو 11078 بايت.
// حجم الصورة غير الملونة باللوحة هو 40054 بايت.
```

### انظر أيضًا

* class [BmpOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions/)
* assembly [Aspose.Imaging](../../../)


