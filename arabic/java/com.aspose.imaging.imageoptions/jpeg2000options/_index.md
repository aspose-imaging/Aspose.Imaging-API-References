---
title: "Jpeg2000Options"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنشاء ملفات صور JPEG2000 JP2 باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من تقنية الموجات المتقدمة لتشفير المحتوى غير الفاقد."
type: docs
weight: 25
url: /ar/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

إنشاء ملفات صور JPEG2000 (JP2) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من تقنية الموجات المتقدمة لتشفير المحتوى غير الفاقد. استفد من الدعم لمختلف الترميزات، بما في ذلك الضغط غير القابل للعكس والضغط غير الفاقد، وكذلك حاويات بيانات XMP، مما يضمن مرونة وإنشاء صور عالية الجودة وفقًا لاحتياجاتك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | يُنشئ مثيلاً جديدًا من الفئة `Jpeg2000Options`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getComments()](#getComments--) | يحصل أو يعيّن علامات تعليقات Jpeg. |
| [setComments(String[] value)](#setComments-java.lang.String---) | يحصل أو يعيّن علامات تعليقات Jpeg. |
| [getCodec()](#getCodec--) | يحصل أو يعيّن برنامج الترميز JPEG2000. |
| [setCodec(int value)](#setCodec-int-) | يحصل أو يعيّن برنامج الترميز JPEG2000. |
| [getCompressionRatios()](#getCompressionRatios--) | يحصل أو يعيّن مصفوفة نسب الضغط. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | يحصل أو يعيّن مصفوفة نسب الضغط. |
| [getIrreversible()](#getIrreversible--) | يحصل على قيمة تشير إلى ما إذا كان يستخدم تحويل الموجة المتقطعة غير القابل للعكس DWT 9-7 (صحيح) أو يستخدم ضغط DWT 5-3 غير الفاقد (الافتراضي). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | يعيّن قيمة تشير إلى ما إذا كان يستخدم تحويل الموجة المتقطعة غير القابل للعكس DWT 9-7 (صحيح) أو يستخدم ضغط DWT 5-3 غير الفاقد (الافتراضي). |

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


يحصل أو يعيّن علامات تعليقات Jpeg.

**Returns:**
java.lang.String[] - علامات تعليقات Jpeg.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


يحصل أو يعيّن علامات تعليقات Jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String[] | علامات تعليقات Jpeg. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


يحصل أو يعيّن برنامج الترميز JPEG2000.

**Returns:**
int - برنامج الترميز JPEG2000
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


يحصل أو يعيّن برنامج الترميز JPEG2000.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | برنامج الترميز JPEG2000 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
    saveOptions.setIrreversible(true);

    // JP2 هو تنسيق "الحاوية" لتدفقات شفرة JPEG 2000.
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


يحصل أو يعيّن مصفوفة نسب الضغط. نسب ضغط مختلفة للطبقات المتتالية. المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب. يلزم تقليل النسب.

**Returns:**
int[] - نسب الضغط.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


يحصل أو يعيّن مصفوفة نسب الضغط. نسب ضغط مختلفة للطبقات المتتالية. المعدل المحدد لكل مستوى جودة هو عامل الضغط المطلوب. يلزم تقليل النسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int[] | نسب الضغط. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


يحصل على قيمة تشير إلى ما إذا كان يستخدم تحويل الموجة المتقطعة غير القابل للعكس DWT 9-7 (صحيح) أو يستخدم ضغط DWT 5-3 غير الفاقد (الافتراضي).

**Returns:**
boolean - قيمة تشير إلى ما إذا كنت تستخدم DWT 9-7 غير القابل للعكس (صحيح) أو تستخدم ضغط DWT 5-3 غير الفاقد
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


يعيّن قيمة تشير إلى ما إذا كان يستخدم تحويل الموجة المتقطعة غير القابل للعكس DWT 9-7 (صحيح) أو يستخدم ضغط DWT 5-3 غير الفاقد (الافتراضي).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كنت تستخدم DWT 9-7 غير القابل للعكس (صحيح) أو تستخدم ضغط DWT 5-3 غير الفاقد |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// إنشاء صورة PNG بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // املأ الصورة بالكامل باللون الأحمر.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // استخدم تحويل الموجة المتقطعة غير القابل للعكس 9-7
    saveOptions.setIrreversible(true);

    // JP2 هو تنسيق "الحاوية" لتدفقات شفرة JPEG 2000.
    // J2K هو بيانات مضغوطة خام، بدون غلاف.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // احفظ إلى ملف
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

