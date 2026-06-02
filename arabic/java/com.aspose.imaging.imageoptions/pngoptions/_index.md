---
title: "PngOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "أنشئ صورًا نقطية PNG عالية الجودة من نوع Portable Network Graphics بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا التي تقدم خيارات قابلة للتخصيص لمستويات الضغط وعدد البتات لكل بكسل والعمق وبتات ألفا."
type: docs
weight: 38
url: /ar/java/com.aspose.imaging.imageoptions/pngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class PngOptions extends ImageOptionsBase
```

أنشئ صورًا نقطية عالية الجودة من نوع Portable Network Graphics (PNG) بسهولة باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع تقديم خيارات قابلة للتخصيص لمستويات الضغط وعدد البتات لكل بكسل والعمق وبتات ألفا. عالج حاويات بيانات تعريف XMP بسلاسة، مما يضمن إدارة شاملة لبيانات تعريف الصورة، ويمنحك القدرة على تخصيص صور PNG وفقًا لمواصفاتك الدقيقة بسهولة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PngOptions()](#PngOptions--) | يُنشئ مثيلاً جديدًا من الفئة `PngOptions`. |
| [PngOptions(PngOptions pngOptions)](#PngOptions-com.aspose.imaging.imageoptions.PngOptions-) | يُنشئ مثيلاً جديدًا من الفئة `PngOptions`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_COMPRESSION_LEVEL](#DEFAULT-COMPRESSION-LEVEL) | مستوى الضغط الافتراضي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorType()](#getColorType--) | يحصل على نوع اللون. |
| [setColorType(int value)](#setColorType-int-) | يضبط نوع اللون. |
| [getProgressive()](#getProgressive--) | يحصل على قيمة تشير إلى ما إذا كان [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) تقدميًا. |
| [setProgressive(boolean value)](#setProgressive-boolean-) | يضبط قيمة تشير إلى ما إذا كان [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) تقدميًا. |
| [getFilterType()](#getFilterType--) | يحصل على نوع الفلتر المستخدم أثناء عملية حفظ ملف png. |
| [setFilterType(int value)](#setFilterType-int-) | يضبط نوع الفلتر المستخدم أثناء عملية حفظ ملف png. |
| [getCompressionLevel()](#getCompressionLevel--) | يحصل على مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | يضبط مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getPngCompressionLevel()](#getPngCompressionLevel--) | يحصل على مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [setPngCompressionLevel(int value)](#setPngCompressionLevel-int-) | يضبط مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |
| [getBitDepth()](#getBitDepth--) | يحصل على قيم عمق البت في النطاق 1، 2، 4، 8، 16. |
| [setBitDepth(byte value)](#setBitDepth-byte-) | يضبط قيم عمق البت في النطاق 1، 2، 4، 8، 16. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
يوضح هذا المثال استخدام فئات مختلفة من مساحة الأسماء SaveOptions لأغراض التصدير. يتم تحميل صورة من نوع Gif إلى مثيل من الفئة Image ثم يتم تصديرها إلى عدة صيغ.
``` java
String dir = "c:\\temp\\";

//تحميل صورة موجودة (من نوع Gif) في مثيل من الفئة Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to PNG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.png");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.PngOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن PNG ليس تنسيقًا متعدد الصفحات.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### PngOptions() {#PngOptions--}
```
public PngOptions()
```


يُنشئ مثيلاً جديدًا من الفئة `PngOptions`.

### PngOptions(PngOptions pngOptions) {#PngOptions-com.aspose.imaging.imageoptions.PngOptions-}
```
public PngOptions(PngOptions pngOptions)
```


يُنشئ مثيلاً جديدًا من الفئة `PngOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | خيارات PNG. |

### DEFAULT_COMPRESSION_LEVEL {#DEFAULT-COMPRESSION-LEVEL}
```
public static final int DEFAULT_COMPRESSION_LEVEL
```


مستوى الضغط الافتراضي.

### getColorType() {#getColorType--}
```
public final int getColorType()
```


يحصل على نوع اللون.

القيمة: نوع اللون.

**Returns:**
int - نوع اللون.
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```


يضبط نوع اللون.

القيمة: نوع اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نوع اللون. |


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


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
// يمكنك أيضًا تحميل صورة بأي تنسيق مدعوم من ملف أو تدفق.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالتدرج الأزرق الشفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // استخدم التحميل التقدمي.
    saveOptions.setProgressive(true);

    // اضبط الدقة الأفقية والعمودية إلى 96 بكسل لكل بوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // كل بكسل هو ثلاثية (أحمر، أخضر، أزرق) تليها ألفا.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // اضبط أقصى مستوى للضغط.
    saveOptions.setCompressionLevel(9);

    // هذا هو أفضل ضغط، لكنه أبطأ وقت تنفيذ.
    // يعني الترشيح التكيفي أن عملية الحفظ ستختار الفلتر الأنسب لكل صف بيانات.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // عدد البتات لكل قناة.
    saveOptions.setBitDepth((byte) 8);

    // احفظ إلى ملف.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getProgressive() {#getProgressive--}
```
public final boolean getProgressive()
```


يحصل على قيمة تشير إلى ما إذا كان [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) تقدميًا.

القيمة: `` إذا كان تقدميًا؛ وإلا ``.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) تقدميًا.
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public final void setProgressive(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) تقدميًا.

القيمة: `` إذا كان تقدميًا؛ وإلا ``.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) تقدميًا. |


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


**Example: This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();

// عدد البتات لكل قناة لون
createOptions.setBitDepth((byte) 8);

// كل بكسل هو ثلاثية (أحمر، أخضر، أزرق) تليها مكوّن ألفا.
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

// أقصى مستوى للضغط.
createOptions.setCompressionLevel(9);

// استخدام الفلاتر يسمح بضغط الصور النغمية المستمرة بشكل أكثر فعالية.
createOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Sub);

// استخدم التحميل التدريجي
createOptions.setProgressive(true);

// إنشاء صورة PNG بمعلمات مخصصة.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(createOptions, 100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بتدرج شبه شفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    // احفظ إلى ملف.
    pngImage.save(dir + "output.explicitoptions.png");
} finally {
    pngImage.dispose();
}
```

### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


يحصل على نوع الفلتر المستخدم أثناء عملية حفظ ملف png.

**Returns:**
int - نوع الفلتر المستخدم أثناء عملية حفظ ملف PNG.
### setFilterType(int value) {#setFilterType-int-}
```
public final void setFilterType(int value)
```


يضبط نوع الفلتر المستخدم أثناء عملية حفظ ملف png.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نوع الفلتر المستخدم أثناء عملية حفظ ملف PNG. |


**Example: The following example shows how different filter types affect the size of the output PNG image.**

``` java

// فئة المساعدة
class Utils {
    public String getPngFilterTypeString(int filterType) {
        switch (filterType) {
            case com.aspose.imaging.fileformats.png.PngFilterType.None:
                return "None";

            case com.aspose.imaging.fileformats.png.PngFilterType.Up:
                return "Up";

            case com.aspose.imaging.fileformats.png.PngFilterType.Sub:
                return "Sub";

            case com.aspose.imaging.fileformats.png.PngFilterType.Paeth:
                return "Paeth";

            case com.aspose.imaging.fileformats.png.PngFilterType.Avg:
                return "Avg";

            case com.aspose.imaging.fileformats.png.PngFilterType.Adaptive:
                return "Adaptive";

            default:
                throw new IllegalArgumentException("filterType");
        }
    }
}

// هنا المثال الرئيسي
Utils utils = new Utils();

int[] filterTypes = new int[]
        {
                com.aspose.imaging.fileformats.png.PngFilterType.None,
                com.aspose.imaging.fileformats.png.PngFilterType.Up,
                com.aspose.imaging.fileformats.png.PngFilterType.Sub,
                com.aspose.imaging.fileformats.png.PngFilterType.Paeth,
                com.aspose.imaging.fileformats.png.PngFilterType.Avg,
                com.aspose.imaging.fileformats.png.PngFilterType.Adaptive,
        };

for (int filterType : filterTypes) {
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
    try {
        // تعيين نوع الفلتر
        options.setFilterType(filterType);

        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            image.save(stream, options);
            System.out.printf("The filter type is %s, the output image size is %s bytes.", utils.getPngFilterTypeString(filterType), stream.size());
        } finally {
            stream.close();
        }
    } finally {
        image.dispose();
    }
}

//قد يبدو الإخراج هكذا:
//نوع الفلتر هو None، حجم الصورة الناتجة هو 116845 بايت.
//نوع الفلتر هو Up، حجم الصورة الناتجة هو 86360 بايت.
//نوع الفلتر هو Sub، حجم الصورة الناتجة هو 94907 بايت.
//نوع الفلتر هو Paeth، حجم الصورة الناتجة هو 86403 بايت.
//نوع الفلتر هو Avg، حجم الصورة الناتجة هو 89956 بايت.
//نوع الفلتر هو Adaptive، حجم الصورة الناتجة هو 97248 بايت.
```

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


يحصل على مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


يضبط مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |


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


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
// يمكنك أيضًا تحميل صورة بأي تنسيق مدعوم من ملف أو تدفق.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالتدرج الأزرق الشفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // استخدم التحميل التقدمي.
    saveOptions.setProgressive(true);

    // اضبط الدقة الأفقية والعمودية إلى 96 بكسل لكل بوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // كل بكسل هو ثلاثية (أحمر، أخضر، أزرق) تليها ألفا.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // اضبط أقصى مستوى للضغط.
    saveOptions.setCompressionLevel(9);

    // هذا هو أفضل ضغط، لكنه أبطأ وقت تنفيذ.
    // يعني الترشيح التكيفي أن عملية الحفظ ستختار الفلتر الأنسب لكل صف بيانات.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // عدد البتات لكل قناة.
    saveOptions.setBitDepth((byte) 8);

    // احفظ إلى ملف.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getPngCompressionLevel() {#getPngCompressionLevel--}
```
public final int getPngCompressionLevel()
```


يحصل على مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Returns:**
int - مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).
### setPngCompressionLevel(int value) {#setPngCompressionLevel-int-}
```
public final void setPngCompressionLevel(int value)
```


يضبط مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | مستوى ضغط [PngImage](../../com.aspose.imaging.fileformats.png/pngimage). |

### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


يحصل على قيم عمق البت في النطاق 1، 2، 4، 8، 16.

انتبه إلى الحدود التالية:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Returns:**
byte - قيم عمق البت في النطاق 1، 2، 4، 8، 16.
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public final void setBitDepth(byte value)
```


يضبط قيم عمق البت في النطاق 1، 2، 4، 8، 16.

انتبه إلى الحدود التالية:

[PngColorType.IndexedColor](../../com.aspose.imaging.fileformats.png/pngcolortype\#IndexedColor) supports bit depth of 1, 2, 4, 8.

[PngColorType.Grayscale](../../com.aspose.imaging.fileformats.png/pngcolortype\#Grayscale), [PngColorType.GrayscaleWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#GrayscaleWithAlpha) support bits depth of 8.

[PngColorType.Truecolor](../../com.aspose.imaging.fileformats.png/pngcolortype\#Truecolor), [PngColorType.TruecolorWithAlpha](../../com.aspose.imaging.fileformats.png/pngcolortype\#TruecolorWithAlpha) support bits depth of 8, 16.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | قيم عمق البت في النطاق 1، 2، 4، 8، 16. |


**Example: The following example shows how to save an image to PNG format using various options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
// يمكنك أيضًا تحميل صورة بأي تنسيق مدعوم من ملف أو تدفق.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(pngImage.getWidth(), pngImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getTransparent());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالتدرج الأزرق الشفاف.
    graphics.fillRectangle(gradientBrush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // استخدم التحميل التقدمي.
    saveOptions.setProgressive(true);

    // اضبط الدقة الأفقية والعمودية إلى 96 بكسل لكل بوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    // كل بكسل هو ثلاثية (أحمر، أخضر، أزرق) تليها ألفا.
    saveOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

    // اضبط أقصى مستوى للضغط.
    saveOptions.setCompressionLevel(9);

    // هذا هو أفضل ضغط، لكنه أبطأ وقت تنفيذ.
    // يعني الترشيح التكيفي أن عملية الحفظ ستختار الفلتر الأنسب لكل صف بيانات.
    saveOptions.setFilterType(com.aspose.imaging.fileformats.png.PngFilterType.Adaptive);

    // عدد البتات لكل قناة.
    saveOptions.setBitDepth((byte) 8);

    // احفظ إلى ملف.
    pngImage.save(dir + "output.png", saveOptions);
} finally {
    pngImage.dispose();
}
```

