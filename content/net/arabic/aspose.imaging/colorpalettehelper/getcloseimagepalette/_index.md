---
title: GetCloseImagePalette
second_title: Aspose.Imaging لمرجع NET API
description: الحصول على لوحة ألوان من الصورة النقطية palletizes image في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة  سيتم استخدامها بدلاً من إجراء الحسابات.
type: docs
weight: 60
url: /ar/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_3}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي على*entriesCount* إدخالات .

### أمثلة

يقوم المثال التالي بتحميل صورة BMP وحفظها مرة أخرى في BMP باستخدام خيارات حفظ متنوعة.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // إنشاء BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
    saveOptions.BitsPerPixel = 8;

    // قم بتعيين أقرب لوحة ألوان 8 بت تغطي العدد الأقصى لوحدات البكسل للصورة ، بحيث تكون الصورة ذات لوحة الألوان
    // يكاد لا يمكن تمييزه بصريًا عن غير المنقول.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // حفظ بدون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // اضبط الدقة الأفقية والعمودية على 96 نقطة في البوصة.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

يوضح المثال التالي كيفية نقل صورة BMP إلى منصات نقالة لتقليل حجم الإخراج.

```csharp
[C#]

// قم بإنشاء صورة BMP 100 × 100 بكسل.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // التدرج الخطي من الزاوية اليسرى العلوية إلى الزاوية اليمنى السفلية للصورة.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // املأ الصورة بأكملها بفرشاة التدرج الخطي.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // احصل على أقرب لوحة ألوان 8 بت تغطي أكبر عدد ممكن من وحدات البكسل ، بحيث تكون الصورة ملوّنة
    // يكاد لا يمكن تمييزه بصريًا عن غير المنقول.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // تحتوي اللوحة 8 بت على 256 لونًا بحد أقصى.
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

// يبدو الإخراج كالتالي:
// حجم الصورة باليت هو 11078 بايت.
// حجم الصورة غير المصقول هو 40054 بايت.
```

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* مساحة الاسم [Aspose.Imaging](../../colorpalettehelper)
* المجسم [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, int, PaletteMiningMethod) {#getcloseimagepalette_4}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. لوحة الألوان على وشك تحسين جودة الصورة المفهرسة أو التقاطها "كما هي" عند استخدام PaletteMiningMethod.UseCurrentPalette.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |
| paletteMiningMethod | PaletteMiningMethod | طريقة تعدين الألواح. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي على*entriesCount* إدخالات .

### أمثلة

يوضح المثال التالي كيفية ضغط صورة PNG ، باستخدام لون مفهرس مع أفضل لوحة ملائمة

```csharp
[C#]

// تحميل صورة png        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // استخدم نوع اللون المفهرس
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // استخدم أقصى ضغط
         CompressionLevel = 9,
      // احصل على أقرب لوحة ألوان 8 بت تغطي أكبر عدد ممكن من وحدات البكسل ، بحيث تكون الصورة ملوّنة
         // يكاد لا يمكن تمييزه بصريًا عن غير المنقول.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // يجب تقليل حجم الملف الناتج بشكل كبير
```

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* مساحة الاسم [Aspose.Imaging](../../colorpalettehelper)
* المجسم [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي على*entriesCount* إدخالات .

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* مساحة الاسم [Aspose.Imaging](../../colorpalettehelper)
* المجسم [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |
| useImagePalette | Boolean | إذا تم ضبطه ، فسيستخدم لوحة الصور الخاصة به إذا كان ذلك متاحًا |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي على*entriesCount* إدخالات .

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* مساحة الاسم [Aspose.Imaging](../../colorpalettehelper)
* المجسم [Aspose.Imaging](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool, Color) {#getcloseimagepalette_2}

الحصول على لوحة ألوان من الصورة النقطية (palletizes image) في حالة عدم احتواء الصورة على واحدة. في حالة وجود لوحة ، سيتم استخدامها بدلاً من إجراء الحسابات.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette, Color alphaBlendInColor)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| image | RasterImage | الصورة النقطية. |
| destBounds | Rectangle | حدود الصورة الوجهة. |
| entriesCount | Int32 | عدد الإدخالات المطلوبة. |
| useImagePalette | Boolean | إذا تم ضبطه ، فسيستخدم لوحة الصور الخاصة به إذا كان ذلك متاحًا |
| alphaBlendInColor | Color | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |

### قيمة الإرجاع

لوحة الألوان التي تبدأ بأكثر الألوان شيوعًا من*image* ويحتوي على*entriesCount* إدخالات .

### أنظر أيضا

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* struct [Color](../../color)
* class [ColorPaletteHelper](../../colorpalettehelper)
* مساحة الاسم [Aspose.Imaging](../../colorpalettehelper)
* المجسم [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
