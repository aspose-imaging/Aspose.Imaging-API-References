---
title: Save
second_title: Aspose.Imaging لمرجع NET API
description: يحفظ بيانات الصورة في التدفق الأساسي.
type: docs
weight: 240
url: /ar/aspose.imaging/image/save/
---
## Save() {#save}

يحفظ بيانات الصورة في التدفق الأساسي.

```csharp
public void Save()
```

### أمثلة

يوضح المثال التالي كيفية حفظ صورة BMP أو جزء منها في ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة أبيض وأسود
    bmpImage.BinarizeOtsu();

    // حفظ في نفس الموقع مع الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // تحتوي اللوحة على لونين فقط: أبيض وأسود في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) ، يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // حفظ في موقع آخر بالخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ فقط الجزء المركزي من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // حفظ الصورة بأكملها في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// قد يبدو الإخراج كالتالي:
// حجم الصورة بأكملها بالبايت: 24062
// حجم الجزء المركزي من الصورة بالبايت: 6046
```

### أنظر أيضا

* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

يحفظ الصورة في موقع الملف المحدد.

```csharp
public override void Save(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف الذي سيتم حفظ الصورة فيه. |

### أنظر أيضا

* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| options | ImageOptionsBase | الخيارات . |

### أمثلة

المثال التالي يقوم بتحميل صورة BMP من ملف ، ثم يحفظ الصورة في ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // احفظ الصورة بأكملها في ملف PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

يوضح هذا المثال الخطوات البسيطة لحفظ صورة. لإثبات هذه العملية ، نقوم بتحميل ملف موجود من بعض مواقع القرص ، ونقوم بإجراء عملية التدوير على الصورة وحفظ الصورة بتنسيق PSD باستخدام مسار الملف

```csharp
[C#]

string dir = "c:\\temp\\";

// إنشاء مثيل لفئة الصورة وتهيئته بملف موجود من خلال مسار الملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // قم بتدوير الصورة 180 درجة حول المحور X.
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    // احفظ الصورة بصيغة PSD في مسار الملف بإعدادات PsdOptions الافتراضية
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

يوضح المثال التالي كيفية حفظ صورة BMP أو جزء منها في ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة أبيض وأسود
    bmpImage.BinarizeOtsu();

    // حفظ في نفس الموقع مع الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // تحتوي اللوحة على لونين فقط: أبيض وأسود في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) ، يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // حفظ في موقع آخر بالخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ فقط الجزء المركزي من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // حفظ الصورة بأكملها في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// قد يبدو الإخراج كالتالي:
// حجم الصورة بأكملها بالبايت: 24062
// حجم الجزء المركزي من الصورة بالبايت: 6046
```

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

يحفظ بيانات الكائن في موقع الملف المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| options | ImageOptionsBase | الخيارات. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المسار. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | والخيارات |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | فشل حفظ الصورة. |

### أمثلة

يقوم المثال التالي بتحميل صورة BMP من ملف ، ثم يحفظ جزءًا مستطيلًا من الصورة في ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // احفظ النصف العلوي من الصورة في ملف PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

يوضح المثال التالي كيفية حفظ صورة BMP أو جزء منها في ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة أبيض وأسود
    bmpImage.BinarizeOtsu();

    // حفظ في نفس الموقع مع الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // تحتوي اللوحة على لونين فقط: أبيض وأسود في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) ، يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // حفظ في موقع آخر بالخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ فقط الجزء المركزي من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // حفظ الصورة بأكملها في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// قد يبدو الإخراج كالتالي:
// حجم الصورة بأكملها بالبايت: 24062
// حجم الجزء المركزي من الصورة بالبايت: 6046
```

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | التدفق الذي سيتم حفظ بيانات الصورة فيه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الخيارات |
| ArgumentException | لا يمكن الحفظ بالتنسيق المحدد لأنه غير مدعوم في الوقت الحالي.؛ optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | فشل تصدير الصورة. |

### أمثلة

المثال التالي يقوم بتحميل صورة من ملف ، ثم يحفظ الصورة في تدفق ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // احفظ الصورة بأكملها في دفق ملف.
        image.Save(outputStream, saveOptions);
    }
}
```

يوضح هذا المثال عملية حفظ صورة في MemoryStream. لتوضيح هذه العملية ، يقوم المثال بتحميل ملف موجود من بعض مواقع القرص ، وتنفيذ عملية التدوير على الصورة وحفظ الصورة بتنسيق PSD

```csharp
[C#]

// إنشاء مثيل MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    // إنشاء مثيل لفئة الصورة وتهيئته بملف موجود من خلال مسار الملف
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        // قم بتدوير الصورة 180 درجة حول المحور X.
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        // احفظ الصورة بصيغة PSD في MemoryStream باستخدام إعدادات PsdOptions الافتراضية
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

يوضح المثال التالي كيفية حفظ صورة BMP أو جزء منها في ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة أبيض وأسود
    bmpImage.BinarizeOtsu();

    // حفظ في نفس الموقع مع الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // تحتوي اللوحة على لونين فقط: أبيض وأسود في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) ، يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // حفظ في موقع آخر بالخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ فقط الجزء المركزي من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // حفظ الصورة بأكملها في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// قد يبدو الإخراج كالتالي:
// حجم الصورة بأكملها بالبايت: 24062
// حجم الجزء المركزي من الصورة بالبايت: 6046
```

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

يحفظ بيانات الصورة إلى التدفق المحدد بتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | التدفق الذي سيتم حفظ بيانات الصورة فيه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | الخيارات |
| ArgumentException | لا يمكن الحفظ بالتنسيق المحدد لأنه غير مدعوم في الوقت الحالي.؛ optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | فشل تصدير الصورة. |

### أمثلة

يقوم المثال التالي بتحميل صورة من ملف ، ثم يحفظ جزءًا مستطيلًا من الصورة في تدفق ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // احفظ النصف العلوي من الصورة في تدفق ملف.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

يوضح المثال التالي كيفية حفظ صورة BMP أو جزء منها في ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة أبيض وأسود
    bmpImage.BinarizeOtsu();

    // حفظ في نفس الموقع مع الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // تحتوي اللوحة على لونين فقط: أبيض وأسود في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) ، يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // حفظ في موقع آخر بالخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ فقط الجزء المركزي من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // حفظ الصورة بأكملها في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة في تيار الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
// قد يبدو الإخراج كالتالي:
// حجم الصورة بأكملها بالبايت: 24062
// حجم الجزء المركزي من الصورة بالبايت: 6046
```

### أنظر أيضا

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* مساحة الاسم [Aspose.Imaging](../../image)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
