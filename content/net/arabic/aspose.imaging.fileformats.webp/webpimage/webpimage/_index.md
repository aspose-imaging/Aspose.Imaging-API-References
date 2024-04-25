---
title: WebPImage
second_title: Aspose.Imaging لمرجع NET API
description: يقوم بتهيئة مثيل جديد لملفWebPImageaspose.imaging.fileformats.webp/webpimage class من تيار .
type: docs
weight: 10
url: /ar/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) class من تيار .

```csharp
public WebPImage(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | صورة تيار WebP. |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة WebP من دفق ملف وحفظها في PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة WebP من دفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // حفظ في PNG
    // لاحظ أنه سيتم تخزين الإطار النشط فقط في PNG ، نظرًا لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة من تيار .

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | صورة تيار WebP. |
| loadOptions | LoadOptions | خيارات التحميل. |

### أنظر أيضا

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة من ملف .

```csharp
public WebPImage(string path)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار ملف WebP Image |

### أمثلة

يوضح هذا المثال كيفية تحميل صورة WebP من ملف وحفظها في PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة WebP من ملف.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // حفظ في PNG
    // لاحظ أنه سيتم تخزين الإطار النشط فقط في PNG ، نظرًا لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### أنظر أيضا

* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة من ملف .

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| path | String | مسار ملف WebP Image |
| loadOptions | LoadOptions | خيارات التحميل. |

### أنظر أيضا

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة من الصورة النقطية.

```csharp
public WebPImage(RasterImage rasterImage)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP من صورة نقطية أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";

// قم بتحميل صورة PNG بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // قم بإنشاء صورة WebP بناءً على صورة PNG.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // حفظ في ملف WebP بالخيارات الافتراضية
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة من الصورة النقطية.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |
| loadOptions | LoadOptions | خيارات التحميل. |

### أنظر أيضا

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة مع صورة فارغة.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة |
| height | Int32 | ارتفاع الصورة. |
| options | WebPOptions | الخيارات. |

### أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP بالخيارات المحددة من البداية.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource (dir + "output.webp") ;

// قم بإنشاء صورة WebP بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // املأ الصورة بأكملها باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // حفظ في ملف WebP
    webPImage.Save(dir + "output.webp");
}
```

يوضح هذا المثال كيفية إنشاء صورة WebP متحركة متعددة الإطارات باستخدام الخيارات المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// الإطار الافتراضي بالإضافة إلى 36 + 36 إطارًا إضافيًا.
createOptions.AnimLoopCount = 36 + 36 + 1;

// قم بإنشاء صورة WebP بحجم 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد زاوية شكل القوس الأحمر تدريجيًا.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // زد زاوية القوس الأسود تدريجيًا وامسح القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // حفظ في ملف WebP
    webPImage.Save(dir + "output.webp");
}
```

### أنظر أيضا

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`WebPImage`](../../webpimage) فئة مع صورة فارغة.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| width | Int32 | عرض الصورة |
| height | Int32 | ارتفاع الصورة. |
| options | WebPOptions | الخيارات. |
| loadOptions | LoadOptions | خيارات التحميل. |

### أنظر أيضا

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions)
* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [WebPImage](../../webpimage)
* مساحة الاسم [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
