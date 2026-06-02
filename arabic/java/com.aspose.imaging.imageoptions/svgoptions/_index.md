---
title: "SvgOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "إنشاء ملفات صور SVG (رسومات متجهية قياسية) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع خيارات متعددة لأنواع الألوان ومستويات الضغط."
type: docs
weight: 45
url: /ar/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

إنشاء ملفات صور SVG (رسومات متجهية قياسية) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع خيارات متعددة لأنواع الألوان ومستويات الضغط. خصّص صور SVG الخاصة بك بدقة وسلاسة، لضمان جودة مثالية وتوافق مع احتياجات التصميم الخاصة بك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColorType()](#getColorType--) | يحصل أو يعيّن نوع اللون لصورة SVG. |
| [setColorType(int value)](#setColorType-int-) | يحصل أو يعيّن نوع اللون لصورة SVG. |
| [getTextAsShapes()](#getTextAsShapes--) | يحصل على قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال. |
| [getCallback()](#getCallback--) | يحصل على استراتيجية التخزين للموارد المضمنة في [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مثل الخطوط والراستر المتداخل. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | يضبط استراتيجية التخزين للموارد المضمنة في [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مثل الخطوط والراستر المتداخل. |
| [getCompress()](#getCompress--) | يحصل على قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة. |
| [setCompress(boolean value)](#setCompress-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليين فقط. في الواقع، سيتم تحويل صفحة واحدة فقط لأن SVG ليس تنسيقًا متعدد الصفحات.
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


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgOptions() {#SvgOptions--}
```
public SvgOptions()
```


### getColorType() {#getColorType--}
```
public int getColorType()
```


يحصل أو يعيّن نوع اللون لصورة SVG.

**Returns:**
int - نوع لون صورة SVG.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


يحصل أو يعيّن نوع اللون لصورة SVG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | نوع لون صورة SVG. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


يحصل على قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال.

القيمة: `true` إذا تم تحويل جميع النص إلى أشكال SVG أثناء التحويل؛ وإلا `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال.

القيمة: `true` إذا تم تحويل جميع النص إلى أشكال SVG أثناء التحويل؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // سيتم تحويل النص إلى أشكال.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // لون الخلفية لسطح الرسم.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // حجم الصفحة.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // حدد الهامش الأفقي
    rasterizationOptions.setBorderX(50);

    // حدد الهامش الرأسي
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
}
```

### getCallback() {#getCallback--}
```
public ISvgResourceKeeperCallback getCallback()
```


يحصل على استراتيجية التخزين للموارد المضمنة في [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مثل الخطوط والراستر المتداخل.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


يضبط استراتيجية التخزين للموارد المضمنة في [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مثل الخطوط والراستر المتداخل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | استراتيجية التخزين للموارد المضمنة في [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مثل الخطوط والراستر المتداخل. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


يحصل على قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان يجب ضغط الصورة الناتجة. |


**Example: The following example shows how to convert a svg images to svgz format**

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

