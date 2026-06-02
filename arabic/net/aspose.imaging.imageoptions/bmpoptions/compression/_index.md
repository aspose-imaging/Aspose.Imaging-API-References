---
title: "BmpOptions.Compression"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية BmpOptions. يحصل أو يضبط نوع الضغط. نوع الضغط الافتراضي هو Bitfields الذي يسمح بحفظ BmpImage مع الشفافية"
type: docs
weight: 30
url: /ar/net/aspose.imaging.imageoptions/bmpoptions/compression/
---
## BmpOptions.Compression property

يحصل أو يضبط نوع الضغط. نوع الضغط الافتراضي هو Bitfields، الذي يسمح بحفظ [`BmpImage`](../../../aspose.imaging.fileformats.bmp/bmpimage/) مع الشفافية.

```csharp
public BitmapCompression Compression { get; set; }
```

### Property Value

نوع الضغط.

## أمثلة

فك ضغط صورة BMP التي تم ضغطها مسبقًا باستخدام خوارزمية ضغط DXT1.

```csharp
[C#]

using (var image = Image.Load("CompressedTiger.bmp"))
{
    image.Save("DecompressedTiger.bmp", new BmpOptions());
}
```

ضغط صورة BMP باستخدام خوارزمية ضغط DXT1.

```csharp
[C#]

using (var image = Image.Load("Tiger.bmp"))
{
    image.Save("CompressedTiger.bmp", new BmpOptions { Compression = BitmapCompression.Dxt1 });
}
```

يوضح المثال كيفية تصدير BmpImage بنوع الضغط Rgb.

```csharp
[C#]

string sourcePath = "input.png";
// حمِّل صورة PNG من ملف.
using (Image pngImage = Image.Load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة الضغط BitmapCompression.Bitfields.
    // لحفظ صورة BMP باستخدام طريقة الضغط Rgb، يجب تحديد BmpOptions مع خاصية Compression مضبوطة على BitmapCompression.Rgb.
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

يوضح المثال كيفية تصدير BmpImage من ملف Png مع الحفاظ على قناة ألفا، وحفظ ملف Bmp مع الشفافية.

```csharp
[C#]

string sourcePath = "input.png";
// حمِّل صورة PNG من ملف.
using (Image pngImage = Image.Load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا.
    // إذا كنت ترغب في تحديد هذا الوضع صراحةً، يجب ضبط خاصية Compression في BmpOptions على BitmapCompression.Bitfields.
    // طريقة الضغط BitmapCompression.Bitfields هي طريقة الضغط الافتراضية في BmpOptions.
    // لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية إما بإحدى الطرق التالية.
    // مع خيارات افتراضية ضمنية:
    pngImage.Save(outputPath);
    // مع خيارات افتراضية صريحة:
    pngImage.Save(outputPath, new BmpOptions());
    // تحديد طريقة الضغط BitmapCompression.Bitfields:
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

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

### انظر أيضًا

* enum [BitmapCompression](../../../aspose.imaging.fileformats.bmp/bitmapcompression/)
* class [BmpOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions/)
* assembly [Aspose.Imaging](../../../)


