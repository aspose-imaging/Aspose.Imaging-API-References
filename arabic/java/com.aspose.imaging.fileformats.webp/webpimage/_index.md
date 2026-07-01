---
title: "WebPImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "قم بمعالجة صور WebP النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا باستخدام ميزاتها الحديثة لكل من الضغط غير الفاقد والفقدان، مما يضمن جودة صورة مثالية مع تقليل حجم الملفات."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

قم بمعالجة صور WebP النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، باستخدام ميزاتها الحديثة لكل من الضغط غير الفاقد والفقدان، مما يضمن جودة صورة مثالية مع تقليل حجم الملفات. تعامل بسلاسة مع صيغ الملفات الموسعة، والرسوم المتحركة، وقنوات ألفا، مع تحديث الأبعاد بسهولة، وإعادة التحجيم بشكل متناسب، والقص، والدوران، وتطبيق الفلاتر، وضبط معلمات الصورة، وتحويلها إلى صيغ صور أخرى لتحسين مرن للصور على الويب.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مبدئية من مصدر تدفق مُقدم. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام تدفق وخيارات تحميل محددة، مما يسهل التعامل المتنوع مع بيانات صورة WebP. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مبدئية من مصدر ملف مُقدم. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام ملف وخيارات تحميل محددة، مما يسهل التعامل المرن مع بيانات صورة WebP. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مبدئية من كائن rasterImage مُقدم. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام كائن rasterImage وخيارات تحميل محددة، مما يتيح التعامل المرن مع بيانات الصورة. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة بأبعاد عرض وارتفاع محددة. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة وخيارات تحميل محددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOptions()](#getOptions--) | استرجاع أو تعديل الخيارات المرتبطة بالخاصية المحددة، مما يتيح تخصيصًا دقيقًا للسلوك والإعدادات. |
| [getPages()](#getPages--) | الوصول إلى كتل WebP داخل الصورة، مما يسمح بفحص مفصل أو تعديل للهيكل الكتلي الأساسي. |
| [getPageCount()](#getPageCount--) | استرجع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. |
| [getFileFormat()](#getFileFormat--) | الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، لتوفير معلومات حول الصيغة التي تُخزن بها الصورة. |
| [hasAlpha()](#hasAlpha--) | استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يدل على وجود معلومات شفافية. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | إضافة صفحة جديدة إلى الصورة، لتوسيع محتواها واستيعاب عناصر بصرية إضافية. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | دمج كتلة WebP جديدة في الصورة، لتعزيز محتواها وتسهيل معالجة متقدمة للصورة. |
| [clearBlocks()](#clearBlocks--) | مسح جميع كتل WebP الموجودة من الصورة، لتوفير مساحة نظيفة للتعديلات أو الإضافات اللاحقة. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | إدراج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا في تسلسل الكتل. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | إزالة كتلة WebP المحددة من الصورة، مما يسهل إدارة بنية بيانات الصورة بكفاءة. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | تدوير الصورة حول مركزها بزاوية محددة، مع تغيير حجمها بشكل متناسب وتطبيق معلمات لون الخلفية المحددة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | تغيير حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | ضبط عرض الصورة بشكل متناسب مع الحفاظ على نسبة أبعادها. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | ضبط ارتفاع الصورة بشكل متناسب، مع الحفاظ على نسبة أبعادها لضمان تغيير حجم ثابت. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | تطبيق التدوير أو القلب أو كلا العمليتين حصريًا على الإطار النشط داخل الصورة. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | إجراء التمويه على الصورة الحالية لتقليل تدرجات اللون وتحسين جودة العرض. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة باستخدام منطقة مستطيلة محددة، مع إزالة الأجزاء غير المرغوبة مع الحفاظ على المحتوى المطلوب. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قص الصورة عن طريق تطبيق إزاحات إلى اليسار واليمين والأعلى والأسفل، لتحديد منطقة اهتمام داخل الصورة بفعالية. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | إجراء التحويل إلى ثنائي على الصورة باستخدام قيمة عتبة محددة مسبقًا، وتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة بناءً على شدة الإضاءة مقارنة بالعتبة. |
| [binarizeOtsu()](#binarizeOtsu--) | إجراء التحويل إلى ثنائي على الصورة باستخدام طريقة عتبة أوتسو، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على مخطط الصورة. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | تطبيق التحويل إلى ثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة. |
| [grayscale()](#grayscale--) | تطبيق التحويل إلى ثنائي على الصورة باستخدام خوارزمية العتبة التكيفية لبرايدلي مع عتبة الصورة المتكاملة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تطبيق تصحيح جاما على الصورة، مع تعديل شدة البكسلات لتحقيق السطوع وتوازن الألوان المطلوبين. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | إجراء تصحيح جاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يتيح تعديلات دقيقة لتوازن الألوان والتباين. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | تنفيذ تعديل `brightness` للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تحسين التباين في [Image](../../com.aspose.imaging/image)، مع تضخيم الفروق بين المناطق الفاتحة والداكنة. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | تصفية المحتوى داخل المستطيل المحدد، وتطبيق مرشح معالجة صورة مخصص لتعزيز أو تعديل المنطقة المختارة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | تغيير حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة العرض إلى الارتفاع وسلوك التحجيم. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// تحميل صورة WebP من ملف.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // احفظ إلى PNG
    // لاحظ أن الإطار النشط فقط سيتم تخزينه كـ PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


إنشاء نسخة جديدة من فئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مُهيأة من مصدر تدفق مُقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من التدفقات بسلاسة، مما يتيح معالجة فعّالة وتعديل بيانات صورة WebP داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | صورة WebP من التدفق. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


إنشاء نسخة جديدة من فئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام تدفق وخيارات تحميل محددة، لتسهيل معالجة مرنة لبيانات صورة WebP. دمج هذا المُنشئ لتهيئة كائنات صورة WebP من التدفقات بسلاسة مع تخصيص معلمات التحميل حسب الحاجة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | صورة WebP من التدفق. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


إنشاء نسخة جديدة من فئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مُهيأة من مصدر ملف مُقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من الملفات بسلاسة، مما يبسط عملية تحميل وتعديل بيانات صورة WebP داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار | java.lang.String | مسار ملف صورة WebP |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


إنشاء نسخة جديدة من فئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام ملف وخيارات تحميل محددة، لتسهيل معالجة مرنة لبيانات صورة WebP. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من الملفات بسلاسة مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مسار | java.lang.String | مسار ملف صورة WebP |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


إنشاء نسخة جديدة من فئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مُهيأة من كائن rasterImage مُقدم. يتيح هذا المُنشئ تحويل الصور النقطية إلى تنسيق WebP بسلاسة، مما يتيح معالجة فعّالة وتعديل بيانات الصورة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام كائن rasterImage وخيارات التحميل المحددة، مما يتيح معالجة مرنة لبيانات الصورة. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP بسلاسة من صور raster مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة بأبعاد العرض والارتفاع المحددة. يتيح هذا المُنشئ إنشاء صور WebP فارغة، مما يوفر أساسًا للتلاعب اللاحق بالصور وتوليد المحتوى داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة |
| height | int | ارتفاع الصورة. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | الخيارات. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة وخيارات تحميل محددة. يتيح هذا المُنشئ تهيئة صور WebP بمعلمات تحميل قابلة للتخصيص، مما يوفر مرونة في إنشاء الصور وتعديلها داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة |
| height | int | ارتفاع الصورة. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | الخيارات. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


استرجاع أو تعديل الخيارات المرتبطة بالخاصية المحددة، مما يتيح تخصيصًا دقيقًا للسلوك والإعدادات. استخدم هذه الخاصية للوصول السلس إلى المعلمات القابلة للتكوين وتعديلها، مما يسهل التحكم المتنوع والتحسين داخل وظائف تطبيقك.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


الوصول إلى كتل WebP داخل الصورة، مما يسمح بفحص تفصيلي أو تعديل للهيكل الكتلي الأساسي. استخدم هذه الخاصية لتحليل أو تعديل الكتل الفردية داخل بيانات صورة WebP، مما يسهل تقنيات معالجة الصور المتقدمة داخل تطبيقك.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه الوظيفة لتعزيز تجربة المستخدم، وتمكين وصول سلس إلى هياكل المستند الشاملة.

**Returns:**
int - عدد الصفحات.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، مع توفير معلومات حول التنسيق الذي تُخزن به الصورة. استخدم هذه الخاصية لتحديد تنسيق ملف الصورة، مما يسهل فحوص التوافق والمعالجة الخاصة بالتنسيق داخل تطبيقك.

**Returns:**
long - قيمة تنسيق الملف
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يدل على وجود معلومات الشفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة تشمل الشفافية، مما يتيح التعامل المناسب ومعالجة العمليات المتعلقة بالألفا داخل تطبيقك.

**Returns:**
منطقي - `true` إذا كان هناك قناة ألفا.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // إذا كان إطار TIFF النشط يحتوي على قناة ألفا، فسيُعتبر أن صورة TIFF بأكملها تحتوي على قناة ألفا.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// قد يبدو الإخراج هكذا:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, القنوات المستخدمة: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


إضافة صفحة جديدة إلى الصورة، مما يوسع محتواها ويستوعب عناصر بصرية إضافية. دمج هذه الطريقة لتسهيل إدارة الصفحات الديناميكية داخل تطبيقك، مما يتيح إنشاء وتوسيع مستندات أو صور متعددة الصفحات بسلاسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصفحة المراد إضافتها. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


دمج كتلة WebP جديدة في الصورة، مما يعزز محتواها ويسهل التلاعب المتقدم بالصور. دمج هذه الطريقة لتعزيز بنية وتعقيد بيانات صورة WebP داخل تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا في عرض الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | كتلة Webp المراد إضافتها. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// الإطار الافتراضي بالإضافة إلى 36 + 36 إطارًا إضافيًا.
createOptions.setAnimLoopCount(36 + 36 + 1);

// إنشاء صورة WebP بحجم 100×100 بكسل.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // الدائرة الأولى حمراء
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // الدائرة الثانية سوداء
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // زيادة زاوية الشكل القوسي الأحمر تدريجيًا.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // زيادة زاوية القوس الأسود تدريجيًا وإزالة القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // حفظ إلى ملف WebP
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


مسح جميع كتل WebP الموجودة من الصورة، مما يتيح بداية نظيفة للتعديلات أو الإضافات اللاحقة. استخدم هذه الطريقة لإعادة ضبط بنية الكتل داخل بيانات صورة WebP بفعالية، مما يضمن إدارة وتنظيم مثالي لمحتوى الصورة داخل تطبيقك.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


إدراج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا في تسلسل الكتل. دمج هذه الطريقة لتضمين كتل WebP إضافية بسلاسة في بنية بيانات الصورة، مما يسهل معالجة الصور المتقدمة والتحسين داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | العنصر القائم على الصفر، الذي سيتم إدراج `block` فيه. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | كتلة Webp المراد إضافتها. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


إزالة كتلة WebP المحددة من الصورة، مما يسهل إدارة فعّالة لبنية بيانات الصورة. استخدم هذه الطريقة لتبسيط سير عمل معالجة الصور عن طريق حذف الكتل أو المكونات غير الضرورية داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | الكتلة المراد إزالتها. |

--------------------

ملاحظة: لا تنسَ استدعاء Dispose للـ `block` إذا لم تقم بإضافته إلى WebPImage آخر. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


تدوير الصورة حول مركزها بزاوية محددة، مع تغيير حجمها بشكل متناسب وتطبيق معلمات لون الخلفية المحددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحولات دقيقة بألوان خلفية قابلة للتخصيص، مما يضمن عرضًا بصريًا مثاليًا داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور فقط `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


تغيير حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. دمج هذه الطريقة في سير عمل معالجة الصور لتكبير أو تصغير الصور ديناميكيًا لتلبية متطلبات العرض أو التخزين المختلفة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


قم بضبط عرض الصورة بشكل نسبي مع الحفاظ على نسبة الأبعاد. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتغيير حجم الصور ديناميكيًا بنسب متسقة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


قم بضبط ارتفاع الصورة بشكل نسبي، مع الحفاظ على نسبة الأبعاد لتغيير حجم متسق. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتغيير حجم الصور ديناميكيًا بنسب موحدة، مما يضمن عرضًا أو تخزينًا مثاليًا داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


طبق الدوران أو القلب أو كلا العمليتين حصريًا على الإطار النشط داخل الصورة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق معالجة دقيقة للإطارات الفردية، مما يعزز المرونة والتحكم في تحويلات الإطارات داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع تدوير القليب. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


قم بتنفيذ التمويه على الصورة الحالية لتقليل تدرج الألوان وتحسين الجودة البصرية. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق انتقالات أكثر سلاسة بين الألوان وتحسين المظهر العام للصورة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قم بقص الصورة باستخدام منطقة مستطيلة محددة، لإزالة الأجزاء غير المرغوب فيها مع الاحتفاظ بالمحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لاستخراج وتركيز مناطق معينة من الاهتمام داخل الصورة بدقة، مما يعزز الوضوح والتكوين لتطبيقات مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قم بقص الصورة عن طريق تطبيق إزاحات إلى اليسار واليمين والأعلى والأسفل، مما يحدد بفعالية منطقة اهتمام داخل الصورة. استخدم هذه الطريقة لاستخراج الأجزاء المطلوبة من الصورة ديناميكيًا مع تعديل تكوينها وتركيزها وفقًا لمتطلبات تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


قم بتنفيذ التحويل إلى صورة ثنائية على الصورة باستخدام قيمة عتبة محددة مسبقًا، لتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة بناءً على شدتها مقارنةً بالعتبة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتسهيل مهام التجزئة واستخراج الميزات، مما يعزز الدقة والكفاءة في التحليل اللاحق داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة (byte)255 لها، وإلا 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


قم بتنفيذ التحويل إلى صورة ثنائية على الصورة باستخدام طريقة عتبة أوتو، التي تحدد تلقائيًا قيمة العتبة المثلى بناءً على هيستوغرام الصورة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق تجزئة فعّالة واستخراج ميزات، مما يعزز دقة وموثوقية مهام تحليل الصور داخل تطبيقك.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


طبق التحويل إلى صورة ثنائية على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب عتبات محلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام المعالجة اللاحقة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |

### grayscale() {#grayscale--}
```
public void grayscale()
```


طبق التحويل إلى صورة ثنائية على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب عتبات محلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تجزئة قوية للمهام المعالجة اللاحقة داخل تطبيقك.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


طبق تصحيح غاما على الصورة، مع تعديل شدة البكسلات لتحقيق السطوع وتوازن اللون المطلوبين. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز الجودة البصرية وتحسين دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما للقنوات الحمراء والخضراء والزرقاء |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


قم بتنفيذ تصحيح غاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يسمح بتعديلات دقيقة لتوازن اللون والتباين. دمج هذه الطريقة في خط أنابيب معالجة الصور الخاص بك لتحقيق تحكم دقيق في عرض الألوان وتعزيز الوضوح البصري داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما للقناة الحمراء |
| gammaGreen | float | معامل غاما للقناة الخضراء |
| gammaBlue | float | معامل غاما للقناة الزرقاء |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


نفّذ تعديل `brightness` للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتعزيز الوضوح وتحسين الجودة البصرية للصور داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


عزز التباين في [Image](../../com.aspose.imaging/image)، مع تضخيم الفروق بين المناطق الفاتحة والداكنة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحسين الوضوح البصري وجودة الصورة العامة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


صَفِّ المحتوى داخل المستطيل المحدد، مطبقًا مرشح معالجة صور مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور الخاص بك لتحقيق تحسينات أو تحولات مستهدفة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // تطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بالكامل.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // تطبيق مرشح تنعيم ثنائي الجانب بحجم نواة 5 على الصورة بالكامل.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // تطبيق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // تطبيق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بالكامل.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // تطبيق مرشح حركة واينر بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // تطبيق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


قم بإعادة تحجيم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد ونسبة الأبعاد وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق عمليات تحجيم مخصصة تتناسب مع المتطلبات المحددة لتطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |

