---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "طريقة ColorPaletteHelper. يحصل على لوحة ألوان من صورة نقطية تقوم بإنشاء لوحة ألوان للصورة إذا لم تكن لها واحدة. في حال وجود لوحة ألوان، سيتم استخدامها بدلاً من إجراء الحسابات"
type: docs
weight: 70
url: /ar/net/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_4}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. إذا وجدت لوحة، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

## أمثلة

المثال التالي يحمل صورة BMP ويحفظها مرة أخرى كـ BMP باستخدام خيارات حفظ مختلفة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // إنشاء BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // استخدم 8 بتات لكل بكسل لتقليل حجم صورة الإخراج.
    saveOptions.BitsPerPixel = 8;

    // حدد أقرب لوحة ألوان 8‑bit التي تغطي الحد الأقصى من بكسلات الصورة، بحيث تكون الصورة مُلوَّنة بلوحة ألوان
    // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // احفظ دون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
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

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_5}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. سيتم تحسين اللوحة للحصول على جودة صورة مفهرسة أفضل أو تُؤخذ "AS IS" عندما يُستخدم PaletteMiningMethod.UseCurrentPalette.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |
| paletteMiningMethod | PaletteMiningMethod | طريقة استخراج لوحة الألوان. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

## أمثلة

يوضح المثال التالي كيفية ضغط صورة PNG باستخدام اللون المفهرس مع لوحة ألوان الأنسب.

```csharp
[C#]

// يحمّل صورة PNG
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // استخدم نوع اللون المفهرس.
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // استخدم أقصى ضغط.
         CompressionLevel = 9,
      // احصل على أقرب لوحة ألوان 8-بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة بلوحة ألوان
         // تقريبًا لا يمكن تمييزها بصريًا عن صورة غير ملوّنة بلوحة ألوان.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // يجب أن يتم تقليل حجم ملف الإخراج بشكل كبير.
```

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* enum [PaletteMiningMethod](../../paletteminingmethod/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. إذا وجدت لوحة، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. إذا وجدت لوحة، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |
| useImagePalette | Boolean | إذا تم الضبط، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متوفرة |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. إذا وجدت لوحة، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |
| useImagePalette | Boolean | إذا تم الضبط، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متوفرة |
| alphaBlendInColor | لون | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color, bool) {#getcloseimagepalette_3}

يحصل على لوحة ألوان من صورة نقطية (يقوم بإنشاء لوحة من الصورة) في حال عدم وجود لوحة للصور. إذا وجدت لوحة، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor, bool keepTransparency)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوب. |
| useImagePalette | Boolean | إذا تم الضبط، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متوفرة |
| alphaBlendInColor | لون | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |
| keepTransparency | Boolean | إذا تم التعيين، فسيأخذ في الاعتبار بتات قناة ألفا لألوان الصورة. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان تكرارًا من *الصورة* وتحتوي على *entriesCount* إدخالًا.

### انظر أيضًا

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


