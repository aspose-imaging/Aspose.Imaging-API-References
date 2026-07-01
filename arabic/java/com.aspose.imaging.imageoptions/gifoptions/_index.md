---
title: "GifOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات لإنشاء ملفات صور نقطية بتنسيق GIF (Graphics Interchange Format) للمطورين خيارات شاملة لتوليد صور GIF مع تحكم دقيق."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

توفر واجهة برمجة التطبيقات لإنشاء ملفات صور نقطية بتنسيق Graphics Interchange Format (GIF) للمطورين خيارات شاملة لتوليد صور GIF مع تحكم دقيق. تشمل الميزات ضبط لون الخلفية، لوحة الألوان، الدقة، نوع التداخل، اللون الشفاف، حاوية بيانات التعريف XMP، وضغط الصورة، مما يضمن مرونة وكفاءة في إنشاء ملفات GIF محسّنة وجذابة بصريًا مُصممة لتلبية متطلبات التطبيقات المحددة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifOptions()](#GifOptions--) | يُهيئ مثيلاً جديداً من الفئة `GifOptions`. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | يُهيئ مثيلاً جديداً من الفئة `GifOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقًا. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقًا. |
| [getLoopsCount()](#getLoopsCount--) | يحصل على عدد الحلقات (الافتراضي حلقة واحدة). |
| [setLoopsCount(int value)](#setLoopsCount-int-) | يعيّن عدد الحلقات (الافتراضي حلقة واحدة). |
| [getColorResolution()](#getColorResolution--) | يحصل أو يعيّن دقة ألوان GIF. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | يحصل أو يعيّن دقة ألوان GIF. |
| [isPaletteSorted()](#isPaletteSorted--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | يحصل أو يعيّن فهرس لون خلفية GIF. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | يحصل أو يعيّن فهرس لون خلفية GIF. |
| [hasTrailer()](#hasTrailer--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي. |
| [getInterlaced()](#getInterlaced--) | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | صحيح إذا كان يجب أن تكون الصورة متشابكة. |
| [getMaxDiff()](#getMaxDiff--) | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يعيّن لون الخلفية. |
| [hasTransparentColor()](#hasTransparentColor--) | يحصل على قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | يعيّن قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. |

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


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليين فقط. سيتم عرض هاتين الصفحتين كإطارات متحركة في GIF الناتج.
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


يُهيئ مثيلاً جديداً من الفئة `GifOptions`.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


يُهيئ مثيلاً جديداً من الفئة `GifOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | خيارات GIF. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقًا.

**Returns:**
منطقي - `true` إذا تم تطبيق تصحيح اللوحة؛ وإلا `false`.

يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت ولكن الصورة الناتجة ستحصل على أفضل لوحة ألوان مطابقة والنتيجة تكون بصريًا أفضل.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | boolean | `true` إذا تم تطبيق تصحيح اللوحة؛ وإلا `false`. |

يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات). تستغرق عملية التحليل بعض الوقت ولكن الصورة الناتجة ستحصل على أفضل لوحة ألوان مطابقة والنتيجة تكون بصريًا أفضل. |


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

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر
    // لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // حمّل صورة GIF بطريقة تدريجية.
    // GIF المتشابك لا يعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل يعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل الانتهاء من تحميله.
    saveOptions.setInterlaced(true);

    // احفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // عيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان.
    // القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط عالي.
    saveOptions.setMaxDiff(80);

    // احفظ كملف GIF بفقدان البيانات.
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
//حجم GIF غير الفاقد: 212816 بايت.
//حجم GIF الفاقد: 89726 بايت.
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
| value | int | عدد الحلقات (الافتراضي حلقة واحدة) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


يحصل أو يعيّن دقة ألوان GIF.

**Returns:**
byte - دقة اللون.

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم كامل لوحة الألوان التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل 3، فإن لوحة ألوان الصورة الأصلية كانت تحتوي على 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى لوحة الألوان الأصلية، حتى إذا لم يكن كل لون من اللوحة بالكامل متاحًا على الجهاز المصدر.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


يحصل أو يعيّن دقة ألوان GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte | دقة اللون. |

دقة اللون - عدد البتات لكل لون أساسي متاح في الصورة الأصلية، ناقص 1. تمثل هذه القيمة حجم كامل لوحة الألوان التي تم اختيار الألوان منها في الرسم، وليس عدد الألوان المستخدمة فعليًا في الرسم. على سبيل المثال، إذا كانت القيمة في هذا الحقل 3، فإن لوحة ألوان الصورة الأصلية كانت تحتوي على 4 بتات لكل لون أساسي متاح لإنشاء الصورة. يجب ضبط هذه القيمة للإشارة إلى غنى لوحة الألوان الأصلية، حتى إذا لم يكن كل لون من اللوحة بالكامل متاحًا على الجهاز المصدر. |


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

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر
    // لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // حمّل صورة GIF بطريقة تدريجية.
    // GIF المتشابك لا يعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل يعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل الانتهاء من تحميله.
    saveOptions.setInterlaced(true);

    // احفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // عيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان.
    // القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط عالي.
    saveOptions.setMaxDiff(80);

    // احفظ كملف GIF بفقدان البيانات.
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
//حجم GIF غير الفاقد: 212816 بايت.
//حجم GIF الفاقد: 89726 بايت.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة.

**Returns:**
boolean - `true` إذا تم ترتيب مدخلات لوحة الألوان؛ وإلا `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت إدخالات لوحة الألوان مرتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا تم ترتيب مدخلات لوحة الألوان؛ وإلا `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: نسبة الأبعاد = (نسبة أبعاد البكسل + 15) / 64. تُعرف نسبة أبعاد البكسل بأنها ناتج عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Returns:**
byte - نسبة أبعاد بكسل GIF.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


يحصل أو يعيّن نسبة أبعاد بكسل GIF.

نسبة أبعاد البكسل - العامل المستخدم لحساب تقريب لنسبة أبعاد البكسل في الصورة الأصلية. إذا لم تكن قيمة الحقل 0، يتم حساب هذا التقريب للنسبة بناءً على الصيغة: نسبة الأبعاد = (نسبة أبعاد البكسل + 15) / 64. تُعرف نسبة أبعاد البكسل بأنها ناتج عرض البكسل على ارتفاعه. يتيح نطاق القيم في هذا الحقل تحديد أوسع بكسل بنسبة 4:1 إلى أطول بكسل بنسبة 1:4 بزيادات قدرها 1/64. القيم: 0 - لا توجد معلومات عن نسبة الأبعاد. 1..255 - القيمة المستخدمة في الحساب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte | نسبة أبعاد بكسل GIF. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


يحصل أو يعيّن فهرس لون خلفية GIF.

**Returns:**
byte - فهرس لون الخلفية في GIF.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


يحصل أو يعيّن فهرس لون خلفية GIF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte | فهرس لون الخلفية في GIF. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي.

**Returns:**
boolean - `true` إذا كان GIF يحتوي على مقبض النهاية؛ وإلا `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا كان GIF يحتوي على مقبض النهاية؛ وإلا `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


صحيح إذا كان يجب أن تكون الصورة متشابكة.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


صحيح إذا كان يجب أن تكون الصورة متشابكة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |


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

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر
    // لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // حمّل صورة GIF بطريقة تدريجية.
    // GIF المتشابك لا يعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل يعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل الانتهاء من تحميله.
    saveOptions.setInterlaced(true);

    // احفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // عيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان.
    // القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط عالي.
    saveOptions.setMaxDiff(80);

    // احفظ كملف GIF بفقدان البيانات.
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
//حجم GIF غير الفاقد: 212816 بايت.
//حجم GIF الفاقد: 89726 بايت.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان البيانات. القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط عالي. يعمل بشكل أفضل عندما يتم إدخال خسارة قليلة فقط، وبسبب قيود خوارزمية الضغط لا تعطي المستويات العالية من الخسارة الكثير من الفائدة. نطاق القيم المسموح به هو [0, 1000].

**Returns:**
int - نطاق القيم المسموح بها.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان البيانات. القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط عالي. يعمل بشكل أفضل عندما يتم إدخال خسارة قليلة فقط، وبسبب قيود خوارزمية الضغط لا تعطي المستويات العالية من الخسارة الكثير من الفائدة. نطاق القيم المسموح به هو [0, 1000].

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | نطاق القيم المسموح بها. |


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

    // يعني تصحيح اللوحة أنه كلما تم تصدير الصورة إلى GIF سيتم تحليل ألوان الصورة المصدر
    // لبناء أفضل لوحة ألوان مطابقة (في حالة عدم وجود لوحة ألوان للصورة أو عدم تحديدها في الخيارات)
    saveOptions.setDoPaletteCorrection(true);

    // حمّل صورة GIF بطريقة تدريجية.
    // GIF المتشابك لا يعرض خطوط المسح بشكل خطي من الأعلى إلى الأسفل، بل يعيد ترتيبها
    // لذلك يصبح محتوى GIF واضحًا حتى قبل الانتهاء من تحميله.
    saveOptions.setInterlaced(true);

    // احفظ كـ GIF غير مضغوط.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // عيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان.
    // القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 هو ضغط خفيف جدًا، 200 هو ضغط عالي.
    saveOptions.setMaxDiff(80);

    // احفظ كملف GIF بفقدان البيانات.
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
//حجم GIF غير الفاقد: 212816 بايت.
//حجم GIF الفاقد: 89726 بايت.
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


يحصل على قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. إذا كانت القيمة المرجعة `null`، يتم تجاوز هذه الخاصية بسياق الصورة المصدر.

**Returns:**
java.lang.Boolean - قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. إذا كانت القيمة المرجعة `null`، يتم تجاوز هذه الخاصية بواسطة سياق صورة المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.Boolean | قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. |

