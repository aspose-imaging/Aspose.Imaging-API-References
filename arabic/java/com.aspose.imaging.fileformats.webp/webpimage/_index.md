---
title: "WebPImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "معالجة صور WebP النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، باستخدام ميزاتها الحديثة لكل من الضغط غير الفاقد والضغط الفاقد، لضمان جودة صورة مثالية مع تقليل حجم الملفات."
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

معالجة صور WebP النقطية باستخدام واجهة برمجة التطبيقات الخاصة بنا، باستخدام ميزاتها الحديثة لكل من الضغط غير الفاقد والضغط الفاقد، لضمان جودة صورة مثالية مع تقليل حجم الملفات. التعامل بسلاسة مع صيغ الملفات الموسعة، والرسوم المتحركة، وقنوات ألفا، مع تحديث الأبعاد بسهولة، وإعادة التحجيم بشكل متناسب، والقص، والدوران، وتطبيق الفلاتر، وضبط معلمات الصورة، وتحويلها إلى صيغ صور أخرى لتحسين صور الويب المتعدد الاستخدامات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مهيأة من مصدر تدفق مُقدم. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام تدفق وخيارات تحميل محددة، مما يسهّل التعامل المتنوع مع بيانات صورة WebP. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مهيأة من مصدر ملف مُقدم. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام ملف وخيارات تحميل محددة، مما يسهّل التعامل المرن مع بيانات صورة WebP. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مهيأة من كائن rasterImage مُقدم. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام كائن rasterImage وخيارات تحميل محددة، مما يتيح التعامل المرن مع بيانات الصورة. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة بأبعاد عرض وارتفاع محددين. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | إنشاء نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة وخيارات تحميل محددة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOptions()](#getOptions--) | استرجاع أو تعديل الخيارات المرتبطة بالخاصية المحددة، مما يتيح تخصيصًا دقيقًا للسلوك والإعدادات. |
| [getPages()](#getPages--) | الوصول إلى كتل WebP داخل الصورة، مما يسمح بفحص تفصيلي أو تعديل للهيكل الأساسي للكتل. |
| [getPageCount()](#getPageCount--) | استرجاع العدد الإجمالي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. |
| [getFileFormat()](#getFileFormat--) | الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، مما يوفر معلومات حول التنسيق الذي تُخزن به الصورة. |
| [hasAlpha()](#hasAlpha--) | استرجاع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يدل على وجود معلومات شفافية. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | إضافة صفحة جديدة إلى الصورة، لتوسيع محتواها واستيعاب عناصر بصرية إضافية. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | دمج كتلة WebP جديدة في الصورة، لإثراء محتواها وتسهيل معالجة الصورة المتقدمة. |
| [clearBlocks()](#clearBlocks--) | مسح جميع كتل WebP الموجودة من الصورة، لتوفير قاعدة نظيفة للتعديلات أو الإضافات اللاحقة. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | إدراج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا في تسلسل الكتل. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | إزالة كتلة WebP المحددة من الصورة، لتسهيل إدارة فعّالة لهياكل بيانات الصورة. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | دوران الصورة حول مركزها بزاوية محددة، مع إعادة تحجيمها بشكل متناسب وتطبيق معلمات لون الخلفية المحددة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | إعادة تحجيم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | تعديل عرض الصورة بشكل متناسب مع الحفاظ على نسبة أبعادها. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | تعديل ارتفاع الصورة بشكل متناسب، مع الحفاظ على نسبة أبعادها لضمان إعادة تحجيم متسقة. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | تطبيق الدوران أو القلب أو كلا العمليتين حصريًا على الإطار النشط داخل الصورة. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | إجراء تمويه على الصورة الحالية لتقليل تدرج الألوان وتحسين الجودة البصرية. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قص الصورة باستخدام منطقة مستطيلة محددة، لإزالة الأجزاء غير المرغوب فيها مع الحفاظ على المحتوى المطلوب. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قم بقص الصورة عن طريق تطبيق إزاحات إلى اليسار واليمين والأعلى والأسفل، مما يتيح اختيار منطقة اهتمام داخل الصورة. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | قم بإجراء التحويل إلى صورة ثنائية على الصورة باستخدام قيمة عتبة محددة مسبقًا، وتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة بناءً على شدة إضاءة كل بكسل مقارنة بالعتبة. |
| [binarizeOtsu()](#binarizeOtsu--) | قم بالتحويل إلى صورة ثنائية على الصورة باستخدام طريقة عتبة أوتسو، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على هيستوغرام الصورة. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | طبق التحويل إلى صورة ثنائية على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. |
| [grayscale()](#grayscale--) | طبق التحويل إلى صورة ثنائية على الصورة باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | طبق تصحيح جاما على الصورة، مع تعديل شدة البكسلات لتحقيق السطوع وتوازن الألوان المطلوبين. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | قم بتطبيق تصحيح جاما على الصورة باستخدام معاملات منفصلة لقنوات الأحمر والأخضر والأزرق، مما يتيح ضبطًا دقيقًا لتوازن الألوان والتباين. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | نفّذ تعديل `brightness` للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | عزز التباين في [Image](../../com.aspose.imaging/image)، مع تضخيم الفروق بين المناطق الفاتحة والداكنة. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | قم بفلترة المحتوى داخل المستطيل المحدد، مع تطبيق مرشح معالجة صورة مخصص لتحسين أو تعديل المنطقة المختارة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | غيّر حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد، نسبة العرض إلى الارتفاع، وسلوك التحجيم. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// حمّل صورة WebP من ملف.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // حفظ إلى PNG
    // لاحظ أن الإطار النشط فقط سيُحفظ بصيغة PNG، لأن PNG ليس تنسيقًا متعدد الصفحات.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مبدئًا من مصدر تدفق مُقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من التدفقات بسلاسة، مما يتيح معالجة فعّالة وتعديل بيانات صورة WebP داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | صورة WebP من التدفق. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام تدفق وخيارات تحميل محددة، لتسهيل معالجة مرنة لبيانات صورة WebP. دمج هذا المُنشئ لتهيئة كائنات صورة WebP من التدفقات بسلاسة مع تخصيص معلمات التحميل حسب الحاجة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | صورة WebP من التدفق. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مبدئًا من مصدر ملف مُقدم. استخدم هذا المُنشئ لإنشاء كائنات صورة WebP مباشرةً من الملفات بسلاسة، مما يبسط عملية تحميل وتعديل بيانات صورة WebP داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | مسار ملف صورة WebP |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام ملف وخيارات تحميل محددة، لتسهيل معالجة مرنة لبيانات صورة WebP. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من الملفات بسلاسة مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | java.lang.String | مسار ملف صورة WebP |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage)، مبدئًا من كائن rasterImage مُقدم. يتيح هذا المُنشئ تحويل الصور النقطية إلى تنسيق WebP بسلاسة، مما يضمن معالجة فعّالة وتعديل بيانات الصورة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) باستخدام كائن rasterImage وخيارات تحميل محددة، لتوفير معالجة مرنة لبيانات الصورة. استخدم هذا المُنشئ لتهيئة كائنات صورة WebP من الصور النقطية بسلاسة مع تخصيص معلمات التحميل وفقًا لمتطلبات تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة النقطية. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة بأبعاد عرض وارتفاع محددة. يتيح هذا المُنشئ إنشاء صور WebP فارغة، مما يوفر أساسًا لمعالجة الصور لاحقًا وتوليد المحتوى داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة |
| الارتفاع | int | ارتفاع الصورة. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | الخيارات. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


أنشئ نسخة جديدة من الفئة [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) بصورة فارغة وخيارات تحميل محددة. يتيح هذا المُنشئ تهيئة صور WebP بمعلمات تحميل قابلة للتخصيص، مما يوفر مرونة في إنشاء وتعديل الصور داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض الصورة |
| الارتفاع | int | ارتفاع الصورة. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | الخيارات. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


استرجع أو عدّل الخيارات المرتبطة بالخاصية المحددة، مما يتيح تخصيصًا دقيقًا للسلوك والإعدادات. استخدم هذه الخاصية للوصول إلى المعلمات القابلة للتكوين وتعديلها بسلاسة، مما يسهل التحكم المتنوع والتحسين داخل وظائف تطبيقك.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


الوصول إلى كتل WebP داخل الصورة، مما يسمح بفحص مفصل أو تعديل للهيكل الكتلي الأساسي. استخدم هذه الخاصية لتحليل أو تعديل الكتل الفردية داخل بيانات صورة WebP، مما يدعم تقنيات معالجة صور متقدمة داخل تطبيقك.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع العدد الكلي للصفحات داخل المستند المحدد، مما يسهل التنقل الفعال وإدارة المحتوى متعدد الصفحات. دمج هذه الوظيفة لتعزيز تجربة المستخدم، وتمكين وصول سلس إلى هياكل المستند الشاملة.

**Returns:**
int - عدد الصفحات.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


الوصول إلى قيمة تنسيق الملف المرتبط بالصورة، والتي توفر معلومات حول التنسيق الذي تُخزن به الصورة. استخدم هذه الخاصية لتحديد تنسيق ملف الصورة، مما يسهل فحوص التوافق والمعالجة الخاصة بالتنسيق داخل تطبيقك.

**Returns:**
long - قيمة تنسيق الملف
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


استرجع ما إذا كانت الصورة تحتوي على قناة ألفا، مما يدل على وجود معلومات شفافية. استخدم هذه الخاصية لتحديد ما إذا كانت الصورة تشمل شفافية، مما يتيح معالجة مناسبة للعمليات المتعلقة بالألفا داخل تطبيقك.

**Returns:**
boolean - `true` إذا كانت هناك قناة ألفا.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // إذا كان الإطار النشط لملف TIFF يحتوي على قناة ألفا، فإن صورة TIFF بأكملها تُعتبر ذات قناة ألفا.
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


أضف صفحة جديدة إلى الصورة، مما يوسع محتواها ويستوعب عناصر بصرية إضافية. دمج هذه الطريقة لتسهيل إدارة الصفحات الديناميكية داخل تطبيقك، مما يتيح إنشاء وتوسيع مستندات أو صور متعددة الصفحات بسلاسة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصفحة التي سيتم إضافتها. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


أدمج كتلة WebP جديدة في الصورة، مما يثري محتواها ويسهل معالجة الصور المتقدمة. دمج هذه الطريقة لتعزيز بنية وتعقيد بيانات صورة WebP داخل تطبيقك بشكل ديناميكي، مما يتيح تحكمًا دقيقًا وتحسينًا في عرض الصورة.

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

    // زيادة زاوية القوس الأسود تدريجيًا ومحو القوس الأحمر.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // احفظ إلى ملف WebP
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


امسح جميع كتل WebP الموجودة من الصورة، مما يتيح صفحة نظيفة للتعديلات أو الإضافات اللاحقة. استخدم هذه الطريقة لإعادة ضبط بنية الكتل داخل بيانات صورة WebP بفعالية، وضمان إدارة وتنظيم مثالي لمحتوى الصورة داخل تطبيقك.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


أدرج كتلة WebP جديدة في الفهرس المحدد داخل الصورة، مما يتيح تحكمًا دقيقًا في تسلسل الكتل. دمج هذه الطريقة لإدراج كتل WebP إضافية بسلاسة في بنية بيانات الصورة، مما يسهل معالجة الصور المتقدمة وتحسينها داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | العنصر صفر‑الترقيم الذي سيتم إدراج `block` فيه. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | كتلة Webp المراد إضافتها. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


أزل كتلة WebP المحددة من الصورة، مما يسهل إدارة بنية بيانات الصورة بكفاءة. استخدم هذه الطريقة لتبسيط سير عمل معالجة الصور عن طريق إزالة الكتل أو المكونات غير الضرورية داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | الكتلة المراد إزالتها. |

--------------------

ملاحظة: لا تنسَ التخلص من `block` إذا لم تقم بإضافتها إلى WebPImage أخرى. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون ذلك مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام طريقة [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-)، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى طريقة [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) كمعامل ثانٍ.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


دوّر الصورة حول مركزها بزاوية محددة، مع تغيير حجمها بشكل متناسب وتطبيق معلمات لون الخلفية المحددة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تحولات دقيقة مع ألوان خلفية قابلة للتخصيص، وضمان عرض بصري مثالي داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تعديل وتُدور فقط محتويات الصورة ``. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


غيّر حجم الصورة، مع تعديل أبعادها مع الحفاظ على نسبة العرض إلى الارتفاع. دمج هذه الطريقة في سير عمل معالجة الصور لتكبير أو تصغير الصور ديناميكيًا لتناسب متطلبات العرض أو التخزين المختلفة داخل تطبيقك.

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

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


ضبط عرض الصورة بشكل متناسب مع الحفاظ على نسبة أبعادها. دمج هذه الطريقة في سير عمل معالجة الصور لتغيير حجم الصور ديناميكيًا بنسب ثابتة، وضمان عرض أو تخزين مثالي داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


ضبط ارتفاع الصورة بشكل متناسب، مع الحفاظ على نسبة أبعادها لتغيير حجم متسق. دمج هذه الطريقة في سير عمل معالجة الصور لتغيير حجم الصور ديناميكيًا بنسب موحدة، وضمان عرض أو تخزين مثالي داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


طبق الدوران أو القلب أو كلا العمليتين حصريًا على الإطار النشط داخل الصورة. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق تعديل دقيق للإطارات الفردية، مما يعزز المرونة والتحكم في تحولات الإطارات داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع الدوران والقلب. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


قم بعملية التمويه (dithering) على الصورة الحالية لتقليل تدرج الألوان وتحسين الجودة البصرية. دمج هذه الطريقة في سير عمل معالجة الصور لتحقيق انتقالات ألوان أكثر سلاسة وتحسين المظهر العام للصورة داخل تطبيقك.

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


قص الصورة باستخدام منطقة مستطيلة محددة، مع إزالة الأجزاء غير المرغوب فيها مع الحفاظ على المحتوى المطلوب. دمج هذه الطريقة في سير عمل معالجة الصور لاستخراج وتركيز دقيق على مناطق معينة داخل الصورة، مما يعزز الوضوح والتكوين لتطبيقات مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قص الصورة عن طريق تطبيق إزاحات من اليسار واليمين والأعلى والأسفل، لتحديد منطقة اهتمام داخل الصورة بفعالية. استخدم هذه الطريقة لاستخراج الأجزاء المطلوبة من الصورة ديناميكيًا مع تعديل تكوينها وتركيزها وفقًا لمتطلبات تطبيقك.

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


قم بعملية التثنائي (binarization) على الصورة باستخدام قيمة عتبة محددة مسبقًا، لتحويلها إلى صورة ثنائية حيث يتم تصنيف البكسلات كخلفية أو مقدمة بناءً على شدة إضاءةها مقارنة بالعتبة. دمج هذه الطريقة في سير عمل معالجة الصور لتسهيل مهام التقسيم واستخراج الميزات، مما يعزز دقة وكفاءة التحليل اللاحق داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة (byte)255 له، وإلا فستكون 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


قم بتنفيذ تحويل الصورة إلى ثنائية باستخدام طريقة عتبة أوتسو، مع تحديد قيمة العتبة المثلى تلقائيًا بناءً على مخطط ترددات الصورة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق تقسيم فعال واستخراج الميزات، مما يعزز دقة وموثوقية مهام تحليل الصور داخل تطبيقك.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


طبق تحويل الصورة إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب العتبات المحلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تقسيمًا قويًا للمهام اللاحقة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s بكسل متمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s بكسل متمركزة حول هذا البكسل. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


طبق تحويل الصورة إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة. تقوم هذه الطريقة بحساب العتبات المحلية ديناميكيًا بناءً على جوار الصورة، مما يعزز القدرة على التكيف مع ظروف الإضاءة المتغيرة ويضمن تقسيمًا قويًا للمهام اللاحقة داخل تطبيقك.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


طبق تصحيح غاما على الصورة، مع تعديل شدة البكسل لتحقيق السطوع وتوازن الألوان المطلوبين. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحسين الجودة البصرية وزيادة دقة التحليل أو مهام العرض اللاحقة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما لقنوات الأحمر والأخضر والأزرق |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


قم بتنفيذ تصحيح غاما على الصورة باستخدام معاملات فردية لقنوات الأحمر والأخضر والأزرق، مما يسمح بإجراء تعديلات دقيقة على توازن الألوان والتباين. دمج هذه الطريقة في خط أنابيب معالجة الصور الخاص بك لتحقيق تحكم دقيق في عرض الألوان وتعزيز الدقة البصرية داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما لقناة الأحمر |
| gammaGreen | float | معامل غاما لقناة الأخضر |
| gammaBlue | float | معامل غاما لقناة اللون الأزرق |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


نفّذ تعديل `brightness` للصورة، مما يسمح بتعديل مستويات الإضاءة العامة. دمج هذه الطريقة في سير عمل معالجة الصور لتعزيز الرؤية وتحسين الجودة البصرية للصور داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


حسّن التباين في [Image](../../com.aspose.imaging/image)، مع تضخيم الفروق بين المناطق الفاتحة والداكنة. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحسين الوضوح البصري وجودة الصورة العامة داخل تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


صفي المحتوى داخل المستطيل المحدد، مطبقًا مرشح معالجة صورة مخصص لتعزيز أو تعديل المنطقة المختارة. دمج هذه الطريقة في سير عمل تعديل الصور لتحقيق تحسينات أو تحويلات مستهدفة داخل تطبيقك.

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

    // طبق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // طبق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // طبق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // طبق مرشح واينر حركي بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // طبق مرشح شحذ بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
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


غيّر حجم الصورة وفقًا للإعدادات المحددة، مما يتيح تحكمًا دقيقًا في الأبعاد، نسبة العرض إلى الارتفاع، وسلوك التحجيم. دمج هذه الطريقة في سير عمل معالجة الصور الخاص بك لتحقيق عمليات تغيير حجم مخصصة تتناسب مع المتطلبات المحددة لتطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |

