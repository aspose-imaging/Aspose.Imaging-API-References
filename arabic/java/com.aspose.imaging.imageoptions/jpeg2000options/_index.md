---
title: "Jpeg2000Options"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنشاء ملفات صور JPEG2000 JP2 باستخدام واجهة برمجة التطبيقات الخاصة بنا مستفيدًا من تقنية الموجات المتقدمة لتشفير المحتوى غير الفاقد."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

إنشاء ملفات صور JPEG2000 (JP2) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من تقنية الموجات المتقدمة لتشفير المحتوى غير الفاقد. استفد من الدعم لمختلف المشفرات، بما في ذلك الضغط غير القابل للعكس والضغط غير الفاقد، بالإضافة إلى حاويات بيانات XMP، مما يضمن مرونة وإنشاء صور عالية الجودة وفقًا لاحتياجاتك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000Options`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getComments()](#getComments--) | يحصل أو يضبط علامات تعليقات Jpeg. |
| [setComments(String[] value)](#setComments-java.lang.String---) | يحصل أو يضبط علامات تعليقات Jpeg. |
| [getCodec()](#getCodec--) | يحصل أو يضبط مشفر JPEG2000 |
| [setCodec(int value)](#setCodec-int-) | يحصل أو يضبط مشفر JPEG2000 |
| [getCompressionRatios()](#getCompressionRatios--) | يحصل أو يضبط مصفوفة نسب الضغط. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | يحصل أو يضبط مصفوفة نسب الضغط. |
| [getIrreversible()](#getIrreversible--) | يحصل على قيمة تشير إلى ما إذا كان يستخدم DWT غير القابل للعكس 9-7 (true) أو يستخدم ضغط DWT غير الفاقد 5-3 (الافتراضي). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | يضبط قيمة تشير إلى ما إذا كان يستخدم DWT غير القابل للعكس 9-7 (true) أو يستخدم ضغط DWT غير الفاقد 5-3 (الافتراضي). |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليتين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط إلى نقطية لأن JPEG 2000 ليس تنسيقًا متعدد الصفحات.
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

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000Options`.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000Options`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | خيارات تنسيق ملف Jpeg2000 لنسخ الإعدادات منها. |

### getComments() {#getComments--}
```
public String[] getComments()
```


يحصل أو يضبط علامات تعليقات Jpeg.

**Returns:**
java.lang.String[] - علامات تعليقات Jpeg.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


يحصل أو يضبط علامات تعليقات Jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] | علامات تعليقات Jpeg. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


يحصل أو يضبط مشفر JPEG2000

**Returns:**
int - مشفر JPEG2000
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


يحصل أو يضبط مشفر JPEG2000

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | مشفر JPEG2000 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// أنشئ صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
    saveOptions.setIrreversible(true);

    // JP2 هو تنسيق "الحاوية" لـ JPEG 2000 codestreams.
    // J2K هو بيانات مضغوطة خام، بدون غلاف.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // احفظ إلى ملف
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


يحصل أو يضبط الـ Array لنسبة الضغط. نسب ضغط مختلفة للطبقات المتتالية. المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب. نسب الانخفاض مطلوبة.

**Returns:**
int[] - نسب الضغط.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


يحصل أو يضبط الـ Array لنسبة الضغط. نسب ضغط مختلفة للطبقات المتتالية. المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب. نسب الانخفاض مطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | نسب الضغط. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


يحصل على قيمة تشير إلى ما إذا كان يستخدم DWT غير القابل للعكس 9-7 (true) أو يستخدم ضغط DWT غير الفاقد 5-3 (الافتراضي).

**Returns:**
boolean - قيمة تشير إلى ما إذا كنت تستخدم DWT غير العكسي 9-7 (true) أو تستخدم ضغط DWT 5-3 بدون فقدان
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يستخدم DWT غير القابل للعكس 9-7 (true) أو يستخدم ضغط DWT غير الفاقد 5-3 (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كنت تستخدم DWT غير العكسي 9-7 (true) أو تستخدم ضغط DWT 5-3 بدون فقدان |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// أنشئ صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
    saveOptions.setIrreversible(true);

    // JP2 هو تنسيق "الحاوية" لـ JPEG 2000 codestreams.
    // J2K هو بيانات مضغوطة خام، بدون غلاف.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // احفظ إلى ملف
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

