---
title: BitsPerSample
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على أو تعيين وحدات البت لكل عينة.
type: docs
weight: 50
url: /ar/net/aspose.imaging.imageoptions/tiffoptions/bitspersample/
---
## TiffOptions.BitsPerSample property

الحصول على أو تعيين وحدات البت لكل عينة.

```csharp
public ushort[] BitsPerSample { get; set; }
```

### Property_Value

وحدات البت لكل قيمة نموذجية .

### ملاحظات

عند تعيين هذه القيمة ، ضع في اعتبارك أنها ستعمل أيضًا على تعيين قيمة SamplesPerPixel على طول الصفيف. هاتان الخاصيتان متقاربتان بإحكام شديد لذا يمكن ضبطهما معًا فقط.

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة TIFF من البداية وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// اضبط 8 بت لكل مكون من مكونات اللون.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// تعيين ترتيب بايت Endian الكبير (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// اضبط ضغط LZW.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// اضبط نموذج ألوان RGB.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// سيتم تخزين جميع مكونات اللون في مستوى واحد.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// قم بإنشاء إطار TIFF بحجم 100 × 100 بكسل.
// لاحظ أنه لا يتعين عليك التخلص من إطار بشكل صريح إذا تم تضمينه في TiffImage.
// عندما يتم التخلص من الحاوية ، سيتم التخلص من جميع الإطارات تلقائيًا.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// املأ الإطار بالكامل بالتدرج اللوني الأزرق والأصفر.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// إنشاء صورة TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

يوضح المثال التالي كيفية تكوين TIFF متعدد الأشكال من الصور النقطية الفردية.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // هذا هو الخط والفرشاة لرسم النص على إطارات فردية.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // إنشاء 5 إطارات
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // قم بإنشاء صورة PNG وارسم رقم الصفحة عليها.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // إنشاء إطار بناءً على صورة PNG.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // أضف الإطار إلى صورة TIFF.
        tiffImage.AddFrame(frame);
    }

    // تم إنشاء الصورة بإطار افتراضي واحد. دعونا نزيله.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // لا تنس التخلص من الإطار إذا لم تقم بإضافته إلى بعض صور TiffImage الأخرى
    activeFrame.Dispose();

    tiffImage.Save();
}
```

يوضح المثال التالي كيفية إنشاء نسخة بتدرج الرمادي لإطار موجود وإضافته إلى صورة TIFF.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم وليس مؤقتًا.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العلوية إلى الزاوية اليمنى السفلية للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الإطار النشط بفرشاة متدرجة خطية.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // خيارات تدرج الرمادي
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // إنشاء نسخة بتدرج الرمادي من الإطار النشط.
    // يتم الاحتفاظ ببيانات البكسل ولكن يتم تحويلها إلى التنسيق المطلوب.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // أضف الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

يوضح هذا المثال كيفية حفظ صورة نقطية بتنسيق TIFF باستخدام خيارات متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// اضبط 8 بت لكل مكون من مكونات اللون.
saveOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// تعيين ترتيب بايت Endian الكبير (Motorola)
saveOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// اضبط ضغط LZW.
saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// السماح بتقليل حجم الصور ذات الدرجة اللونية المستمرة.
// حاليًا يُستخدم هذا الحقل فقط مع ترميز LZW لأن LZW ربما يكون مخطط ترميز TIFF الوحيد
// التي تستفيد بشكل كبير من خطوة التنبؤ.
saveOptions.Predictor = Imaging.FileFormats.Tiff.Enums.TiffPredictor.Horizontal;

// اضبط نموذج ألوان RGB.
saveOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// بالنسبة إلى YCbCr ، يمكنك استخدام أحد الخيارات التالية:
// YCbCrSubSubSampling Field عوامل أخذ عينات JPEG
// ----------------------------------------------
// 1،1 1x1، 1x1، 1x1
// 2،1 2x1، 1x1، 1x1
// 2،2 (القيمة الافتراضية) 2x2، 1x1، 1x1
// saveOptions.YCbCrSubsampling = new ushort [] {2، 2};

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
saveOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// قم بإنشاء إطار TIFF بحجم 100 × 100 بكسل.
using (Aspose.Imaging.Image image = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ الصورة بأكملها بالتدرج اللوني الأزرق والأصفر.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(image.Width, image.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save(dir + "output.tif", saveOptions);
}
```

يوضح هذا المثال كيفية إنشاء صورة TIFF بإطارين وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// خيارات الإطار الأول
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// اضبط 8 بت لكل مكون من مكونات اللون.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// تعيين ترتيب بايت Endian الكبير (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// اضبط ضغط LZW.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// اضبط نموذج ألوان RGB.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// سيتم تخزين جميع مكونات اللون في مستوى واحد.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// أنشئ أول إطار TIFF بحجم 100x100 بكسل.
// لاحظ أنه لا يتعين عليك التخلص من الإطارات بشكل صريح إذا تم تضمينها في TiffImage.
// عندما يتم التخلص من الحاوية ، سيتم التخلص من جميع الإطارات تلقائيًا.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// املأ الإطار الأول بالتدرج اللوني الأزرق والأصفر.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// خيارات الإطار الأول
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// ضبط 1 بت لكل بكسل لصورة B / W.
createOptions2.BitsPerSample = new ushort[] { 1 };

// تعيين ترتيب بايت Little Endian (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// تعيين ضغط الفاكس CCITT Group 3.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// اضبط نموذج اللون B / W حيث يكون 0 أسود و 1 أبيض.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// أنشئ إطار TIFF الثاني بحجم 200 × 200 بكسل.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// املأ الإطار الثاني بالتدرج اللوني الأزرق والأصفر.
// سيتم تحويله تلقائيًا إلى تنسيق B / W بسبب الإعدادات المقابلة للإطار.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// إنشاء صورة TIFF.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### أنظر أيضا

* class [TiffOptions](../../tiffoptions)
* مساحة الاسم [Aspose.Imaging.ImageOptions](../../tiffoptions)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
