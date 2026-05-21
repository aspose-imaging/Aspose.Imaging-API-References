---
title: "Jpeg2000Image.Jpeg2000Image"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ Jpeg2000Image. ابدأ العمل مع فئة Jpeg2000Image بإنشاء مثيل جديد باستخدام المسار إلى الصورة التي تريد تحميلها. يتيح هذا المنشئ وصولًا سهلاً إلى صور JPEG2000، مبسطًا عملية تحميل ومعالجة ملفات الصور. من خلال توفير مسار الملف، يمكنك بسرعة بدء معالجة وتعديل صور JPEG2000 في تطبيقك"
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

ابدأ العمل مع فئة [`Jpeg2000Image`](../) عن طريق تهيئة نسخة جديدة مع المسار إلى الصورة التي تريد تحميلها. يتيح هذا المُنشئ الوصول السهل إلى صور JPEG2000، مبسطًا عملية تحميل ومعالجة ملفات الصور. من خلال توفير مسار الملف، يمكنك البدء بسرعة في معالجة وتعديل صور JPEG2000 في تطبيقك.

```csharp
public Jpeg2000Image(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة JPEG2000 من ملف وحفظها بصيغة PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة JPEG2000.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // حفظ إلى PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

ابدأ بسهولة مع فئة [`Jpeg2000Image`](../) بإنشاء نسخة جديدة باستخدام كل من مسار الملف ومعامل البتات لكل بكسل المطلوب. يتيح هذا المُنشئ ضبط عملية تحميل الصورة بدقة، مما يضمن التوافق مع صيغ الصور المختلفة وإعدادات الجودة. مع هذه المرونة، يمكنك إدارة وتعديل صور JPEG2000 بفعالية وفقًا لمتطلباتك الخاصة.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية باستخدام |
| bitsPerPixel | Int32 | عدد البتات لكل بكسل. |

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

قم بتهيئة نسخة جديدة من فئة [`Jpeg2000Image`](../) بسهولة عن طريق توفير كائن تدفق. يبسط هذا المُنشئ عملية تحميل صور JPEG2000 مباشرةً من التدفقات، مقدماً مرونة وراحة في التعامل مع بيانات الصور من مصادر مختلفة.

```csharp
public Jpeg2000Image(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة JPEG2000 من تدفق ملف وحفظها بصيغة PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة JPEG2000 من تدفق.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // حفظ إلى PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

تهيئة نسخة جديدة من فئة [`Jpeg2000Image`](../) باستخدام تدفق لتحميل الصورة، مع معاملات البتات لكل بكسل. يوفّر هذا المُنشئ مرونة من خلال السماح لك بتحديد كل من مصدر بيانات الصورة والبتات لكل بكسل المطلوبة، مما يمنح تحكمًا أدق في عملية تحميل الصورة.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |
| bitsPerPixel | Int32 | عدد البتات لكل بكسل. |

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

إنشاء نسخة جديدة من فئة [`Jpeg2000Image`](../)، مع تحديد معلمات العرض والارتفاع. يتيح هذا المُنشئ تهيئة صورة JPEG2000 بأبعاد محددة، وهو مفيد في السيناريوهات التي تحتاج فيها إلى إنشاء صورة بحجم معين برمجيًا.

```csharp
public Jpeg2000Image(int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة |
| الارتفاع | Int32 | ارتفاع الصورة |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة JPEG2000 بحجم 100x100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // احفظ إلى ملف
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

إنشاء كائن جديد من [`Jpeg2000Image`](../)، مع توفير معلمات العرض والارتفاع وخيارات الصورة. يتيح هذا المُنشئ إنشاء صور JPEG2000 بأبعاد محددة وخيارات إضافية، مقدمًا مرونة في توليد الصور.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة |
| الارتفاع | Int32 | ارتفاع الصورة |
| الخيارات | Jpeg2000Options | الخيارات. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG وحفظها إلى JPEG2000 مع الخيارات المطلوبة.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
    saveOptions.Irreversible = true;

    // JP2 هو تنسيق \"الحاوية\" لتدفقات JPEG 2000.
    // J2K هو بيانات مضغوطة خام، بدون غلاف.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // احفظ إلى ملف
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 مع الخيارات المطلوبة وحفظها إلى ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
createOptions.Irreversible = true;

// JP2 هو تنسيق \"الحاوية\" لتدفقات JPEG 2000.
// J2K هو بيانات مضغوطة خام، بدون غلاف.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// إنشاء صورة JPEG2000 بحجم 100x100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // احفظ إلى ملف
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### انظر أيضًا

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

إنشاء نسخة جديدة من فئة [`Jpeg2000Image`](../) مع معلمات العرض والارتفاع وعدد البتات. يتيح هذا المُنشئ إنشاء صور JPEG2000 بأبعاد محددة وعمق بتات، مقدماً مرونة لاحتياجات التصوير المختلفة.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة |
| الارتفاع | Int32 | ارتفاع الصورة |
| bitsCount | Int32 | عدد البتات. |

### انظر أيضًا

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

إنشاء نسخة جديدة من فئة [`Jpeg2000Image`](../) باستخدام صورة نقطية. يسهل هذا المُنشئ إنشاء صورة JPEG2000 من صورة نقطية موجودة، مقدماً تكاملًا سلسًا وتحويلًا بين صيغ الصور المختلفة.

```csharp
public Jpeg2000Image(RasterImage image)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 من صورة نقطية أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // إنشاء صورة JPEG2000 بناءً على صورة PNG.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // احفظ إلى ملف
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

تهيئة نسخة جديدة من [`Jpeg2000Image`](../) باستخدام صورة نقطية ومعاملات البتات لكل بكسل. يتيح هذا المُنشئ تحكمًا دقيقًا في جودة وحجم صورة JPEG2000 الناتجة، مما يجعلها مثالية للسيناريوهات التي تكون فيها التخصيصات ضرورية.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة لتهيئة بيانات البكسل ولوحة الألوان بها. |
| bitsPerPixel | Int32 | عدد البتات لكل بكسل. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


