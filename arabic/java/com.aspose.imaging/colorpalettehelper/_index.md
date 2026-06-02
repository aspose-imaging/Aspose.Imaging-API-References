---
title: "ColorPaletteHelper"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة المساعدة لتعديل لوحة الألوان."
type: docs
weight: 29
url: /ar/java/com.aspose.imaging/colorpalettehelper/
---
**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

فئة المساعدة لتعديل لوحة الألوان.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createMonochrome()](#createMonochrome--) | ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط. |
| [create4Bit()](#create4Bit--) | ينشئ لوحة ألوان 4 بت. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | ينشئ لوحة تدرج رمادي 4 بت. |
| [create8Bit()](#create8Bit--) | ينشئ لوحة ألوان 8 بت. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | ينشئ لوحة تدرج رمادي 8 بت. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseTransparentImagePalette(RasterImage image, int entriesCount)](#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)](#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)](#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-) | يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.imaging.RasterImage-) | احصل على لوحة ألوان موحدة مكونة من 256 لونًا. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.imaging.RasterImage-) | احصل على لوحة ألوان 256، مكوّنة من البتات العليا لقيم ألوان الصورة الأصلية. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.imaging.IColorPalette-) | يحدد ما إذا كانت اللوحة المحددة تحتوي على ألوان شفافة. |
| [createGrayscale(int bits)](#createGrayscale-int-) | يحصل على لوحة التدرج الرمادي لعدد البتات المحدد. |
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


ينشئ لوحة ألوان أحادية اللون تحتوي على لونين فقط.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Color palette for monochrome images.
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


ينشئ لوحة ألوان 4 بت.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


ينشئ لوحة تدرج رمادي 4 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minIsWhite | boolean | إذا تم تعيينه إلى `true` تبدأ اللوحة باللون الأبيض، وإلا تبدأ باللون الأسود. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


ينشئ لوحة ألوان 8 بت.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


ينشئ لوحة تدرج رمادي 8 بت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minIsWhite | boolean | إذا تم تعيينه إلى `true` تبدأ اللوحة باللون الأبيض، وإلا تبدأ باللون الأسود. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The 8 bit grayscale palette.

**Example: The following example creates a palettized grayscale BMP image and then saves it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.BmpOptions createOptions = new com.aspose.imaging.imageoptions.BmpOptions();

// احفظ إلى ملف
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.palette8bit.bmp", false));

// استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
createOptions.setBitsPerPixel(8);

// حدد لوحة ألوان التدرج الرمادي القياسية 8 بت التي تغطي جميع ألوان التدرج الرمادي.
// إذا كانت الصورة المعالجة تحتوي فقط على ألوان تدرج رمادي، فإن نسختها المحوّلة إلى لوحة ألوان
// تكون غير قابلة للتمييز بصريًا عن النسخة غير المحوّلة إلى لوحة ألوان.
createOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

// احفظ بدون ضغط.
// يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

// حدد الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
createOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

// أنشئ صورة BMP بحجم 100 × 100 بكسل واحفظها إلى ملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlack(),
            com.aspose.imaging.Color.getWhite());

    // املأ الصورة بتدرج رمادي
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save();
} finally {
    image.dispose();
}
```

### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة فستُستخدم بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| entriesCount | int | عدد الإدخالات المطلوب. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// إنشاء صورة BMP بحجم 100 × 100 بكسل.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلية للصورة.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // ملء الصورة بالكامل بفرشاة التدرج الخطي.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة باللوحة
    // تكاد تكون غير قابلة للتمييز بصريًا عن صورة غير ملوّنة باللوحة.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // لوحة ألوان 8‑بت تحتوي على ما لا يزيد عن 256 لونًا.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// المخرجات تبدو هكذا:
// حجم الصورة الملونة باللوحة هو 11078 بايت.
// حجم الصورة غير الملونة باللوحة هو 40054 بايت.
```

### getCloseTransparentImagePalette(RasterImage image, int entriesCount) {#getCloseTransparentImagePalette-com.aspose.imaging.RasterImage-int-}
```
public static IColorPalette getCloseTransparentImagePalette(RasterImage image, int entriesCount)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة فستُستخدم بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| entriesCount | int | عدد الإدخالات المطلوب. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod) {#getCloseImagePalette-com.aspose.imaging.RasterImage-int-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount, int paletteMiningMethod)
```


يحصل على لوحة الألوان من الصورة النقطية (يحوّل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. سيتم تحسين اللوحة للحصول على جودة صورة مفهرسة أفضل أو تُؤخذ "AS IS" عندما يتم استخدام PaletteMiningMethod.UseCurrentPalette.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| entriesCount | int | عدد الإدخالات المطلوب. |
| paletteMiningMethod | int | طريقة استخراج لوحة الألوان. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.

**Example: The following example shows how to compress a PNG image, using indexed color with best fit palette**

``` java

// يحمّل صورة PNG        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // استخدم نوع اللون المفهرس
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // استخدم أقصى ضغط
    options.setCompressionLevel(9);
    // احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة باللوحة
    // تكاد تكون غير قابلة للتمييز بصريًا عن صورة غير ملوّنة باللوحة.
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// يجب تقليل حجم ملف الإخراج بشكل كبير
```

### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة فستُستخدم بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | حدود الصورة الوجهة. |
| entriesCount | int | عدد الإدخالات المطلوب. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة فستُستخدم بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | حدود الصورة الوجهة. |
| entriesCount | int | عدد الإدخالات المطلوب. |
| useImagePalette | boolean | إذا تم التعيين، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة فستُستخدم بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | حدود الصورة الوجهة. |
| entriesCount | int | عدد الإدخالات المطلوب. |
| useImagePalette | boolean | إذا تم التعيين، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency) {#getCloseImagePalette-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-int-boolean-com.aspose.imaging.Color-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette, Color alphaBlendInColor, boolean keepTransparency)
```


يحصل على لوحة ألوان من صورة نقطية (يقوم بعملية تحويل الصورة إلى لوحة ألوان) في حال عدم وجود لوحة ألوان للصورة. إذا كانت اللوحة موجودة فستُستخدم بدلاً من إجراء الحسابات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| destBounds | [Rectangle](../../com.aspose.imaging/rectangle) | حدود الصورة الوجهة. |
| entriesCount | int | عدد الإدخالات المطلوب. |
| useImagePalette | boolean | إذا تم التعيين، سيستخدم لوحة ألوان الصورة الخاصة به إذا كانت متاحة |
| alphaBlendInColor | [Color](../../com.aspose.imaging/color) | اللون الذي يجب استخدامه كلون خلفية لاستبدال ألفا شبه الشفاف. |
| keepTransparency | boolean | إذا تم التعيين، سيأخذ في الاعتبار بتات قناة ألفا لألوان الصورة. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette which starts with the most frequent colors from the `image` and contains `entriesCount` entries.
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


احصل على لوحة ألوان موحدة مكونة من 256 لونًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.imaging.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


احصل على لوحة ألوان 256، مكوّنة من البتات العليا لقيم ألوان الصورة الأصلية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة. |

**Returns:**
[ColorPalette](../../com.aspose.imaging/colorpalette) - The `ColorPalette`.
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.imaging.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


يحدد ما إذا كانت اللوحة المحددة تحتوي على ألوان شفافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |

**Returns:**
منطقية - `true` إذا كانت لوحة الألوان المحددة تحتوي على ألوان شفافة؛ وإلا `false`.
### createGrayscale(int bits) {#createGrayscale-int-}
```
public static IColorPalette createGrayscale(int bits)
```


يحصل على لوحة تدرج الرمادي للعدد المحدد من البتات. القيم المسموح بها للبت هي 1، 2، 4، 8.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bits | int | عدد البتات. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - Grayscale palette.
