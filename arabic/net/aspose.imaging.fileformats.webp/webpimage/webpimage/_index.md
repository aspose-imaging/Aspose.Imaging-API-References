---
title: "WebPImage.WebPImage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "منشئ WebPImage. إنشاء نسخة جديدة من فئة WebPImage مبدئية من مصدر تدفق مُقدم. استخدم هذا المنشئ لإنشاء كائنات صورة WebP مباشرةً من التدفقات بسلاسة، مما يتيح معالجة فعالة وتعديل بيانات صورة WebP داخل تطبيقك."
type: docs
weight: 10
url: /ar/net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

إنشاء نسخة جديدة من فئة [`WebPImage`](../) مبدئية من مصدر تدفق مُقدم. استخدم هذا المنشئ لإنشاء كائنات صورة WebP مباشرةً من التدفقات بسلاسة، مما يتيح معالجة فعالة وتعديل بيانات صورة WebP داخل تطبيقك.

```csharp
public WebPImage(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق صورة WebP. |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة WebP من تدفق ملف وحفظها بصيغة PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة WebP من تدفق ملف.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // حفظ إلى PNG
    // لاحظ أن الإطار النشط فقط سيتم تخزينه كـ PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../)، مبدئًا من مصدر ملف مُقدَّم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من الملفات بسلاسة، مما يُبسِّط عملية تحميل ومعالجة بيانات صورة WebP داخل تطبيقك.

```csharp
public WebPImage(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | مسار ملف صورة WebP |

## أمثلة

يوضح هذا المثال كيفية تحميل صورة WebP من ملف وحفظها كـ PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// تحميل صورة WebP من ملف.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // حفظ إلى PNG
    // لاحظ أن الإطار النشط فقط سيتم تخزينه كـ PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### انظر أيضًا

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../) باستخدام ملف وخيارات تحميل محددة، مما يُسهل التعامل المرن مع بيانات صورة WebP. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من الملفات مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | مسار ملف صورة WebP |
| loadOptions | LoadOptions | خيارات التحميل. |

### انظر أيضًا

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../)، مبدئًا من كائن rasterImage مُقدَّم. يتيح هذا المُنشئ تحويل صور raster إلى صيغة WebP بسلاسة، مما يُمكّن من التعامل الفعال ومعالجة بيانات الصورة داخل تطبيقك.

```csharp
public WebPImage(RasterImage rasterImage)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP من صورة raster أخرى.

```csharp
[C#]

string dir = "c:\\temp\\";

// حمّل صورة PNG بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // أنشئ صورة WebP بناءً على صورة PNG.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // احفظ إلى ملف WebP باستخدام الخيارات الافتراضية
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../) باستخدام كائن rasterImage وخيارات تحميل محددة، مما يُتيح التعامل المرن مع بيانات الصورة. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من صور raster مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | RasterImage | الصورة النقطية. |
| loadOptions | LoadOptions | خيارات التحميل. |

### انظر أيضًا

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../) بصورة فارغة بأبعاد عرض وارتفاع محددين. يتيح هذا المُنشئ إنشاء صور WebP فارغة، مما يوفر أساسًا للتلاعب اللاحق بالصورة وتوليد المحتوى داخل تطبيقك.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة |
| الارتفاع | Int32 | ارتفاع الصورة. |
| الخيارات | WebPOptions | الخيارات. |

## أمثلة

يوضح هذا المثال كيفية إنشاء صورة WebP من الصفر باستخدام الخيارات المحددة.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// إنشاء صورة WebP بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // املأ الصورة بالكامل باللون الأحمر.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // حفظ إلى ملف WebP
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

// إنشاء صورة WebP بحجم 100×100 بكسل.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // الدائرة الأولى حمراء
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // الدائرة الثانية سوداء
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // زد تدريجياً زاوية الشكل القوسي الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // زد تدريجياً زاوية القوس الأسود وأزل القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // حفظ إلى ملف WebP
    webPImage.Save(dir + "output.webp");
}
```

### انظر أيضًا

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../) بصورة فارغة وخيارات تحميل محددة. يتيح هذا المُنشئ تهيئة صور WebP مع معلمات تحميل قابلة للتخصيص، مما يوفر مرونة في إنشاء الصور ومعالجتها داخل تطبيقك.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | Int32 | عرض الصورة |
| الارتفاع | Int32 | ارتفاع الصورة. |
| الخيارات | WebPOptions | الخيارات. |
| loadOptions | LoadOptions | خيارات التحميل. |

### انظر أيضًا

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions/)
* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

أنشئ نسخة جديدة من الفئة [`WebPImage`](../) من تدفق، مع دمج خيارات تحميل محددة وإعدادات إدارة الذاكرة. يوفّر هذا المُنشئ مرونة في تحميل صور WebP من التدفقات مع إدارة موارد الذاكرة بكفاءة، مما يضمن أداءً مثاليًا واستخدامًا فعالًا للموارد داخل تطبيقك.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | تدفق صورة WebP. |
| loadOptions | LoadOptions | خيارات التحميل. |

### انظر أيضًا

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


