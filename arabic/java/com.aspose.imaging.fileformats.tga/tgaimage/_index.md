---
title: "TgaImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعديل ملفات صور TGA النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا المصممة لتنسيق TARGA Truevision Advanced Raster Adapter مما يتيح تحميلًا سلسًا وتخصيصًا."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

تعديل ملفات صور TGA النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، المصممة لتنسيق TARGA (Truevision Advanced Raster Adapter)، مما يتيح تحميلًا سلسًا وتخصيصًا. يمكنك بسهولة تحديث الخصائص العامة مثل المؤلف، والطابع الزمني، ومعرّف الصورة، وإصدار البرنامج، مع استخدام إعدادات مختلفة للبتات لكل بكسل، وقناة ألفا، وشفافية اللون. بالإضافة إلى ذلك، يمكنك تصدير صور TGA إلى تنسيقات نقطية شائعة أخرى، مما يضمن التوافق لمشاريعك.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | يُهيئ كائنًا جديدًا من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) باستخدام مسار الملف المقدم لتحميل محتوى الصورة. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | إنشاء نسخة جديدة من فئة [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) عن طريق توفير كائن صورة نقطية. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | تهيئة نسخة جديدة من فئة [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) باستخدام تدفق لتحميل الصورة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | استرجاع قيمة البتات لكل بكسل، مما يوفر معلومات أساسية حول عمق ألوان الصورة. |
| [getBytesPerPixel()](#getBytesPerPixel--) | الحصول على قيمة البايتات لكل بكسل، التي تشير إلى مقدار الذاكرة التي يشغلها كل بكسل في الصورة. |
| [hasAlpha()](#hasAlpha--) | استرجاع قيمة منطقية تشير إلى ما إذا كان [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) يتضمن قناة ألفا، مما يسهل تأثيرات الشفافية. |
| [isGrayScale()](#isGrayScale--) | الحصول على قيمة منطقية تشير إلى ما إذا كان [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) يمثل صورة بتدرج الرمادي. |
| [getWidth()](#getWidth--) | استرجاع عرض الصورة التي تمثلها هذه النسخة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getHeight()](#getHeight--) | الحصول على ارتفاع الصورة التي تحتويها هذه النسخة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [getFileFormat()](#getFileFormat--) | الحصول على معلومات حيوية حول تنسيق ملف الصورة التي تمثلها هذه النسخة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| [hasColorMap()](#hasColorMap--) | استرجاع ما إذا كانت هذه النسخة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) تحتوي على خريطة ألوان. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | يحصل على الجزء البسط من قيمة غاما، وهو أساسي لتمثيل الألوان بدقة في الصور. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | يسترجع الجزء المقام من قيمة غاما، وهو عامل أساسي في تحديد تمثيل الألوان داخل الصور. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | يسترجع المكوّن البسط لنسبة أبعاد البكسل، التي تؤثر على المظهر البصري للبكسلات داخل الصورة. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | يسترجع الجزء المقام لنسبة أبعاد البكسل، وهو عامل حاسم في تحديد المظهر البصري للبكسلات داخل الصورة. |
| [getXOrigin()](#getXOrigin--) | يحصل على الإحداثي الأفقي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA). |
| [setXOrigin(int value)](#setXOrigin-int-) | يضبط الإحداثي الأفقي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA). |
| [getYOrigin()](#getYOrigin--) | يحصل على الإحداثي العمودي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA). |
| [setYOrigin(int value)](#setYOrigin-int-) | يضبط الإحداثي العمودي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA). |
| [getImageId()](#getImageId--) | يحصل على المعرف الفريد المرتبط بالصورة. |
| [setImageId(String value)](#setImageId-java.lang.String-) | يضبط المعرف الفريد المرتبط بالصورة. |
| [getAuthorComments()](#getAuthorComments--) | يسترجع أو يضبط التعليقات التي قدمها مؤلف الصورة. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | يسترجع أو يضبط التعليقات التي قدمها مؤلف الصورة. |
| [getAuthorName()](#getAuthorName--) | يسترجع أو يعيّن اسم المؤلف المرتبط بالصورة. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | يسترجع أو يعيّن اسم المؤلف المرتبط بالصورة. |
| [getDateTimeStamp()](#getDateTimeStamp--) | يحصل على طابع التاريخ/الوقت. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | يعيّن طابع التاريخ/الوقت. |
| [getJobNameOrId()](#getJobNameOrId--) | يسترجع أو يعيّن اسم الوظيفة أو المعرف المرتبط بالصورة. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | يسترجع أو يعيّن اسم الوظيفة أو المعرف المرتبط بالصورة. |
| [getJobTime()](#getJobTime--) | يسترجع أو يعيّن طابع الوقت الذي يشير إلى وقت الوظيفة المرتبط بالصورة. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | يسترجع أو يعيّن طابع الوقت الذي يشير إلى وقت الوظيفة المرتبط بالصورة. |
| [getTransparentColor()](#getTransparentColor--) | يسترجع أو يعيّن اللون الرئيسي المرتبط بالصورة. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | يسترجع أو يعيّن اللون الرئيسي المرتبط بالصورة. |
| [hasTransparentColor()](#hasTransparentColor--) | يسترجع أو يعيّن قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | يسترجع أو يعيّن قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |
| [getBackgroundColor()](#getBackgroundColor--) | يسترجع أو يعيّن لون الخلفية للصورة. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يسترجع أو يعيّن لون الخلفية للصورة. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يسترجع أو يعيّن قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يسترجع أو يعيّن قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |
| [getSoftwareVersion()](#getSoftwareVersion--) | يسترجع أو يعيّن نسخة البرنامج المرتبطة بالصورة. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | يسترجع أو يعيّن نسخة البرنامج المرتبطة بالصورة. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | يسترجع أو يعيّن المكوّن الحرفي لنسخة البرنامج المرتبطة بالصورة. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | يسترجع أو يعيّن المكوّن الحرفي لنسخة البرنامج المرتبطة بالصورة. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | يسترجع أو يعيّن المكوّن الرقمي لنسخة البرنامج المرتبطة بالصورة. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | يسترجع أو يعيّن المكوّن الرقمي لنسخة البرنامج المرتبطة بالصورة. |
| [getSoftwareId()](#getSoftwareId--) | يدير معرف البرنامج (ID) المرتبط بالصورة، مع السماح بما يصل إلى 40 حرفًا ASCII. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | يدير معرف البرنامج (ID) المرتبط بالصورة، مع السماح بما يصل إلى 40 حرفًا ASCII. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | يُجري مقارنة مساواة بين صورتين TGA، مع مراعاة كل من الصورة الأولى والثانية المتورّطتين في عملية المقارنة. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | يُجري مقارنة عدم مساواة بين صورتين TGA، مع تقييم كل من الصورة الأولى والثانية المتورّطتين في المقارنة. |
| [deepClone()](#deepClone--) | ينتج نسخة مكررة من الكائن الحالي، مُنشئًا كائنًا جديدًا ينسخ جميع السمات والخصائص من الأصل. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | استنسخ خصائص كائن [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) آخر، مُنشئًا نسخة جديدة بسمات مطابقة. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | في مقارنة مساواة، تُقَيِّم الطريقة ما إذا كانت نسخة [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) الحالية مساوية للصورة الثانية المقدمة كمعامل. |
| [equals(Object other)](#equals-java.lang.Object-) | تُجري الطريقة مقارنة مساواة بين نسخة [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) الحالية وكائن آخر مُقدَّم كمعامل. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | تتيح طريقة "rotateFlip" عمليات الدوران والقلب على الصورة. |
| [hashCode()](#hashCode--) | استرجع قيمة التجزئة (hash code) للنسخة الحالية. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة إلى منطقة محددة. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قص الصورة بتحديد إزاحات للحدود اليسرى، اليمنى، العليا والسفلى. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | غيّر حجم الصورة مع تطبيق إعدادات محددة للحفاظ على الأبعاد المطلوبة ونسبة العرض إلى الارتفاع. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يضبط حجم الصورة باستخدام نوع تغيير حجم محدد، والذي يحدد كيفية تنفيذ عملية تغيير الحجم. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | يدور الصورة حول مركزها بزاوية محددة مع الحفاظ على تناسق الحجم وإبقاء لون الخلفية. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


يقوم بتهيئة كائن [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) جديد باستخدام مسار الملف المقدم لتحميل محتوى الصورة. يقوم هذا المُنشئ بتهيئة نسخة الصورة بكفاءة، مما يسمح بالوصول السلس إلى ملفات صور TGA، وتبسيط دمجها في سير عمل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | المسار لتحميل صورة. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


إنشاء نسخة جديدة من فئة [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) عن طريق توفير كائن صورة نقطية. يسهل هذا المُنشئ دمج الصور النقطية الحالية مباشرةً في تنسيق صورة TGA، مما يبسط عملية التحويل لتوافق أفضل داخل أنظمة البرمجيات الخاصة بك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


تهيئة نسخة جديدة من فئة [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) باستخدام تدفق لتحميل الصورة. يتيح هذا المُنشئ دمج بيانات الصورة من التدفقات بسلاسة، مما يسهل التعامل الفعال ومعالجة صور TGA داخل تطبيقاتك البرمجية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | التدفق لتحميل صورة. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


استرجاع قيمة البتات لكل بكسل، مع توفير معلومات أساسية حول عمق ألوان الصورة. تُعد هذه الخاصية مقياسًا حاسمًا لفهم مستوى التفاصيل وغنى الألوان الموجود في الصورة، مما يساعد المطورين على تحسين خوارزميات المعالجة وتخصيص الموارد لتحقيق معالجة وعرض صورة فعّال.

**Returns:**
int - بتات لكل بكسل.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


الحصول على قيمة البايتات لكل بكسل، التي تشير إلى مقدار الذاكرة التي يشغلها كل بكسل في الصورة. تُعد هذه الخاصية مقياسًا مهمًا لإدارة الذاكرة وتحسينها، مما يساعد المطورين على تخصيص الموارد ومعالجة بيانات الصورة بكفاءة.

**Returns:**
int - بايتات لكل بكسل.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


استرجاع قيمة منطقية تشير إلى ما إذا كان [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) يتضمن قناة ألفا، مما يسهل تأثيرات الشفافية. توفر هذه الخاصية معلومات أساسية لمعالجة تركيب الصورة وعرضها، وتساعد المطورين على تنفيذ تأثيرات بصرية متنوعة وعمليات تركيب.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) يحتوي على قناة ألفا.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


الحصول على قيمة منطقية تشير إلى ما إذا كان [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) يمثل صورة ذات تدرج رمادي. تُعد هذه الخاصية حاسمة للتمييز بين الصور الملونة وتلك ذات التدرج الرمادي، مما يساعد المطورين على تطبيق تقنيات المعالجة والعرض المناسبة بناءً على خصائص ألوان الصورة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كان هذا [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) بتدرج رمادي.
### getWidth() {#getWidth--}
```
public int getWidth()
```


استرجاع عرض الصورة الممثلة بواسطة هذه النسخة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). توفر هذه الخاصية للمطورين معلومات أساسية حول أبعاد الصورة، مما يسهل مهام تعديل ومعالجة الصور المختلفة داخل تطبيقاتهم البرمجية.

**Returns:**
int - عرض هذه الصورة بالبكسل.
### getHeight() {#getHeight--}
```
public int getHeight()
```


الحصول على ارتفاع الصورة المضمنة في هذه النسخة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). تزود هذه الخاصية المطورين بتفاصيل حيوية حول الأبعاد العمودية للصورة، مما يتيح دمجًا سلسًا وتعديلًا للصور داخل حلول البرمجيات الخاصة بهم.

**Returns:**
int - ارتفاع هذه الصورة بالبكسل.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


احصل على معلومات حاسمة حول تنسيق ملف الصورة الممثلة بهذه الحالة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). فهم تنسيق الملف أمر أساسي لفحوصات التوافق وضمان تكامل سلس داخل أنظمة البرمجيات، مما يتيح معالجة وتعديل الصور بكفاءة.

**Returns:**
long - معلومات حاسمة حول تنسيق ملف الصورة الممثلة بهذه الحالة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage).
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


استرجع ما إذا كانت هذه الحالة من [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) تحتوي على خريطة ألوان. فهم وجود خريطة الألوان أمر حاسم للتفسير الدقيق ومعالجة بيانات ألوان الصورة.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت هذه الصورة تحتوي على خريطة ألوان.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


يحصل على الجزء البسط من قيمة جاما، وهو أمر أساسي لتمثيل الألوان بدقة في الصور. في الصور بدون تصحيح جاما، يجب أن تكون هذه القيمة 1.0. فهم واستخدام هذه القيمة أمر حاسم للحفاظ على دقة الألوان وضمان عرض الصورة بدقة.

**Returns:**
int - الجزء البسط من قيمة جاما، وهو أمر أساسي لتمثيل الألوان بدقة في الصور.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


يسترجع الجزء المقام من قيمة جاما، وهو عامل أساسي في تحديد تمثيل الألوان داخل الصور. بالنسبة للصور التي تفتقر إلى تصحيح جاما، يجب أن تكون هذه القيمة 1.0، مما يضمن عرض ألوان دقيق. تقدير واستخدام هذه المعلمة أساسي للحفاظ على دقة الألوان وتحقيق تصور صورة دقيق.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


يسترجع المكوّن البسط من نسبة أبعاد البكسل، التي تؤثر على المظهر البصري للبكسلات داخل الصورة. فهم وتعديل هذه القيمة أمر أساسي لتحقيق تمثيل بكسل دقيق ونسب أبعاد صحيحة في عرض ومعالجة الصورة.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


يسترجع الجزء المقام من نسبة أبعاد البكسل، وهو عامل حاسم في تحديد المظهر البصري للبكسلات داخل الصورة. هذه القيمة أساسية للحفاظ على تمثيل بكسل دقيق ونسب أبعاد طوال عمليات عرض ومعالجة الصور المختلفة، مما يضمن مخرجات بصرية عالية الجودة.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


يحصل على الإحداثي الأفقي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA).

**Returns:**
int - إحداثي أفقي مطلق للزاوية السفلية اليسرى للصورة كما هو موضع على جهاز عرض يملك الأصل في أسفل يسار الشاشة.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


يضبط الإحداثي الأفقي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحداثي أفقي مطلق للزاوية السفلية اليسرى للصورة كما هو موضع على جهاز عرض يملك الأصل في أسفل يسار الشاشة. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


يحصل على الإحداثي العمودي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA).

**Returns:**
int - إحداثي عمودي مطلق للزاوية السفلية اليسرى للصورة كما هو موضع على جهاز عرض يملك الأصل في أسفل يسار الشاشة.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


يضبط الإحداثي العمودي المطلق للزاوية السفلية اليسرى للصورة كما يتم وضعها على جهاز عرض يكون أصله في أسفل اليسار من الشاشة (مثال: سلسلة TARGA).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | إحداثي عمودي مطلق للزاوية السفلية اليسرى للصورة كما هو موضع على جهاز عرض يملك الأصل في أسفل يسار الشاشة. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


يحصل على المعرف الفريد المرتبط بالصورة. هذا المعرف يعمل كنقطة مرجعية لتحديد وتمييز الصورة عن غيرها داخل نظام أو تطبيق. من خلال تعيين أو استرجاع معرف الصورة، يمكنك إدارة وتتبع الصور بفعالية، مما يسهل عمليات إدارة واسترجاع الصور المنظمة.

هذا الحقل الاختياري يحتوي على معلومات تعريفية حول الصورة. الحد الأقصى لطول هذا الحقل هو 255 بايت.

**Returns:**
java.lang.String - المعرف الفريد المرتبط بالصورة.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


يضبط المعرف الفريد المرتبط بالصورة. هذا المعرف يعمل كنقطة مرجعية لتحديد وتمييز الصورة عن غيرها داخل نظام أو تطبيق. من خلال تعيين أو استرجاع معرف الصورة، يمكنك إدارة وتتبع الصور بفعالية، مما يسهل عمليات إدارة واسترجاع الصور المنظمة.

هذا الحقل الاختياري يحتوي على معلومات تعريفية حول الصورة. الحد الأقصى لطول هذا الحقل هو 255 بايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | المعرف الفريد المرتبط بالصورة. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


يسترجع أو يضبط التعليقات التي قدمها مؤلف الصورة. غالبًا ما تحتوي هذه التعليقات على معلومات قيمة، مثل الأوصاف، التعليقات التوضيحية، أو سياق إضافي حول الصورة. من خلال الوصول إلى خاصية تعليقات المؤلف أو تعديلها، يمكن للمطورين تعزيز البيانات الوصفية المرتبطة بالصورة، وتزويد المستخدمين برؤى قيمة وسياق حول محتواها أو إنشاءها. هذا حقل ASCII يتكون من 324 بايت منظمة كأربع أسطر من 80 حرفًا، يتبع كل منها فاصل صفري.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


يسترجع أو يضبط التعليقات التي قدمها مؤلف الصورة. غالبًا ما تحتوي هذه التعليقات على معلومات قيمة، مثل الأوصاف، التعليقات التوضيحية، أو سياق إضافي حول الصورة. من خلال الوصول إلى خاصية تعليقات المؤلف أو تعديلها، يمكن للمطورين تعزيز البيانات الوصفية المرتبطة بالصورة، وتزويد المستخدمين برؤى قيمة وسياق حول محتواها أو إنشاءها. هذا حقل ASCII يتكون من 324 بايت منظمة كأربع أسطر من 80 حرفًا، يتبع كل منها فاصل صفري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


يسترجع أو يضبط اسم المؤلف المرتبط بالصورة. تسمح هذه الخاصية للمطورين بالوصول إلى بيانات اسم المؤلف أو تعديلها، مما يوفر معلومات قيمة حول منشئ الصورة. باستخدام خاصية اسم المؤلف، يمكن للمستخدمين بسهولة التعرف على الفرد المسؤول عن إنشاء أو المساهمة في الصورة، مما يعزز بياناتها الوصفية العامة ويوفر سياقًا قيمًا للمشاهدين. هذا الحقل يتضمن إجمالي 40 حرفًا ASCII للاسم. إذا تم استخدام الحقل، يجب أن يحتوي على اسم الشخص الذي أنشأ الصورة (المؤلف).

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


يسترجع أو يضبط اسم المؤلف المرتبط بالصورة. تسمح هذه الخاصية للمطورين بالوصول إلى بيانات اسم المؤلف أو تعديلها، مما يوفر معلومات قيمة حول منشئ الصورة. باستخدام خاصية اسم المؤلف، يمكن للمستخدمين بسهولة التعرف على الفرد المسؤول عن إنشاء أو المساهمة في الصورة، مما يعزز بياناتها الوصفية العامة ويوفر سياقًا قيمًا للمشاهدين. هذا الحقل يتضمن إجمالي 40 حرفًا ASCII للاسم. إذا تم استخدام الحقل، يجب أن يحتوي على اسم الشخص الذي أنشأ الصورة (المؤلف).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | اسم المؤلف. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


يحصل على طابع التاريخ/الوقت. يحدد هذا الحقل قيمة التاريخ والوقت الذي تم حفظ الصورة فيه. على الرغم من أن أنظمة التشغيل عادةً ما تضيف طابعًا زمنيًا وتاريخيًا للملفات، فإن هذه الميزة متوفرة لأن نظام التشغيل قد يغيّر الطابع الزمني إذا تم نسخ الملف. باستخدام هذه المنطقة، تضمن وجود منطقة غير معدلة لتسجيل التاريخ والوقت.

**Returns:**
java.util.Date - طابع التاريخ/الوقت.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


يضبط Date/Time Stamp. يحدد هذا الحقل القيمة لتاريخ ووقت حفظ الصورة. على الرغم من أن أنظمة التشغيل عادةً ما تضيف طابع الوقت والتاريخ للملفات، فإن هذه الميزة متوفرة لأن نظام التشغيل قد يغير طابع الوقت والتاريخ إذا تم نسخ الملف. باستخدام هذه المنطقة، تضمن وجود منطقة غير معدلة لتسجيل التاريخ والوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date | Date/Time Stamp. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


يسترجع أو يضبط اسم المهمة أو المعرف المرتبط بالصورة. تتيح هذه الخاصية لك الوصول إلى بيانات التعريف أو تعديلها المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة. باستخدام خاصية Job Name/ID، يمكن للمستخدمين بسهولة تحديد المشروع أو المهمة التي تتعلق بها الصورة، مما يسهل تنظيم وإدارة موارد الصور ضمن سير عمل أو مشاريع أكبر.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


يسترجع أو يضبط اسم المهمة أو المعرف المرتبط بالصورة. تتيح هذه الخاصية لك الوصول إلى بيانات التعريف أو تعديلها المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة. باستخدام خاصية Job Name/ID، يمكن للمستخدمين بسهولة تحديد المشروع أو المهمة التي تتعلق بها الصورة، مما يسهل تنظيم وإدارة موارد الصور ضمن سير عمل أو مشاريع أكبر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


يسترجع أو يضبط الطابع الزمني الذي يشير إلى وقت المهمة المرتبط بالصورة. تتيح هذه الخاصية للمطورين الوصول إلى بيانات الوقت أو تعديلها المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


يسترجع أو يضبط الطابع الزمني الذي يشير إلى وقت المهمة المرتبط بالصورة. تتيح هذه الخاصية للمطورين الوصول إلى بيانات الوقت أو تعديلها المتعلقة بالمهمة أو المشروع المحدد المرتبط بالصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


يسترجع أو يضبط اللون الرئيسي المرتبط بالصورة. تتيح هذه الخاصية لك الوصول إلى اللون المحدد كلون رئيسي لمهام أو تأثيرات معالجة الصور المحددة. يتيح استخدام خاصية Key Color للمستخدمين تطبيق عمليات تعتمد على اللون مثل إزالة الخلفية باللون الأخضر أو استبدال اللون، مما يعزز قدرات تعديل الصورة وإمكانيات الإبداع.

يمكن التفكير في Key Color على أنه \\u2018background color\\u2019 أو \\u2018transparent color\\u2019. هذا هو لون منطقة \\u2018non image\\u2019 على الشاشة، وهو نفس اللون الذي ستُمسح إليه الشاشة إذا تم مسحها في التطبيق.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


يسترجع أو يضبط اللون الرئيسي المرتبط بالصورة. تتيح هذه الخاصية لك الوصول إلى اللون المحدد كلون رئيسي لمهام أو تأثيرات معالجة الصور المحددة. يتيح استخدام خاصية Key Color للمستخدمين تطبيق عمليات تعتمد على اللون مثل إزالة الخلفية باللون الأخضر أو استبدال اللون، مما يعزز قدرات تعديل الصورة وإمكانيات الإبداع.

يمكن التفكير في Key Color على أنه \\u2018background color\\u2019 أو \\u2018transparent color\\u2019. هذا هو لون منطقة \\u2018non image\\u2019 على الشاشة، وهو نفس اللون الذي ستُمسح إليه الشاشة إذا تم مسحها في التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


يسترجع أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. هذه الخاصية أساسية لتحديد ما إذا كانت الصورة تدعم الشفافية، مما يساعدك على تنفيذ التعامل المناسب مع عمليات الشفافية مثل الدمج أو التركيب أو القناع.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


يسترجع أو يضبط قيمة منطقية تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. هذه الخاصية أساسية لتحديد ما إذا كانت الصورة تدعم الشفافية، مما يساعدك على تنفيذ التعامل المناسب مع عمليات الشفافية مثل الدمج أو التركيب أو القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون شفاف. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يسترجع أو يضبط لون الخلفية للصورة. تتيح هذه الخاصية لك تحديد اللون المستخدم كخلفية للصورة، مما يضمن التناسق ويعزز العرض البصري. إنها مفيدة بشكل خاص في السيناريوهات التي تُعرض فيها الصورة على خلفية بلون مختلف أو عند رسم الصورة على لوحة أخرى.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يسترجع أو يضبط لون الخلفية للصورة. تتيح هذه الخاصية لك تحديد اللون المستخدم كخلفية للصورة، مما يضمن التناسق ويعزز العرض البصري. إنها مفيدة بشكل خاص في السيناريوهات التي تُعرض فيها الصورة على خلفية بلون مختلف أو عند رسم الصورة على لوحة أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


يسترجع أو يضبط قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة لتحديد ما إذا كانت الصورة تشمل لون خلفية مميز منفصل عن محتوى المقدمة. تمكنك من تخصيص معالجة الصورة أو عرضها بناءً على وجود أو عدم وجود لون الخلفية.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


يسترجع أو يضبط قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. هذه الخاصية مفيدة لتحديد ما إذا كانت الصورة تشمل لون خلفية مميز منفصل عن محتوى المقدمة. تمكنك من تخصيص معالجة الصورة أو عرضها بناءً على وجود أو عدم وجود لون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كانت الصورة تحتوي على لون خلفية. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


يسترجع أو يضبط نسخة البرنامج المرتبطة بالصورة. الطول المقبول لسلسلة النسخة عادةً ما يكون من 3 إلى 4 أحرف. هذه الخاصية مفيدة لتتبع البرنامج المستخدم لإنشاء أو تعديل الصورة ويمكن أن توفر سياقًا قيمًا لمعالجة الصور وفحوصات التوافق.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


يسترجع أو يضبط نسخة البرنامج المرتبطة بالصورة. الطول المقبول لسلسلة النسخة عادةً ما يكون من 3 إلى 4 أحرف. هذه الخاصية مفيدة لتتبع البرنامج المستخدم لإنشاء أو تعديل الصورة ويمكن أن توفر سياقًا قيمًا لمعالجة الصور وفحوصات التوافق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


يسترجع أو يضبط المكوّن الحرفي لنسخة البرنامج المرتبطة بالصورة. تمثل هذه الخاصية تفصيلًا إضافيًا داخل سلسلة نسخة البرنامج ويمكن أن تكون مفيدة لتفريق النسخ بدقة أكبر.

**Returns:**
char - جزء الحرف من إصدار البرنامج.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


يسترجع أو يضبط المكوّن الحرفي لنسخة البرنامج المرتبطة بالصورة. تمثل هذه الخاصية تفصيلًا إضافيًا داخل سلسلة نسخة البرنامج ويمكن أن تكون مفيدة لتفريق النسخ بدقة أكبر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | char | جزء الحرف من إصدار البرنامج. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


يسترجع أو يعيّن المكوّن الرقمي لإصدار البرنامج المرتبط بالصورة. تمثل هذه الخاصية الجزء الرقمي من سلسلة إصدار البرنامج، وتوفر معلومات هامة حول نسخة البرنامج المستخدمة لإنشاء الصورة أو تعديلها.

**Returns:**
int - جزء الرقم من إصدار البرنامج.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


يسترجع أو يعيّن المكوّن الرقمي لإصدار البرنامج المرتبط بالصورة. تمثل هذه الخاصية الجزء الرقمي من سلسلة إصدار البرنامج، وتوفر معلومات هامة حول نسخة البرنامج المستخدمة لإنشاء الصورة أو تعديلها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | جزء الرقم من إصدار البرنامج. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


يدير تعريف البرنامج (المعرّف) المرتبط بالصورة، ويسمح بما يصل إلى 40 حرف ASCII. تُستخدم هذه الخاصية كوسيلة لتحديد البرنامج المستخدم في إنشاء أو معالجة الصورة بشكل فريد، وتوفر بيانات وصفية قيمة لأغراض التنظيم والمعلومات.

**Returns:**
java.lang.String - معرّف البرنامج.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


يدير تعريف البرنامج (المعرّف) المرتبط بالصورة، ويسمح بما يصل إلى 40 حرف ASCII. تُستخدم هذه الخاصية كوسيلة لتحديد البرنامج المستخدم في إنشاء أو معالجة الصورة بشكل فريد، وتوفر بيانات وصفية قيمة لأغراض التنظيم والمعلومات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | معرّف البرنامج. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


يُجري مقارنة مساواة بين صورتين TGA، مع الأخذ في الاعتبار كل من الصورة الأولى والثانية المشاركة في عملية المقارنة. تُسهّل هذه الطريقة تقييم مساواة الصور بشكل مباشر، مما يضمن تحليلًا دقيقًا واتخاذ قرارات صحيحة ضمن سير عمل معالجة الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | الصورة الأولى [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) التي تشارك في المقارنة. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | الصورة الثانية [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) التي تشارك في المقارنة. |

**Returns:**
boolean - نتائج المقارنة.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


يُجري مقارنة عدم مساواة بين صورتين TGA، مع تقييم كل من الصورة الأولى والثانية المشاركة في المقارنة. تُساعد هذه الطريقة في تحديد الاختلافات أو الفروقات بين الصور، مما يتيح تحليلًا دقيقًا واتخاذ قرارات في مهام معالجة الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | الصورة الأولى [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) التي تشارك في المقارنة. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | الصورة الثانية [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) التي تشارك في المقارنة. |

**Returns:**
boolean - نتائج المقارنة.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


ينتج نسخة مكررة من الكائن الحالي، مُنشئًا كائنًا جديدًا ينسخ جميع السمات والخصائص من الأصل. تُسهل هذه الطريقة إنشاء نسخ مطابقة، مما يضمن سلامة البيانات ويحافظ على حالة الكائن الحالي دون التأثير على الكائن الأصلي.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


تكرار خصائص كائن [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) آخر، وإنشاء نسخة جديدة بسمات مطابقة. يضمن هذا الإجراء الحفاظ على سلامة البيانات ويسهّل تكرار خصائص الصورة دون تعديل الكائن المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | آخر [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


في مقارنة مساواة، تقوم الطريقة بتقييم ما إذا كان كائن [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) الحالي يساوي الصورة الثانية المقدمة كمعامل. يُسهل هذا الإجراء تحديد ما إذا كانت صورتان TGA متطابقتين، مما يساعد في مهام معالجة الصور والمقارنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | الصورة الثانية [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) التي تشارك في المقارنة. |

**Returns:**
boolean - نتائج المقارنة.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


تُجري الطريقة مقارنة مساواة بين كائن [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) الحالي وكائن آخر يُقدم كمعامل. بالتحديد، تُقيم ما إذا كانت خصائص الصورة الحالية تطابق خصائص الكائن الثاني، مما يساعد في تحديد تكافئهما لأغراض المقارنة ضمن سير عمل معالجة الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | java.lang.Object | الصورة الثانية [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) التي تشارك في المقارنة. |

**Returns:**
boolean - نتائج المقارنة.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


تُمكّن الطريقة "rotateFlip" من عمليات الدوران والقلب على الصورة. توفر هذه الوظيفة مرونة متعددة لتعديل اتجاه الصورة، مما يسمح للمستخدمين بإجراء دورانات وقلب وفقًا لمتطلباتهم، وتسهيل مهام معالجة الصور بكفاءة داخل تطبيقات البرمجيات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع الدوران والقلب. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


استرجع قيمة التجزئة (hash code) للكائن الحالي. ومع ذلك، من المهم ملاحظة أن هذه القيمة قد لا تكون مناسبة للاستخدام كمفتاح، خصوصًا لأن كائنات فئة TgaImage ليست ثابتة.

**Returns:**
int - قيمة التجزئة لهذا الكائن.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قم بقص الصورة إلى منطقة محددة. تتيح هذه الطريقة لك تعريف مساحة مستطيلة داخل الصورة للاحتفاظ بها، مع حذف البقية. هذه العملية مفيدة للتركيز على محتوى معين داخل الصورة أو لإزالة أجزاء غير مرغوب فيها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قم بقص الصورة عن طريق تحديد الإزاحات للحدود اليسرى واليمنى والعلوية والسفلية. تسمح لك هذه الطريقة بقص الصورة عن طريق تحريك حدودها بشكل مستقل على المحورين الأفقي والعمودي. من خلال ضبط هذه الإزاحات، يمكنك التحكم بدقة في الأجزاء التي تريد الاحتفاظ بها من الصورة، وبالتالي قصها إلى الأبعاد المطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


قم بتغيير حجم الصورة مع تطبيق إعدادات محددة للحفاظ على الأبعاد المطلوبة ونسبة العرض إلى الارتفاع. من خلال تخصيص إعدادات الصورة، يمكنك تعديل حجم الصورة بفعالية مع ضمان جودة بصرية مثالية وتوافق مع مختلف أجهزة العرض أو التطبيقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يضبط حجم الصورة باستخدام نوع تغيير حجم محدد، والذي يحدد كيفية تنفيذ عملية تغيير الحجم. توفر هذه الطريقة مرونة في تعديل حجم الصور وفقًا لخوارزميات أو تقنيات مختلفة. باختيار نوع تغيير الحجم المناسب، يمكنك تحقيق التوازن المطلوب بين جودة الصورة والكفاءة الحسابية بناءً على المتطلبات أو التفضيلات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


يدور الصورة حول مركزها بزاوية محددة مع الحفاظ على تناسب تغيير الحجم وحفظ لون الخلفية. تتيح هذه الطريقة تعديل الصورة بدقة، مع ضمان أن يدور الصورة بطريقة تحافظ على التوازن البصري والاتساق مع لون الخلفية المحدد. إنها مثالية للمهام التي تتطلب دورانًا دقيقًا حول المركز، مثل تصحيح الاتجاه أو التعديلات الفنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تعديل وتُدور فقط محتويات الصورة ``. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

