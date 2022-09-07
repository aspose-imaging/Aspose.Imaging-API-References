---
title: BmpImage
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفBmpImageaspose.imaging.fileformats.bmp/bmpimage فئة .
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل الصورة منه وتهيئة بيانات البكسل واللوحة به. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الصورة النقطية خالية ؛ rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية تحميل BmpImage من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة BMP من ملف.
// سيتم تحويل وحدات البكسل المصدر إلى تنسيق 32-bpp إذا لزم الأمر.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // قم ببعض معالجة الصور.
    // حفظ في ملف BMP آخر.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### أنظر أيضا

* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل الصورة منه وتهيئة بيانات البكسل واللوحة به. |
| bitsPerPixel | UInt16 | وحدات البت لكل بكسل. |
| compression | BitmapCompression | ضغط الاستخدام. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |
| verticalResolution | Double | الدقة الرأسية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن تكون الصورة النقطية خالية ؛ rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية تحميل BmpImage من ملف بعمق البت المحدد ودقة الوضوح.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة BMP من ملف.
// سيتم تحويل وحدات البكسل المصدر إلى تنسيق 24 bpp إذا لزم الأمر.
// سيتم ضبط الدقة على 96 نقطة في البوصة.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // قم ببعض معالجة الصور.
    // حفظ في ملف BMP آخر.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### أنظر أيضا

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة باستخدام. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن تكون الصورة النقطية خالية ؛ rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية تحميل BmpImage من دفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة BMP من دفق ملف.
// سيتم تحويل وحدات البكسل المصدر إلى تنسيق 32-bpp إذا لزم الأمر.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // قم ببعض معالجة الصور.
        // حفظ في ملف BMP آخر.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### أنظر أيضا

* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة باستخدام. |
| bitsPerPixel | UInt16 | وحدات البت لكل بكسل. |
| compression | BitmapCompression | ضغط الاستخدام. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |
| verticalResolution | Double | الدقة الرأسية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن تكون الصورة النقطية خالية ؛ rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية تحميل BmpImage من دفق ملف بعمق البت ودقة الوضوح المحددين.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة BMP من دفق ملف.
// سيتم تحويل وحدات البكسل المصدر إلى تنسيق 24 bpp إذا لزم الأمر.
// سيتم ضبط الدقة على 96 نقطة في البوصة.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // قم ببعض معالجة الصور.
        // حفظ في ملف BMP آخر.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### أنظر أيضا

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(RasterImage rasterImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة المراد تهيئة بيانات البكسل واللوحة بها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن تكون الصورة النقطية خالية ؛ rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية تحميل BmpImage من مثيل آخر لـ RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG جديدة.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // املأ صورة PNG بأكملها باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // قم بإنشاء صورة BMP بناءً على صورة PNG.
    // سيتم تحويل وحدات البكسل المصدر إلى تنسيق 32-bpp إذا لزم الأمر.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // حفظ في ملف BMP
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة المراد تهيئة بيانات البكسل واللوحة بها. |
| bitsPerPixel | UInt16 | وحدات البت لكل بكسل. |
| compression | BitmapCompression | ضغط الاستخدام. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |
| verticalResolution | Double | الدقة الرأسية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | لا يمكن أن تكون الصورة النقطية خالية ؛ rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية تحميل BmpImage من مثيل آخر لـ RasterImage بعمق البت والضغط المحددين.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG جديدة.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // املأ صورة PNG بأكملها باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // قم بإنشاء صورة BMP بناءً على صورة PNG.
    // سيتم تحويل وحدات البكسل المصدر إلى تنسيق 24 bpp إذا لزم الأمر.
    // سيتم ضبط الدقة على 96 نقطة في البوصة.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // حفظ في ملف BMP
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة. |
| height | Int32 | ارتفاع الصورة. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية إنشاء صورة BmpImage بالحجم المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء صورة BMP 32-bpp بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // حفظ في ملف BMP
    bmpImage.Save(dir + "output.bmp");
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

* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة. |
| height | Int32 | ارتفاع الصورة. |
| bitsPerPixel | UInt16 | وحدات البت لكل بكسل. |
| palette | IColorPalette | لوحة الألوان. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية إنشاء صورة BmpImage بالحجم المحدد باستخدام اللوحة المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// قم بإنشاء لوحة أحادية اللون تحتوي فقط على ألوان حمراء وخضراء.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// قم بإنشاء صورة BMP أحادية اللون 1-bpp بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // املأ النصف العلوي من الصورة باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // املأ النصف السفلي من الصورة باللون الأخضر.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // حفظ في BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### أنظر أيضا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`BmpImage`](../../bmpimage) فئة .

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة. |
| height | Int32 | ارتفاع الصورة. |
| bitsPerPixel | UInt16 | وحدات البت لكل بكسل. |
| palette | IColorPalette | لوحة الألوان. |
| compression | BitmapCompression | ضغط الاستخدام. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |
| verticalResolution | Double | الدقة الرأسية. ملاحظة نظرًا لتقريب الدقة الناتجة قد تختلف قليلاً عن الدقة التي تم تمريرها. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | يجب أن يكون الارتفاع موجبًا. |
| ArgumentException | يجب تحديد لوحة للصور ذات 8 بت لكل بكسل أو أقل. ؛ لوح |

### أمثلة

يوضح المثال كيفية إنشاء صورة BmpImage باستخدام خيارات متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// قم بإنشاء لوحة أحادية اللون تحتوي فقط على ألوان حمراء وخضراء.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// قم بإنشاء صورة BMP أحادية اللون 1-bpp بحجم 100 × 100 بكسل.
// سيتم ضبط الدقة الأفقية والعمودية على 96 نقطة في البوصة.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // املأ النصف العلوي من الصورة باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // املأ النصف السفلي من الصورة باللون الأخضر.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // حفظ في ملف BMP
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### أنظر أيضا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
