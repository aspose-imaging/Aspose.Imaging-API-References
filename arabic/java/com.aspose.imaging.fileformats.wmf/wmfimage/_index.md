---
title: "WmfImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تفاعل مع صور Microsoft Windows Metafile WMF باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع معالجة سلسة لكل من البيانات المتجهية والبتية المخزنة في سجلات ذات طول متغير."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

تفاعل مع صور Microsoft Windows Metafile (WMF) باستخدام واجهة برمجة التطبيقات الخاصة بنا، مع معالجة سلسة لكل من البيانات المتجهية والبتية المخزنة في سجلات ذات طول متغير. قم بتغيير حجم الصور، وتدويرها، وعكسها بسهولة مع ضبط لوحات ألوان مخصصة. حوّل ملفات WMF إلى صيغ WMZ مضغوطة أو احفظها بصيغ صور نقطية للاستخدام المتعدد عبر المنصات والتطبيقات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WmfImage()](#WmfImage--) | أنشئ مثيلاً جديداً من الفئة [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage)، مهيئاً إياه لمزيد من التفاعل ومعالجة بيانات صورة Windows Metafile (WMF). |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | أنشئ مثيلاً جديداً من الفئة [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) مع معلمات عرض وارتفاع قابلة للتخصيص، مما يسهل إنشاء صور WMF فارغة مخصصة لأبعاد محددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isCached()](#isCached--) | استرجع قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً، مما يلغي الحاجة إلى عمليات قراءة بيانات إضافية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجع عدد البتات لكل بكسل في الصورة، مما يدل على مستوى عمق اللون أو الدقة. |
| [getWidthF()](#getWidthF--) | الوصول إلى عرض الصورة، مما يدل على عدد البكسلات على المحور الأفقي. |
| [getHeightF()](#getHeightF--) | الوصول إلى ارتفاع الصورة، ممثلاً عدد البكسلات على المحور العمودي. |
| [getInch()](#getInch--) | الوصول إلى خاصية البوصة أو تعديلها، تمثّل وحدة قياس تُستخدم عادةً لتحديد الأبعاد الفيزيائية في سياقات الطباعة أو العرض. |
| [setInch(int value)](#setInch-int-) | الوصول إلى خاصية البوصة أو تعديلها، تمثّل وحدة قياس تُستخدم عادةً لتحديد الأبعاد الفيزيائية في سياقات الطباعة أو العرض. |
| [getFileFormat()](#getFileFormat--) | الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، لتوفير معلومات حول الصيغة التي تُخزن بها الصورة. |
| [getFrameBounds()](#getFrameBounds--) | الوصول إلى حدود الإطار، موضحاً موقعه وأبعاده داخل الصورة. |
| [cacheData()](#cacheData--) | قم بتخزين البيانات مؤقتاً بكفاءة، مما يلغي الحاجة إلى تحميل إضافي من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | طبق لوحة ألوان محددة على الصورة، مما يتيح تخصيص تمثيل الألوان. |
| [getUsedFonts()](#getUsedFonts--) | استرجع قائمة الخطوط المستخدمة داخل ملف التعريف، لتوفير نظرة على موارد الخطوط المستخدمة في الصورة. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | غيّر حجم لوحة الرسم الخاصة بالصورة، مع تعديل أبعادها مع الحفاظ على محتوى الصورة. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | دمج كائن السجل المحدد في الصورة، مما يُثري محتواها ببيانات إضافية أو بيانات وصفية. |
| [getPostScript()](#getPostScript--) | الوصول إلى بيانات PostScript المرتبطة بالصورة، مع توفير معلومات تفصيلية حول هيكلها أو محتواها. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على خيارات الصورة الأصلية. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


إنشاء مثيل جديد من الفئة [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage)، مع تهيئته لمزيد من المعالجة والتعامل مع بيانات صورة Windows Metafile (WMF). يوفر هذا المُنشئ كائنًا أساسيًا للعمل مع صور WMF، مما يتيح دمجًا سلسًا لإمكانيات معالجة صور WMF في وظائف تطبيقك.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


إنشاء مثيل جديد من الفئة [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) مع معلمات عرض وارتفاع قابلة للتخصيص، لتسهيل إنشاء صور WMF فارغة مخصصة لأبعاد محددة. استخدم هذا المُنشئ لتوليد صور WMF ديناميكيًا بأبعاد دقيقة، مما يتيح إنشاء وتعديل صور مرن داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | العرض. |
| height | int | الارتفاع. |

### isCached() {#isCached--}
```
public boolean isCached()
```


استرجاع قيمة منطقية تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى عمليات قراءة بيانات إضافية. استخدم هذه الخاصية لتحسين الأداء من خلال تحديد ما إذا كانت بيانات الكائن متاحة بسهولة دون الحاجة إلى عمليات استرجاع بيانات مكلفة داخل تطبيقك.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجاع عدد البتات لكل بكسل في الصورة، مما يدل على مستوى عمق اللون أو الدقة. استخدم هذه الخاصية لتحديد تمثيل اللون والدقة في الصورة، مما يسهل فحوص التوافق ومعالجة الألوان داخل تطبيقك.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


الوصول إلى عرض الصورة، مما يدل على عدد البكسلات على المحور الأفقي. استخدم هذه الخاصية لتحديد أبعاد الصورة المكانية ونسبة العرض إلى الارتفاع، مما يتيح تعديل تخطيط وعرض دقيق داخل تطبيقك.

**Returns:**
float - عرض الصورة بالبكسل.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


الوصول إلى ارتفاع الصورة، الذي يمثل عدد البكسلات على المحور العمودي. استخدم هذه الخاصية لتحديد أبعاد الصورة المكانية ونسبة العرض إلى الارتفاع، مما يتيح تعديل تخطيط وعرض دقيق داخل تطبيقك.

**Returns:**
float - ارتفاع الصورة بالبكسل.
### getInch() {#getInch--}
```
public int getInch()
```


الوصول إلى خاصية البوصة أو تعديلها، التي تمثل وحدة قياس تُستخدم عادة لتحديد الأبعاد الفيزيائية في سياق الطباعة أو العرض. استخدم هذه الخاصية لتحديد أو استرجاع قيم البوصة المرتبطة بالصورة، مما يسهل تمثيلًا دقيقًا للأبعاد الفيزيائية داخل تطبيقك.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


الوصول إلى خاصية البوصة أو تعديلها، التي تمثل وحدة قياس تُستخدم عادة لتحديد الأبعاد الفيزيائية في سياق الطباعة أو العرض. استخدم هذه الخاصية لتحديد أو استرجاع قيم البوصة المرتبطة بالصورة، مما يسهل تمثيلًا دقيقًا للأبعاد الفيزيائية داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، مع توفير معلومات حول التنسيق الذي تُخزن به الصورة. استخدم هذه الخاصية لتحديد تنسيق ملف الصورة، مما يسهل فحوص التوافق والمعالجة الخاصة بالتنسيق داخل تطبيقك.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


الوصول إلى حدود الإطار، مع الإشارة إلى موقعه وأبعاده داخل الصورة. استخدم هذه الخاصية لاسترجاع معلومات تفصيلية عن الموقع المكاني للإطار، مما يتيح تعديلًا دقيقًا وعرضًا داخل تطبيقك.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


تخزين البيانات مؤقتًا بكفاءة، مما يلغي الحاجة إلى تحميل إضافي من `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). استخدم هذه الطريقة لتحسين الأداء وتقليل استهلاك الموارد داخل تطبيقك عن طريق تخزين والوصول إلى ذاكرة التخزين المؤقت المحلية.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // تخزين البيانات مؤقتًا لتحميل جميع السجلات.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // المفتاح هو نوع السجل، والقيمة هي عدد السجلات من ذلك النوع في صورة WMF.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // جمع الإحصائيات
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
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
    wmfImage.dispose();
}

//قد يبدو الإخراج هكذا:
//الإجمالي الكلي للسجلات: 613
//نوع السجل                              العدد
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


تطبيق لوحة ألوان محددة على الصورة، مما يتيح تخصيص تمثيل الألوان. استخدم هذه الطريقة لتحسين العرض البصري وتحقيق تأثيرات لونية محددة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


استرجاع قائمة الخطوط المستخدمة داخل ملف الميتا، لتوفير نظرة على موارد الخطوط المستخدمة في الصورة. استخدم هذه الطريقة لتحليل استخدام الخطوط وضمان توفر الخطوط للعرض أو المعالجة الإضافية داخل تطبيقك.

**Returns:**
java.lang.String[] - قائمة الخطوط
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


تغيير حجم لوحة الرسم للصورة، مع تعديل أبعادها مع الحفاظ على محتوى الصورة. استخدم هذه الطريقة لتعديل حجم اللوحة دون تغيير المحتوى، مما يسهل تعديل التخطيط وتغييرات التركيب داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الجديد. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


دمج كائن السجل المحدد في الصورة، مما يثري محتواها ببيانات إضافية أو بيانات وصفية. استخدم هذه الطريقة لدمج كائنات السجل بسلاسة في الصورة، مما يسهل تخزين البيانات بشكل شامل وتنظيمها داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | السجل. |

**Returns:**
int - عدد السجل.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


الوصول إلى بيانات PostScript المرتبطة بالصورة، وتوفير معلومات مفصلة حول هيكلها أو محتواها. استخدم هذه الطريقة لاسترداد بيانات PostScript لمزيد من التحليل أو المعالجة داخل تطبيقك، مما يتيح وظائف متقدمة متعلقة بتصيير أو معالجة PostScript.

**Returns:**
java.lang.String - النص البرمجي
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على خيارات الصورة الأصلية.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
