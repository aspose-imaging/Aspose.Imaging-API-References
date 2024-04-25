---
title: PngImage
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفPngImageaspose.imaging.fileformats.png/pngimage فئة .
type: docs
weight: 10
url: /ar/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | العرض . |
| height | Int32 | الارتفاع . |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG بالحجم المحدد ، وتعبئتها بلون خالص وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// أنشئ صورة PNG بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // قم ببعض عمليات معالجة الصور ، على سبيل المثال ، املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // حفظ في ملف.
    pngImage.Save(dir + "output.png");
}
```

### أنظر أيضا

* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل صورة . |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة PNG من ملف.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // تحويل الصورة إلى تمثيل تدرج الرمادي
    pngImage.Grayscale();

    // حفظ في ملف.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### أنظر أيضا

* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(RasterImage rasterImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية . |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من صورة BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة TrueColor PNG من صورة BMP.
// أولاً ، قم بإنشاء صورة BMP مؤقتة والتي ستكون أساسًا لبناء صورة PNG.
// يمكنك أيضًا تحميل صورة BMP من ملف أو استخدام صورة بأي تنسيق نقطي آخر.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ صورة BMP بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(string path, PngColorType colorType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل صورة . |
| colorType | PngColorType | نوع اللون . |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException |  |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف بنوع اللون المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة PNG من ملف.
// لاحظ أنه سيتم تحويل الصورة الملونة إلى تدرج الرمادي تلقائيًا.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // حفظ في ملف.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### أنظر أيضا

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية . |
| colorType | PngColorType | نوع اللون . |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من صورة BMP بنوع اللون المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة PNG ذات تدرج رمادي من صورة BMP ملونة.
// أولاً ، قم بإنشاء صورة BMP مؤقتة والتي ستكون أساسًا لبناء صورة PNG.
// يمكنك أيضًا تحميل صورة BMP من ملف أو استخدام صورة بأي تنسيق نقطي آخر.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ صورة BMP بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // سيتم تحويل ألوان بكسلات الصورة إلى نظيراتها ذات التدرج الرمادي.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل صورة . |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف أو تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة PNG من دفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // تحويل الصورة إلى تمثيل تدرج الرمادي
        pngImage.Grayscale();

        // حفظ في ملف.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### أنظر أيضا

* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | العرض . |
| height | Int32 | الارتفاع . |
| colorType | PngColorType | نوع اللون . |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG بالحجم المحدد بنوع اللون المحدد ، وتعبئته بلون خالص وحفظه في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بتدرج الرمادي بحجم 100 × 100 بكسل.
// سيتم تحويل جميع الألوان تلقائيًا إلى تنسيق التدرج الرمادي.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // قم ببعض عمليات معالجة الصور ، على سبيل المثال ، املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // حفظ في ملف.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### أنظر أيضا

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`PngImage`](../../pngimage) فئة .

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pngOptions | PngOptions | خيارات png . |
| width | Int32 | العرض . |
| height | Int32 | الارتفاع . |

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

### أنظر أيضا

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Png](../../pngimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
