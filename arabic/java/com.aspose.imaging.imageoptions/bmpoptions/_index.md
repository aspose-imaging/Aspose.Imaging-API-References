---
title: "BmpOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات (API) لإنشاء خيارات تنسيق الصورة النقطية BMP و DIB مجموعة أدوات متعددة الاستخدامات للمطورين لإنشاء صور Bitmap مخصصة BMP و Device Independent Bitmap DIB."
type: docs
weight: 12
url: /ar/java/com.aspose.imaging.imageoptions/bmpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class BmpOptions extends ImageOptionsBase
```

توفر واجهة برمجة التطبيقات (API) لإنشاء خيارات تنسيق الصورة النقطية BMP و DIB مجموعة أدوات متعددة الاستخدامات للمطورين لإنشاء صور Bitmap (BMP) و Device Independent Bitmap (DIB) مخصصة. باستخدام هذه الواجهة، يمكنك تحديد خصائص الصورة بدقة مثل عدد البتات لكل بكسل، مستوى الضغط ونوع الضغط، مما يتيح تعديل الناتج ليتوافق مع المتطلبات المحددة. تمكّن هذه الواجهة الغنية بالميزات المطورين من إنشاء صور نقطية عالية الجودة ومخصصة بسهولة ومرونة لتطبيقات متنوعة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BmpOptions()](#BmpOptions--) | يُنشئ مثيلاً جديداً من الفئة `BmpOptions`. |
| [BmpOptions(BmpOptions bmpOptions)](#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-) | يُنشئ مثيلاً جديداً من الفئة `BmpOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل أو يضبط عدد البتات لكل بكسل في الصورة. |
| [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | يحصل أو يضبط عدد البتات لكل بكسل في الصورة. |
| [getCompression()](#getCompression--) | يحصل على نوع الضغط. |
| [setCompression(long value)](#setCompression-long-) | يضبط نوع الضغط. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
يوضح هذا المثال استخدام فئات مختلفة من مساحة الأسماء SaveOptions لأغراض التصدير. يتم تحميل صورة من نوع Gif إلى مثيل من الفئة Image ثم تُصدَّر إلى عدة صيغ.
``` java
String dir = "c:\\temp\\";

//حمّل صورة موجودة (من نوع Gif) في مثيل من الفئة Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to BMP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.bmp");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.BmpOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن BMP ليس تنسيقًا متعدد الصفحات.
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

### BmpOptions() {#BmpOptions--}
```
public BmpOptions()
```


يُنشئ مثيلاً جديداً من الفئة `BmpOptions`.

### BmpOptions(BmpOptions bmpOptions) {#BmpOptions-com.aspose.imaging.imageoptions.BmpOptions-}
```
public BmpOptions(BmpOptions bmpOptions)
```


يُنشئ مثيلاً جديداً من الفئة `BmpOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bmpOptions | [BmpOptions](../../com.aspose.imaging.imageoptions/bmpoptions) | خيارات BMP. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل أو يضبط عدد البتات لكل بكسل في الصورة.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public void setBitsPerPixel(int value)
```


يحصل أو يضبط عدد البتات لكل بكسل في الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عدد بتات الصورة لكل بكسل. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // إنشاء BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
    saveOptions.setBitsPerPixel(8);

    // تعيين أقرب لوحة ألوان 8‑بت تغطي الحد الأقصى لعدد بكسلات الصورة، بحيث تكون الصورة ذات لوحة ألوان
    // يكاد يكون غير قابل للتمييز بصريًا عن نسخة غير ملوّنة.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // احفظ دون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // اضبط الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


يحصل على نوع الضغط. النوع الافتراضي للضغط هو [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields)، الذي يسمح بحفظ [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) مع الشفافية.

القيمة: نوع الضغط.

**Returns:**
long - نوع الضغط.

**Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.**

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```

### setCompression(long value) {#setCompression-long-}
```
public void setCompression(long value)
```


يضبط نوع الضغط. النوع الافتراضي للضغط هو [BitmapCompression.Bitfields](../../com.aspose.imaging.fileformats.bmp/bitmapcompression\#Bitfields)، الذي يسمح بحفظ [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) مع الشفافية.

القيمة: نوع الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | نوع الضغط. |


**Example: The following example loads a BMP image and saves it back to BMP using various save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // إنشاء BmpOptions
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // استخدم 8 بت لكل بكسل لتقليل حجم الصورة الناتجة.
    saveOptions.setBitsPerPixel(8);

    // تعيين أقرب لوحة ألوان 8‑بت تغطي الحد الأقصى لعدد بكسلات الصورة، بحيث تكون الصورة ذات لوحة ألوان
    // يكاد يكون غير قابل للتمييز بصريًا عن نسخة غير ملوّنة.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(rasterImage, 256));

    // احفظ دون ضغط.
    // يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
    saveOptions.setCompression(com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb);

    // اضبط الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));

    image.save(dir + "sample.bmpoptions.bmp", saveOptions);
} finally {
    image.dispose();
}
```


**Example: Compress BMP image using DXT1 compression algorithm.**

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


**Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.**

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// تحميل صورة PNG من ملف.
try (Image pngImage = Image.load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا.
    // إذا كنت تريد تحديد هذا الوضع صراحةً، يجب تعيين خاصية Compression في BmpOptions إلى BitmapCompression.Bitfields.
    // طريقة ضغط BitmapCompression.Bitfields هي طريقة الضغط الافتراضية في BmpOptions.
    // لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية إما بإحدى الطرق التالية.
    // مع خيارات افتراضية ضمنية:
    pngImage.save(outputPathPng);
    // مع خيارات افتراضية صريحة:
    pngImage.save(outputPathBmp, new BmpOptions());
    // تحديد طريقة ضغط BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


**Example: The example shows how to export a BmpImage with the Rgb compression type.**

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// تحميل صورة PNG من ملف.
try (Image pngImage = Image.load(sourcePath))
{
    // يتم حفظ صورة BMP بدعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة ضغط BitmapCompression.Bitfields.
    // لحفظ صورة BMP باستخدام طريقة ضغط Rgb، يجب تحديد BmpOptions مع خاصية Compression مضبوطة على BitmapCompression.Rgb.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

