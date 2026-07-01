---
title: "SvgImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعديل ملفات رسومات المتجهات القياسية SVG باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من قوة تنسيق النص القائم على XML للتخصيص السلس والقابلية للتوسع."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

تعديل ملفات رسومات المتجهات القياسية (SVG) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مستفيدًا من قوة تنسيق النص القائم على XML للتخصيص السلس والقابلية للتوسع. يمكنكم بسهولة تحميل صور SVG، تحويل العناصر المتجهة إلى نقطية، وتحويلها إلى صيغ أخرى، مع التحكم في مستويات الضغط لتحسين حجم الملف والجودة لمشاريعكم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | ينشئ كائنًا جديدًا من الفئة [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)، باستخدام المسار المحدد لتحديد موقع الصورة وتحميلها. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | ينشئ نسخة جديدة من الفئة [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)، مع تحميل الصورة من الدفق المقدم. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | ينشئ كائنًا جديدًا من [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) بالعرض والارتفاع المحددين. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | ينشئ نسخة جديدة من الفئة [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مع خيارات SVG المحددة، وعرض الصورة، ومعلمات الارتفاع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isCached()](#isCached--) | يسترجع قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى عمليات قراءة بيانات إضافية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يسترجع عدد البتات لكل بكسل في الصورة. |
| [getFileFormat()](#getFileFormat--) | يسترجع تنسيق ملف الصورة، موفرًا بيانات تعريفية أساسية للمعالجة وفحوصات التوافق. |
| [cacheData()](#cacheData--) | قم بتخزين البيانات مؤقتًا وتأكد من عدم تحميل بيانات إضافية من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | قم بتغيير حجم الصورة لتناسب الأبعاد المحددة مع الحفاظ على نسبة العرض إلى الارتفاع. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص المستطيل المحدد. |
| [rotate(float angle)](#rotate-float-) | دوّر الصورة حول المركز. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يطبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص أنظمة الألوان لأغراض جمالية أو وظيفية. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// تحميل صورة SVG من تدفق ملف.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // من أجل تحويل SVG إلى نقطية نحتاج إلى تحديد خيارات التحويل إلى نقطية.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
المثال التالي يوضح كيفية تحويل الصور المضغوطة (*.emz,*.wmz, *.svgz) إلى تنسيق نقطي.
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
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

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


ينشئ كائنًا جديدًا من فئة [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)، باستخدام المسار المحدد لتحديد موقع الصورة وتحميلها. يسهّل هذا المُنشئ إنشاء مثيلات صورة SVG من ملفات خارجية، مما يتيح دمجًا سلسًا في أنظمة البرمجيات وسير العمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار | java.lang.String | المسار لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


ينشئ مثيلًا جديدًا من فئة [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage)، محملاً الصورة من التدفق المقدم. يتيح هذا المُنشئ التحميل المباشر لصور SVG من التدفقات، مما يعزز المرونة والكفاءة في معالجة موارد الصور داخل تطبيقات البرمجيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق لتحميل الصورة منه وتهيئة بيانات البكسل واللوحة اللونية. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


ينشئ كائنًا جديدًا من [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) بالعرض والارتفاع المحددين. يتيح هذا المُنشئ للمطورين إنشاء صور SVG بأبعاد مسبقة التعريف، مما يسهل التحكم الدقيق في حجم الصورة أثناء التهيئة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


ينشئ مثيلًا جديدًا من فئة [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) مع خيارات SVG المحددة، وعرض الصورة، ومعلمات الارتفاع. يتيح هذا المُنشئ للمطورين تهيئة صور SVG بخيارات وأبعاد مخصصة، مما يوفر مرونة في إدارة محتوى SVG وتخطيطه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | خيارات SVG. |
| width | int | عرض الصورة. |
| height | int | ارتفاع الصورة. |

### isCached() {#isCached--}
```
public boolean isCached()
```


يسترجع قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى عمليات قراءة بيانات إضافية. توفر هذه الخاصية نظرة على حالة التخزين المؤقت الحالية، مما يحسن استرجاع البيانات وسير عمليات المعالجة لأداء وكفاءة محسّنة.

**Returns:**
منطقي - `true` إذا كانت بيانات الكائن مخزنة مؤقتًا؛ وإلا `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يسترجع عدد البتات لكل بكسل في الصورة. من المهم ملاحظة أن هذا المعامل غير قابل للتطبيق على الصور المتجهية، لأنها لا تُقاس بالبكسل. توفر هذه الخاصية معلومات حيوية حول عمق ألوان الصورة، مما يساعد في مهام المعالجة والتعديل.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


يسترجع تنسيق ملف الصورة، موفرًا بيانات تعريفية أساسية للمعالجة وفحوصات التوافق. تُعد هذه الخاصية أساسية في تحديد استراتيجيات الترميز وفك الترميز المناسبة للتعامل مع بيانات الصورة بفعالية عبر أنظمة وتطبيقات مختلفة.

**Returns:**
long - تنسيق الملف
### cacheData() {#cacheData--}
```
public void cacheData()
```


قم بتخزين البيانات مؤقتًا وتأكد من عدم تحميل المزيد من البيانات من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). تُحسّن هذه العملية الأداء عن طريق القضاء على عمليات استرجاع البيانات المتكررة، وهو مفيد بشكل خاص في السيناريوهات التي تتطلب وصولًا متكررًا إلى بيانات الصورة.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


غيّر حجم الصورة لتتناسب مع الأبعاد المحددة مع الحفاظ على نسبة العرض إلى الارتفاع. توفر هذه الطريقة وسيلة مريحة لضبط حجم الصورة دون تشويه نسبها، مما يضمن عرضًا أو تخزينًا مثاليًا وفقًا للأبعاد المطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


يقص المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


يطبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص أنظمة الألوان لأغراض جمالية أو وظيفية. توفر هذه الطريقة مرونة في إدارة لوحات الألوان لتلبية متطلبات التصميم أو التطبيق المختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

