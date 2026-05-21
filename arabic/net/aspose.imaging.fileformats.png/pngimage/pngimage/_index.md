---
title: "PngImage.PngImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ PngImage. قم بتهيئة كائن جديد من فئة PngImage عن طريق توفير معلمات العرض والارتفاع. يبسط هذا المنشئ إنشاء صور PNG من خلال السماح للمطورين بتحديد الأبعاد مباشرةً مما يسهل إدارة بيانات صور PNG بكفاءة داخل تطبيقاتهم."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage(int, int) {#constructor_3}

قم بتهيئة كائن جديد من الفئة [`PngImage`](../) عن طريق توفير معلمات العرض والارتفاع. يبسط هذا المنشئ إنشاء صور PNG من خلال السماح للمطورين بتحديد الأبعاد مباشرةً، مما يسهل إدارة بيانات صور PNG بكفاءة داخل تطبيقاتهم.

```csharp
public PngImage(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG بالحجم المحدد، ملؤها بلون صلب وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // قم ببعض معالجة الصور، مثل ملء الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // احفظ إلى ملف.
    pngImage.Save(dir + "output.png");
}
```

### انظر أيضًا

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(string) {#constructor_6}

ينشئ نسخة جديدة من الفئة [`PngImage`](../) باستخدام معامل المسار لتحديد موقع ملف الصورة المراد تحميله. يتيح هذا المنشئ للمطورين إنشاء صور PNG بسهولة عن طريق تحميلها من ملف، مما يبسط عملية التعامل مع صور PNG في تطبيقاتهم.

```csharp
public PngImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | The path to load an image. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة PNG من ملف.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // حوّل الصورة إلى تمثيل تدرج الرمادي.
    pngImage.Grayscale();

    // احفظ إلى ملف.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### انظر أيضًا

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(RasterImage) {#constructor_1}

ينشئ نسخة جديدة من الفئة [`PngImage`](../) عن طريق توفير صورة نقطية كمعامل. يتيح هذا المنشئ للمطورين تهيئة كائن صورة PNG مباشرةً باستخدام صورة نقطية موجودة، مما يبسط عملية التعامل مع صور PNG في تطبيقاتهم.

```csharp
public PngImage(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من صورة BMP.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة PNG ذات ألوان حقيقية (TrueColor) من صورة BMP.
// أولاً، أنشئ صورة BMP مؤقتة ستكون أساسًا لإنشاء صورة PNG.
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

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(string, PngColorType) {#constructor_7}

يُهيئ نسخة جديدة من الفئة [`PngImage`](../) عن طريق تحديد مسار ملف الصورة ونوع اللون. يتيح هذا المنشئ إنشاء صور PNG بسهولة من ملفات بأنواع ألوان مختلفة، مما يوفر مرونة في التعامل مع صيغ الصور المتنوعة.

```csharp
public PngImage(string path, PngColorType colorType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | The path to load an image. |
| colorType | PngColorType | نوع اللون. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException |  |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف بنوع اللون المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمِّل صورة PNG من ملف.
// لاحظ أن الصورة الملونة سيتم تحويلها إلى تدرج الرمادي تلقائيًا.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // احفظ إلى ملف.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### انظر أيضًا

* enum [PngColorType](../../pngcolortype/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(RasterImage, PngColorType) {#constructor_2}

ينشئ نسخة جديدة من الفئة [`PngImage`](../) عن طريق تحديد صورة نقطية ونوع اللون. يتيح هذا المنشئ للمطورين تحويل الصور النقطية مباشرةً إلى صيغة PNG مع تحديد نوع اللون المطلوب، مما يوفر مرونة في تمثيل الألوان.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |
| colorType | PngColorType | نوع اللون. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من صورة BMP بنوع اللون المحدد.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة PNG بتدرج الرمادي من صورة BMP ملونة.
// أولاً، أنشئ صورة BMP مؤقتة ستكون أساسًا لإنشاء صورة PNG.
// يمكنك أيضًا تحميل صورة BMP من ملف أو استخدام صورة بأي تنسيق نقطي آخر.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // املأ صورة BMP بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // سيتم تحويل ألوان بكسلات الصورة إلى نظيراتها بتدرج الرمادي.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* enum [PngColorType](../../pngcolortype/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(Stream) {#constructor_5}

ينشئ نسخة جديدة من الفئة [`PngImage`](../) عن طريق تهيئتها باستخدام تدفق. يتيح هذا المنشئ للمطورين تحميل صور PNG مباشرةً من تدفق، مما يوفر مرونة في استرجاع الصور من مصادر مختلفة.

```csharp
public PngImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | The stream to load an image. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة PNG من ملف أو من تدفق ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة PNG من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // حوّل الصورة إلى تمثيل تدرج الرمادي.
        pngImage.Grayscale();

        // احفظ إلى ملف.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### انظر أيضًا

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(int, int, PngColorType) {#constructor_4}

إنشاء نسخة جديدة من الفئة [`PngImage`](../) مع تحديد معلمات العرض والارتفاع ونوع اللون المطلوبة. يتيح هذا المُنشئ إنشاء صور PNG بسرعة بأبعاد وتكوينات لون مخصصة، مما يُسهل توليد الصور لتطبيقات وسير عمل مختلفة.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |
| colorType | PngColorType | نوع اللون. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG بالحجم المحدد ونوع اللون المحدد، تعبئتها بلون صلب وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بتدرج رمادي بحجم 100×100 بكسل.
// سيتم تحويل جميع الألوان تلقائيًا إلى تنسيق التدرج الرمادي.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // قم ببعض معالجة الصور، مثل ملء الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // احفظ إلى ملف.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### انظر أيضًا

* enum [PngColorType](../../pngcolortype/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)

---

## PngImage(PngOptions, int, int) {#constructor}

تهيئة نسخة جديدة من الفئة [`PngImage`](../) مع دمج خيارات PNG إلى جانب معلمات العرض والارتفاع. يتيح هذا المُنشئ للمطورين إنشاء صور PNG بإعدادات وأبعاد قابلة للتخصيص، مما يوفر مرونة في توليد الصور لحالات استخدام متنوعة.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| pngOptions | PngOptions | خيارات png. |
| العرض | Int32 | العرض. |
| الارتفاع | Int32 | الارتفاع. |

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

### انظر أيضًا

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions/)
* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


