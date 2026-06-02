---
title: "GifOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات لتنسيق تبادل الرسومات GIF لإنشاء ملفات صور نقطية خيارات شاملة للمطورين لإنشاء صور GIF مع تحكم دقيق."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

توفر واجهة برمجة التطبيقات لتنسيق تبادل الرسومات (GIF) لإنشاء ملفات صور نقطية خيارات شاملة للمطورين لإنشاء صور GIF مع تحكم دقيق. تشمل الميزات ضبط لون الخلفية، لوحة الألوان، الدقة، نوع التداخل، اللون الشفاف، حاوية بيانات التعريف XMP، وضغط الصورة، مما يضمن هذه الواجهة مرونة وكفاءة في إنشاء ملفات GIF محسّنة وجذابة بصرياً مُصممة لتلبية متطلبات التطبيقات المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifOptions()](#GifOptions--) | ينشئ مثيلاً جديداً للفئة `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | ينشئ مثيلاً جديداً للفئة `GifOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقاً. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقاً. |
| [getLoopsCount()](#getLoopsCount--) | يحصل على عدد الحلقات (الافتراضي حلقة واحدة). |
| [setLoopsCount(int value)](#setLoopsCount-int-) | يعيّن عدد الحلقات (الافتراضي حلقة واحدة). |
| [getColorResolution()](#getColorResolution--) | يحصل أو يعيّن دقة ألوان GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | يحصل أو يعيّن دقة ألوان GIF. |
| [isPaletteSorted()](#isPaletteSorted--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت مدخلات لوحة الألوان مرتبة. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت مدخلات لوحة الألوان مرتبة. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | يحصل أو يعيّن فهرس لون خلفية GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | يحصل أو يعيّن فهرس لون خلفية GIF. |
| [hasTrailer()](#hasTrailer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة. |
| [getInterlaced()](#getInterlaced--) | صحيح إذا كان يجب أن تكون الصورة متداخلة. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | صحيح إذا كان يجب أن تكون الصورة متداخلة. |
| [getMaxDiff()](#getMaxDiff--) | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يعيّن لون الخلفية. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | يضبط قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. |

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


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليتين فقط. سيتم عرض هاتين الصفحتين كإطارات متحركة في GIF الناتج.
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

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


ينشئ مثيلاً جديداً للفئة `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


ينشئ مثيلاً جديداً للفئة `GifOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | خيارات GIF. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقاً.

**Returns:**
منطقي - `true` إذا تم تطبيق تصحيح اللوحة؛ وإلا `false`.

يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية من أجل بناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت ولكن الصورة الناتجة ستحصل على أفضل لوحة ألوان مطابقة وستكون النتيجة بصريًا أفضل.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقاً.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | `true` إذا تم تطبيق تصحيح اللوحة؛ وإلا `false`. |

يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية من أجل بناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت ولكن الصورة الناتجة ستحصل على أفضل لوحة ألوان مطابقة وستكون النتيجة بصريًا أفضل. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // عدد البتات المطلوبة لتخزين لون، ناقص 1.
    saveOptions.setColorResolution((byte) 7);

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية
    // من أجل بناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // تحميل صورة GIF بطريقة تدريجية.
    // صورة GIF المتشابكة لا تعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل تعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل اكتمال تحميله.
    saveOptions.setInterlaced(true);

    // حفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // حدد الحد الأقصى لاختلاف البكسل المسموح به. إذا كان أكبر من الصفر، سيتم استخدام ضغط بفقدان.
    // القيمة الموصى بها لضغط بفقدان مثالي هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط ثقيل.
    saveOptions.setMaxDiff(80);

    // حفظ كـ GIF بفقدان.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//قد يبدو الإخراج هكذا:
//حجم GIF غير المضغوط: 212816 بايت.
//حجم GIF بفقدان: 89726 بايت.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


يحصل على عدد الحلقات (الافتراضي حلقة واحدة).

القيمة: عدد الحلقات.

**Returns:**
int - عدد الحلقات (الافتراضي حلقة واحدة)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


يعيّن عدد الحلقات (الافتراضي حلقة واحدة).

القيمة: عدد الحلقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | عدد الحلقات (الافتراضي حلقة واحدة) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


يحصل أو يعيّن دقة ألوان GIF.

**Returns:**
byte - دقة اللون.

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل 3، فإن لوحة الصورة الأصلية كان لديها 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للدلالة على غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


يحصل أو يعيّن دقة ألوان GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | byte | دقة اللون. |

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم اللوحة الكاملة التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل 3، فإن لوحة الصورة الأصلية كان لديها 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للدلالة على غنى اللوحة الأصلية، حتى إذا لم يكن كل لون من اللوحة الكاملة متاحًا على الجهاز المصدر. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // عدد البتات المطلوبة لتخزين لون، ناقص 1.
    saveOptions.setColorResolution((byte) 7);

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية
    // من أجل بناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // تحميل صورة GIF بطريقة تدريجية.
    // صورة GIF المتشابكة لا تعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل تعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل اكتمال تحميله.
    saveOptions.setInterlaced(true);

    // حفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // حدد الحد الأقصى لاختلاف البكسل المسموح به. إذا كان أكبر من الصفر، سيتم استخدام ضغط بفقدان.
    // القيمة الموصى بها لضغط بفقدان مثالي هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط ثقيل.
    saveOptions.setMaxDiff(80);

    // حفظ كـ GIF بفقدان.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//قد يبدو الإخراج هكذا:
//حجم GIF غير المضغوط: 212816 بايت.
//حجم GIF بفقدان: 89726 بايت.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت مدخلات لوحة الألوان مرتبة.

**Returns:**
منطقي - `true` إذا تم فرز مدخلات اللوحة؛ وإلا `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت مدخلات لوحة الألوان مرتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا تم فرز مدخلات اللوحة؛ وإلا `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب لنسبة الأبعاد بناءً على الصيغة: نسبة الأبعاد = (نسبة أبعاد البكسل + 15) / 64. تُعرّف نسبة أبعاد البكسل بأنها ناتج عرض البكسل على ارتفاعه. تسمح نطاق القيم في هذا الحقل بتحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Returns:**
بايت - نسبة أبعاد بكسل GIF.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب لنسبة الأبعاد بناءً على الصيغة: نسبة الأبعاد = (نسبة أبعاد البكسل + 15) / 64. تُعرّف نسبة أبعاد البكسل بأنها ناتج عرض البكسل على ارتفاعه. تسمح نطاق القيم في هذا الحقل بتحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | نسبة أبعاد بكسل GIF. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


يحصل أو يعيّن فهرس لون خلفية GIF.

**Returns:**
بايت - فهرس لون الخلفية في GIF.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


يحصل أو يعيّن فهرس لون خلفية GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | فهرس لون الخلفية في GIF. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة.

**Returns:**
منطقي - `true` إذا كان GIF يحتوي على ذيل؛ وإلا `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا كان GIF يحتوي على ذيل؛ وإلا `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


صحيح إذا كان يجب أن تكون الصورة متداخلة.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


صحيح إذا كان يجب أن تكون الصورة متداخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // عدد البتات المطلوبة لتخزين لون، ناقص 1.
    saveOptions.setColorResolution((byte) 7);

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية
    // من أجل بناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // تحميل صورة GIF بطريقة تدريجية.
    // صورة GIF المتشابكة لا تعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل تعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل اكتمال تحميله.
    saveOptions.setInterlaced(true);

    // حفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // حدد الحد الأقصى لاختلاف البكسل المسموح به. إذا كان أكبر من الصفر، سيتم استخدام ضغط بفقدان.
    // القيمة الموصى بها لضغط بفقدان مثالي هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط ثقيل.
    saveOptions.setMaxDiff(80);

    // حفظ كـ GIF بفقدان.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//قد يبدو الإخراج هكذا:
//حجم GIF غير المضغوط: 212816 بايت.
//حجم GIF بفقدان: 89726 بايت.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


يحصل أو يعيّن الحد الأقصى المسموح لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان. القيمة الموصى بها لضغط فقدان مثالي هي 80. 30 يعني ضغط خفيف جدًا، 200 يعني ضغط ثقيل. يعمل بشكل أفضل عندما يتم إدخال فقدان قليل فقط، ونظرًا لحدود خوارزمية الضغط فإن مستويات فقدان عالية جدًا لن تعطي قدرًا كبيرًا من الفائدة. نطاق القيم المسموح به هو [0, 1000].

**Returns:**
int - نطاق القيم المسموح بها.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


يحصل أو يعيّن الحد الأقصى المسموح لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان. القيمة الموصى بها لضغط فقدان مثالي هي 80. 30 يعني ضغط خفيف جدًا، 200 يعني ضغط ثقيل. يعمل بشكل أفضل عندما يتم إدخال فقدان قليل فقط، ونظرًا لحدود خوارزمية الضغط فإن مستويات فقدان عالية جدًا لن تعطي قدرًا كبيرًا من الفائدة. نطاق القيم المسموح به هو [0, 1000].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نطاق القيم المسموح بها. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // عدد البتات المطلوبة لتخزين لون، ناقص 1.
    saveOptions.setColorResolution((byte) 7);

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة الأصلية
    // من أجل بناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // تحميل صورة GIF بطريقة تدريجية.
    // صورة GIF المتشابكة لا تعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل تعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل اكتمال تحميله.
    saveOptions.setInterlaced(true);

    // حفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // حدد الحد الأقصى لاختلاف البكسل المسموح به. إذا كان أكبر من الصفر، سيتم استخدام ضغط بفقدان.
    // القيمة الموصى بها لضغط بفقدان مثالي هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط ثقيل.
    saveOptions.setMaxDiff(80);

    // حفظ كـ GIF بفقدان.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//قد يبدو الإخراج هكذا:
//حجم GIF غير المضغوط: 212816 بايت.
//حجم GIF بفقدان: 89726 بايت.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


يحصل على لون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


يعيّن لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


يحصل على قيمة تشير إلى ما إذا كانت صورة GIF لديها لون شفاف. إذا كانت القيمة المرجعة `null`، يتم تجاوز هذه الخاصية بسياق صورة المصدر.

**Returns:**
java.lang.Boolean - قيمة تشير إلى ما إذا كانت صورة GIF لديها لون شفاف.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


يعيّن قيمة تشير إلى ما إذا كانت صورة GIF لديها لون شفاف. إذا كانت القيمة المرجعة `null`، يتم تجاوز هذه الخاصية بسياق صورة المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.Boolean | قيمة تشير إلى ما إذا كانت صورة GIF لديها لون شفاف. |

