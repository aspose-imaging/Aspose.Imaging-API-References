---
title: Jpeg2000Image
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفJpeg2000Imageaspose.imaging.fileformats.jpeg2000/jpeg2000image فئة .
type: docs
weight: 10
url: /ar/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل الصورة منه وتهيئة بيانات البكسل واللوحة به. |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة JPEG2000 من ملف وحفظها في PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة JPEG2000.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // حفظ في PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار تحميل الصورة منه وتهيئة بيانات البكسل واللوحة به |
| bitsPerPixel | Int32 | وحدات البت لكل بكسل. |

### أنظر أيضا

* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة باستخدام. |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة JPEG2000 من دفق ملف وحفظها في PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة JPEG2000 من الدفق.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // حفظ في PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | الدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة باستخدام. |
| bitsPerPixel | Int32 | وحدات البت لكل بكسل. |

### أنظر أيضا

* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(int width, int height)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة |
| height | Int32 | ارتفاع الصورة |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بإنشاء صورة بتنسيق JPEG2000 بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // حفظ في ملف
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### أنظر أيضا

* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة |
| height | Int32 | ارتفاع الصورة |
| options | Jpeg2000Options | الخيارات. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة PNG وحفظها في JPEG2000 بالخيارات المطلوبة.

```csharp
[C#]

string dir = "c:\\temp\\";

// أنشئ صورة PNG بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // استخدم التحويل المويجي المنفصل الذي لا رجعة فيه 9-7
    saveOptions.Irreversible = true;

    // JP2 هو تنسيق "الحاوية" لتدفقات رموز JPEG 2000.
    // J2K عبارة عن بيانات خام مضغوطة ، بدون غلاف.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // حفظ في ملف
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 بالخيارات المطلوبة وحفظها في ملف.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// استخدم التحويل المويجي المنفصل الذي لا رجعة فيه 9-7
createOptions.Irreversible = true;

// JP2 هو تنسيق "الحاوية" لتدفقات رموز JPEG 2000.
// J2K عبارة عن بيانات خام مضغوطة ، بدون غلاف.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// قم بإنشاء صورة بتنسيق JPEG2000 بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // حفظ في ملف
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### أنظر أيضا

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة |
| height | Int32 | ارتفاع الصورة |
| bitsCount | Int32 | البتات العد. |

### أنظر أيضا

* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(RasterImage image)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة JPEG2000 باستخدام صورة نقطية أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";

// أنشئ صورة PNG بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // قم بإنشاء صورة JPEG2000 بناءً على صورة PNG.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // حفظ في ملف
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`Jpeg2000Image`](../../jpeg2000image) فئة .

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة المراد تهيئة بيانات البكسل واللوحة بها. |
| bitsPerPixel | Int32 | وحدات البت لكل بكسل. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* مساحة الاسم [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
