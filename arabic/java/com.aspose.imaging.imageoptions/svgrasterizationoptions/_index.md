---
title: "SvgRasterizationOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات تمثيل الرسوميات لملف SVG."
type: docs
weight: 46
url: /ar/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

خيارات تمثيل الرسوميات لملف SVG.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | يُنشئ مثيلًا جديدًا من الفئة `SvgRasterizationOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getScaleX()](#getScaleX--) | يحصل أو يضبط مقياس x. |
| [setScaleX(float value)](#setScaleX-float-) | يحصل أو يضبط مقياس x. |
| [getScaleY()](#getScaleY--) | يحصل أو يضبط مقياس y. |
| [setScaleY(float value)](#setScaleY-float-) | يحصل أو يضبط مقياس y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | ينسخ هذه الحالة إلى `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


يُنشئ مثيلًا جديدًا من الفئة `SvgRasterizationOptions`.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


يحصل أو يضبط مقياس x.

**Returns:**
float - مقياس x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


يحصل أو يضبط مقياس x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | مقياس x. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // من أجل تحويل SVG إلى نقطية، نحتاج إلى تحديد خيارات التحويل النقطي.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // تعيين اللون الافتراضي لخلفية صورة. القيمة الافتراضية هي الأبيض.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // تعيين حجم الصفحة
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // يتم تطبيق مضاد التعرجات على الخطوط والمنحنيات وحواف المناطق المملوءة.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز بدون التلميح.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // قلل حجم الصورة 10 مرات، أي أن حجم الإخراج سيكون 10٪ من الحجم الأصلي.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // حفظ إلى ملف PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


يحصل أو يضبط مقياس y.

**Returns:**
float - مقياس y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


يحصل أو يضبط مقياس y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | مقياس y. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل الصورة.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // من أجل تحويل SVG إلى نقطية، نحتاج إلى تحديد خيارات التحويل النقطي.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // تعيين اللون الافتراضي لخلفية صورة. القيمة الافتراضية هي الأبيض.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // تعيين حجم الصفحة
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // يتم تطبيق مضاد التعرجات على الخطوط والمنحنيات وحواف المناطق المملوءة.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز بدون التلميح.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // قلل حجم الصورة 10 مرات، أي أن حجم الإخراج سيكون 10٪ من الحجم الأصلي.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // حفظ إلى ملف PNG
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


ينسخ هذه الحالة إلى `vectorRasterizationOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | خيارات تحويل المتجه إلى نقطية. |

