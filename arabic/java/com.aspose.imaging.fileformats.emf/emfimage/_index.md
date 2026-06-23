---
title: "EmfImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "واجهة برمجة التطبيقات لدعم تنسيق Enhanced Metafile Format (EMF) للصور المتجهة هي أداة شاملة لمعالجة الصور الرسومية بطريقة مستقلة عن الجهاز مع الحفاظ على خصائصها الأصلية."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

واجهة برمجة التطبيقات لدعم تنسيق Enhanced Metafile Format (EMF) للصور المتجهة هي أداة شاملة لمعالجة الصور الرسومية بطريقة مستقلة عن الجهاز مع الحفاظ على خصائصها الأصلية. تم تطويرها للحفاظ على النسب والأبعاد والألوان وغيرها من سمات الرسوم، وتضم دعم تنسيق EMF Plus وميزات لقص المناطق، وتغيير حجم اللوحة والصور، وتدويرها، وعكسها، وتعيين لوحات ألوان الصور، وتصدير واستيراد إلى سياق جهاز APS، وضغط وتحويل EMF إلى صيغ أخرى، مما يضمن معالجة متعددة الاستخدامات وتكامل سلس لصور EMF عبر التطبيقات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [EmfImage()](#EmfImage--) | ابدأ العمل مع صور EMF بتهيئة نسخة جديدة من الفئة [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) class. |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | أنشئ نسخة جديدة من الفئة [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) بتحديد معلمات العرض والارتفاع. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getHeader()](#getHeader--) | استرجع سجل رأس ملف EMF metafile باستخدام هذه الخاصية. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | عدّل سجل رأس ملف EMF metafile باستخدام هذه الخاصية. |
| [isCached()](#isCached--) | الوصول إلى قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. |
| [getRecords()](#getRecords--) | استرجع أو عدّل السجلات المرتبطة بالكائن. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | عدّل السجلات المرتبطة بالكائن. |
| [getFileFormat()](#getFileFormat--) | الوصول إلى قيمة تنسيق الملف المرتبطة بالكائن. |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجع عدد البت لكل بكسل الخاص بالصور النقطية، حيث لا ينطبق هذا المعامل على الصور المتجهة. |
| [getWidthF()](#getWidthF--) | الوصول إلى عرض الصورة، مما يوفر معلومات أساسية للتصيير والمعالجة الدقيقة. |
| [getHeightF()](#getHeightF--) | استرجع ارتفاع الصورة، مما يسهل التصيير الدقيق وتعديلات التخطيط. |
| [cacheData()](#cacheData--) | قم بتخزين البيانات مؤقتًا بفعالية ومنع التحميل المتكرر من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) باستخدام هذه الطريقة. |
| [getUsedFonts()](#getUsedFonts--) | استرجع قائمة الخطوط المستخدمة داخل ملف الميتا باستخدام هذه الطريقة. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | غيّر حجم اللوحة بسهولة باستخدام هذه الدالة. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على خيارات الصورة الأصلية. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

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

    // تعيين الهامش الأفقي
    rasterizationOptions.setBorderX(50);

    // تعيين الهامش العمودي
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


ابدأ العمل مع صور EMF عن طريق تهيئة نسخة جديدة من الفئة [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). مثالي لإدراج صور EMF بسرعة في مشاريعك بسهولة وكفاءة.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


أنشئ نسخة جديدة من الفئة [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) عن طريق تحديد معلمات العرض والارتفاع. يبسط هذا المُنشئ عملية تهيئة صور EMF بأبعاد محددة، مما يعزز كفاءة سير عمل التطوير الخاص بك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | العرض. |
| height | int | الارتفاع. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


استرجع سجل رأس ملف الميتافايل EMF باستخدام هذه الخاصية. مثالي لإدارة بيانات الميتافايل بكفاءة داخل تطبيقك. حسّن سير عملك من خلال وصول مبسط إلى معلومات رأس الميتافايل.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


عدّل سجل رأس ملف الميتافايل EMF باستخدام هذه الخاصية. مثالي لإدارة بيانات الميتافايل بكفاءة داخل تطبيقك. حسّن سير عملك من خلال وصول مبسط إلى معلومات رأس الميتافايل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


الوصول إلى قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. عزّز الكفاءة من خلال تحديد سريع إذا كانت البيانات المخزنة متاحة للوصول الفوري. حسّن سير عملك عبر عمليات استرجاع بيانات مبسطة.

**Returns:**
منطقي - `true` إذا كانت بيانات الكائن مخزنة مؤقتًا؛ وإلا `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


استرجع أو عدّل السجلات المرتبطة بالكائن. وصول وإدارة فعّالة لمجموعة السجلات لتعزيز معالجة البيانات وتعديلها. حسّن سير عملك من خلال التفاعل السلس مع سجلات الكائن.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


عدّل السجلات المرتبطة بالكائن. وصول وإدارة فعّالة لمجموعة السجلات لتعزيز معالجة البيانات وتعديلها. حسّن سير عملك من خلال التفاعل السلس مع سجلات الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | السجلات. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


الوصول إلى قيمة تنسيق الملف المرتبط بالكائن. حدد بسهولة تنسيق الملف المرتبط بالكائن لتسهيل المعالجة وفحوصات التوافق. بسط سير عملك من خلال استرجاع معلومات تنسيق الملف بسهولة.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجع عدد البتات لكل بكسل الخاص بالصور النقطية، حيث لا ينطبق هذا المعامل على الصور المتجهية. حدد بسرعة عمق البكسل للصور النقطية للتحليل الدقيق والتعديل، مما يضمن معالجة صحيحة لبيانات الصورة.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


الوصول إلى عرض الصورة، مما يوفر معلومات أساسية للتصيير والمعالجة الدقيقة. استرجع عرض الصورة بسرعة لضمان التوافق والتخطيط السليم ضمن تطبيقات ومنصات مختلفة.

**Returns:**
float - عرض الصورة بالبكسل.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


استرجع ارتفاع الصورة، مما يسهل التصيير الدقيق وتعديلات التخطيط. الوصول إلى خاصية الارتفاع يضمن التوافق والتكامل السلس عبر منصات وتطبيقات مختلفة.

**Returns:**
float - ارتفاع الصورة بالبكسل.
### cacheData() {#cacheData--}
```
public void cacheData()
```


قم بتخزين البيانات مؤقتًا بكفاءة ومنع التحميل المتكرر من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) باستخدام هذه الطريقة. عزّز الأداء وسهّل الوصول إلى البيانات في تطبيقك، مع تحسين استغلال الموارد لتحسين الاستجابة.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // تخزين البيانات مؤقتًا لتحميل جميع السجلات.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // المفتاح هو نوع السجل، والقيمة هي عدد السجلات من ذلك النوع في صورة WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // جمع الإحصائيات
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // طباعة الإحصائيات
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // محاذاة الإخراج باستخدام المسافات
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد السجلات: 1188
//نوع السجل                              العدد
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


استرجع قائمة الخطوط المستخدمة داخل ملف الميتافايل باستخدام هذه الطريقة. احصل على رؤى حول استخدام الخطوط، مما يسهل الإدارة الفعّالة وتحسين موارد الخطوط لتعزيز التصيير ودقة العرض.

**Returns:**
java.lang.String[] - قائمة الخطوط
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


غيّر حجم اللوحة بسهولة باستخدام هذه الدالة. مثالية لضبط الأبعاد الكلية للصورة دون تعديل محتواها. حسّن العرض وحضر الصور لأحجام عرض مختلفة بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الجديد. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على خيارات الصورة الأصلية.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


يضبط لوحة ألوان الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

