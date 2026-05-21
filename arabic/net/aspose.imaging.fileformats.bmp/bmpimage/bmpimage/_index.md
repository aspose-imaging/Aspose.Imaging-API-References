---
title: "BmpImage.BmpImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ BmpImage. ابدأ باستخدام فئة BmpImage بسهولة مع هذا المنشئ الذي يهيئ نسخة جديدة. مثالي للمطورين الذين يرغبون في البدء بسرعة وكفاءة مع كائنات BmpImage"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

ابدأ باستخدام فئة BmpImage بسهولة مع هذا المنشئ الذي يهيئ نسخة جديدة. مثالي للمطورين الذين يرغبون في البدء بسرعة وكفاءة مع كائنات [`BmpImage`](../).

```csharp
public BmpImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة الراستر فارغة. |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

يوضح المثال كيفية تحميل BmpImage من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة BMP من ملف.
// سيتم تحويل بكسلات المصدر إلى تنسيق 32‑bpp إذا لزم الأمر.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // قم ببعض معالجة الصورة.
    // احفظ إلى ملف BMP آخر.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### انظر أيضًا

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

أنشئ بسهولة نسخة جديدة من فئة [`BmpImage`](../) باستخدام هذا المنشئ، مع تحديد المعلمات مثل المسار، bitsPerPixel، والضغط. مثالي للمطورين الذين يرغبون في تهيئة كائنات BmpImage بسرعة وكفاءة، مع تحكم دقيق في خصائص الصورة.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |
| bitsPerPixel | UInt16 | عدد البتات لكل بكسل. |
| ضغط | BitmapCompression | الضغط المراد استخدامه. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |
| verticalResolution | Double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة الراستر فارغة. |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

يوضح المثال كيفية تحميل BmpImage من ملف مع عمق البت والدقة المحددين.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة BMP من ملف.
// سيتم تحويل بكسلات المصدر إلى تنسيق 24‑bpp إذا لزم الأمر.
// سيتم ضبط الدقة إلى 96 نقطة في البوصة.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // قم ببعض معالجة الصورة.
    // احفظ إلى ملف BMP آخر.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### انظر أيضًا

* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

ابدأ باستخدام فئة [`BmpImage`](../) بسهولة عن طريق تهيئة نسخة جديدة باستخدام هذا المنشئ، مع استخدام تدفق كمدخل. مثالي للمطورين الذين يبحثون عن طريقة مريحة للعمل مع كائنات BmpImage من مصادر بيانات مختلفة، مما يضمن المرونة وسهولة التكامل.

```csharp
public BmpImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة الراستر فارغة. |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

يوضح المثال كيفية تحميل BmpImage من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة BMP من تدفق ملف.
// سيتم تحويل بكسلات المصدر إلى تنسيق 32‑bpp إذا لزم الأمر.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // قم ببعض معالجة الصورة.
        // احفظ إلى ملف BMP آخر.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### انظر أيضًا

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

ابدأ العمل مع فئة [`BmpImage`](../) بسلاسة عن طريق إنشاء نسخة جديدة باستخدام تدفق، مع المعلمات المحددة مثل bitsPerPixel والضغط. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |
| bitsPerPixel | UInt16 | عدد البتات لكل بكسل. |
| ضغط | BitmapCompression | الضغط المراد استخدامه. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |
| verticalResolution | Double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة الراستر فارغة. |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

المثال يوضح كيفية تحميل BmpImage من تدفق ملف مع عمق البت والدقة المحددين.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة BMP من تدفق ملف.
// سيتم تحويل بكسلات المصدر إلى تنسيق 24‑bpp إذا لزم الأمر.
// سيتم ضبط الدقة إلى 96 نقطة في البوصة.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // قم ببعض معالجة الصورة.
        // احفظ إلى ملف BMP آخر.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### انظر أيضًا

* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

أنشئ بسهولة نسخة جديدة من فئة [`BmpImage`](../) عن طريق تهيئتها بكائن RasterImage. مثالي للمطورين الذين يرغبون في تحويل الصور النقطية الحالية إلى تنسيق BmpImage بسلاسة، مما يضمن التوافق وسهولة الدمج في مشاريعهم.

```csharp
public BmpImage(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة لتهيئة بيانات البكسل ولوحة الألوان بها. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة الراستر فارغة. |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

المثال يوضح كيفية تحميل BmpImage من نسخة أخرى من RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG جديدة.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // املأ صورة PNG بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // إنشاء صورة BMP بناءً على صورة PNG.
    // سيتم تحويل بكسلات المصدر إلى تنسيق 32‑bpp إذا لزم الأمر.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // حفظ إلى ملف BMP
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

ابدأ العمل مع فئة [`BmpImage`](../) بسلاسة عن طريق إنشاء نسخة جديدة باستخدام rasterImage مع المعلمات المحددة مثل bitsPerPixel والضغط. مثالي للمطورين الذين يبحثون عن طريقة مباشرة للتعامل مع كائنات BmpImage، مما يضمن المرونة والكفاءة في مشاريعهم.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة لتهيئة بيانات البكسل ولوحة الألوان بها. |
| bitsPerPixel | UInt16 | عدد البتات لكل بكسل. |
| ضغط | BitmapCompression | الضغط المراد استخدامه. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |
| verticalResolution | Double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة الراستر فارغة. |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

المثال يوضح كيفية تحميل BmpImage من نسخة أخرى من RasterImage مع عمق البت والضغط المحددين.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG جديدة.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // املأ صورة PNG بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // إنشاء صورة BMP بناءً على صورة PNG.
    // سيتم تحويل بكسلات المصدر إلى تنسيق 24‑bpp إذا لزم الأمر.
    // سيتم ضبط الدقة إلى 96 نقطة في البوصة.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // حفظ إلى ملف BMP
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

ابدأ باستخدام فئة [`BmpImage`](../) بسهولة عن طريق إنشاء نسخة جديدة مع معلمات العرض والارتفاع المحددة. مثالي للمطورين الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة، مما يضمن المرونة وسهولة الدمج في مشاريعهم.

```csharp
public BmpImage(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

المثال يوضح كيفية إنشاء BmpImage بالحجم المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة BMP بعمق 32 بت بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // حفظ إلى ملف BMP
    bmpImage.Save(dir + "output.bmp");
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

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

ابدأ باستخدام فئة [`BmpImage`](../) بسلاسة عن طريق تهيئة نسخة جديدة مع معلمات مثل العرض، الارتفاع، عمق البت، واللوحة. مثالي للمطورين الذين يبحثون عن طريقة مباشرة لإنشاء كائنات BmpImage بأبعاد مخصصة وتكوينات ألوان، مما يضمن المرونة والكفاءة في مشاريعهم.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |
| bitsPerPixel | UInt16 | عدد البتات لكل بكسل. |
| palette | IColorPalette | لوحة الألوان. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

المثال يوضح كيفية إنشاء BmpImage بالحجم المحدد مع اللوحة المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// أنشئ لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// إنشاء صورة BMP أحادية اللون بدقة 1‑bpp بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // املأ النصف العلوي من الصورة باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // املأ النصف السفلي من الصورة باللون الأخضر.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // حفظ إلى BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### انظر أيضًا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

أنشئ بسهولة نسخة جديدة من فئة [`BmpImage`](../) باستخدام هذا المُنشئ، مع تحديد المعلمات مثل العرض، الارتفاع، bitsPerPixel، واللوحة. مثالي للمطورين الذين يبحثون عن طريقة مريحة لإنشاء كائنات BmpImage بأبعاد مخصصة وتكوينات ألوان، مما يضمن المرونة وسهولة الدمج في مشاريعهم.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة. |
| الارتفاع | Int32 | ارتفاع الصورة. |
| bitsPerPixel | UInt16 | عدد البتات لكل بكسل. |
| palette | IColorPalette | لوحة الألوان. |
| ضغط | BitmapCompression | الضغط المراد استخدامه. |
| horizontalResolution | Double | الدقة الأفقية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |
| verticalResolution | Double | الدقة العمودية. ملاحظة: بسبب التقريب قد تختلف الدقة الناتجة قليلًا عن القيمة المُمرَّرة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception/) | يجب أن يكون الارتفاع إيجابيًا. |
| ArgumentException | يجب تحديد لوحة الألوان للصور التي تحتوي على 8 بتات لكل بكسل أو أقل. |

## أمثلة

المثال يوضح كيفية إنشاء BmpImage باستخدام خيارات متعددة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// أنشئ لوحة ألوان أحادية اللون تحتوي فقط على اللونين الأحمر والأخضر.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// إنشاء صورة BMP أحادية اللون بدقة 1‑bpp بحجم 100 × 100 بكسل.
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

    // حفظ إلى ملف BMP
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### انظر أيضًا

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* enum [BitmapCompression](../../bitmapcompression/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


