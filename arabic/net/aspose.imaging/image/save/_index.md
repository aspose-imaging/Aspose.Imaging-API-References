---
title: "Image.Save"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة Image. تحفظ بيانات الصورة إلى الدفق الأساسي"
type: docs
weight: 310
url: /ar/net/aspose.imaging/image/save/
---
## Save() {#save}

يحفظ بيانات الصورة إلى الدفق الأساسي.

```csharp
public void Save()
```

## أمثلة

المثال التالي يوضح كيفية حفظ صورة BMP كاملة أو جزء منها إلى ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة بالأبيض والأسود
    bmpImage.BinarizeOtsu();

    // احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // لوحة الألوان تحتوي فقط على لونين: الأسود والأبيض في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // احفظ في موقع آخر باستخدام الخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ الجزء المركزي فقط من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // احفظ الصورة كاملة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//قد يبدو الإخراج هكذا:
//حجم الصورة بالكامل بالبايت: 24062
//حجم الجزء المركزي من الصورة بالبايت: 6046
```

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

يحفظ الصورة إلى موقع الملف المحدد.

```csharp
public override void Save(string filePath)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف لحفظ الصورة فيه. |

### انظر أيضًا

* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| الخيارات | ImageOptionsBase | الخيارات. |

## أمثلة

المثال التالي يحمل صورة BMP من ملف، ثم يحفظ الصورة إلى ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // احفظ الصورة كاملة إلى ملف PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

هذا المثال يوضح الخطوات البسيطة لحفظ صورة. لتوضيح هذه العملية، نقوم بتحميل ملف موجود من موقع على القرص، نجري عملية تدوير على الصورة ونحفظ الصورة بصيغة PSD باستخدام مسار الملف.

```csharp
[C#]

string dir = "c:\\temp\\";

//أنشئ مثيلاً من فئة image وابدأها بملف موجود عبر مسار الملف
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //دوران الصورة بزاوية 180 درجة حول المحور X
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //احفظ الصورة بصيغة PSD إلى مسار الملف باستخدام إعدادات PsdOptions الافتراضية
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

المثال التالي يوضح كيفية حفظ صورة BMP كاملة أو جزء منها إلى ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة بالأبيض والأسود
    bmpImage.BinarizeOtsu();

    // احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // لوحة الألوان تحتوي فقط على لونين: الأسود والأبيض في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // احفظ في موقع آخر باستخدام الخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ الجزء المركزي فقط من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // احفظ الصورة كاملة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//قد يبدو الإخراج هكذا:
//حجم الصورة بالكامل بالبايت: 24062
//حجم الجزء المركزي من الصورة بالبايت: 6046
```

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | String | مسار الملف. |
| الخيارات | ImageOptionsBase | الخيارات. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الهدف. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الخيارات |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | فشل حفظ الصورة. |

## أمثلة

المثال التالي يحمل صورة BMP من ملف، ثم يحفظ جزءًا مستطيلًا من الصورة إلى ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // احفظ النصف العلوي من الصورة إلى ملف PNG.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

المثال التالي يوضح كيفية حفظ صورة BMP كاملة أو جزء منها إلى ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة بالأبيض والأسود
    bmpImage.BinarizeOtsu();

    // احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // لوحة الألوان تحتوي فقط على لونين: الأسود والأبيض في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // احفظ في موقع آخر باستخدام الخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ الجزء المركزي فقط من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // احفظ الصورة كاملة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//قد يبدو الإخراج هكذا:
//حجم الصورة بالكامل بالبايت: 24062
//حجم الجزء المركزي من الصورة بالبايت: 6046
```

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لحفظ بيانات الصورة إليه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | لا يمكن الحفظ إلى الصيغة المحددة لأنها غير مدعومة في الوقت الحالي.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | فشل تصدير الصورة. |

## أمثلة

المثال التالي يحمل صورة من ملف، ثم يحفظ الصورة إلى دفق ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // احفظ الصورة بالكامل إلى تدفق ملف.
        image.Save(outputStream, saveOptions);
    }
}
```

يوضح هذا المثال عملية حفظ صورة إلى MemoryStream. لتوضيح هذه العملية، يقوم المثال بتحميل ملف موجود من موقع على القرص، ويجري عملية تدوير على الصورة ويحفظ الصورة بتنسيق PSD.

```csharp
[C#]

//إنشاء مثيل من MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //أنشئ مثيلاً من فئة image وابدأها بملف موجود عبر مسار الملف
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        //دوران الصورة بزاوية 180 درجة حول المحور X
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //احفظ الصورة بصيغة PSD إلى MemoryStream باستخدام إعدادات PsdOptions الافتراضية
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

المثال التالي يوضح كيفية حفظ صورة BMP كاملة أو جزء منها إلى ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة بالأبيض والأسود
    bmpImage.BinarizeOtsu();

    // احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // لوحة الألوان تحتوي فقط على لونين: الأسود والأبيض في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // احفظ في موقع آخر باستخدام الخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ الجزء المركزي فقط من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // احفظ الصورة كاملة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//قد يبدو الإخراج هكذا:
//حجم الصورة بالكامل بالبايت: 24062
//حجم الجزء المركزي من الصورة بالبايت: 6046
```

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | Stream | التدفق لحفظ بيانات الصورة إليه. |
| optionsBase | ImageOptionsBase | خيارات الحفظ. |
| boundsRectangle | Rectangle | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | لا يمكن الحفظ إلى الصيغة المحددة لأنها غير مدعومة في الوقت الحالي.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception/) | فشل تصدير الصورة. |

## أمثلة

يقوم المثال التالي بتحميل صورة من ملف، ثم يحفظ جزءًا مستطيلًا من الصورة إلى تدفق ملف PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // احفظ النصف العلوي من الصورة إلى تدفق ملف.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

المثال التالي يوضح كيفية حفظ صورة BMP كاملة أو جزء منها إلى ملف أو دفق.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // تحويل إلى صورة بالأبيض والأسود
    bmpImage.BinarizeOtsu();

    // احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // لوحة الألوان تحتوي فقط على لونين: الأسود والأبيض في هذه الحالة.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور بالأبيض والأسود) يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.BitsPerPixel = 1;

    // احفظ في موقع آخر باستخدام الخيارات المحددة.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ الجزء المركزي فقط من الصورة.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // احفظ الصورة كاملة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // احفظ الجزء المركزي من الصورة إلى دفق الذاكرة
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//قد يبدو الإخراج هكذا:
//حجم الصورة بالكامل بالبايت: 24062
//حجم الجزء المركزي من الصورة بالبايت: 6046
```

### انظر أيضًا

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.Imaging](../../image/)
* assembly [Aspose.Imaging](../../../)


