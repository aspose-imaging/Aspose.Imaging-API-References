---
title: "DjvuImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تدعم فئة مستند DjVu تنسيق ملفات الرسومات وتسهّل الإدارة السلسة للمستندات والكتب الممسوحة ضوئياً من خلال دمج النص والرسومات والصور والملفات الفوتوغرافية في تنسيق واحد."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

تدعم فئة مستند DjVu تنسيق ملفات الرسومات وتسهّل الإدارة السلسة للمستندات والكتب الممسوحة ضوئياً، من خلال دمج النص والرسومات والصور والملفات الفوتوغرافية في تنسيق واحد. تدعم عمليات الصفحات المتعددة، حيث يمكنك الوصول بفعالية إلى معرفات المستند الفريدة، وعدّ الصفحات، وتعيين الصفحات النشطة، واسترجاع صفحات المستند المحددة. مع ميزات تغيير الحجم، والدوران، وإضافة النقاط (dithering)، والقص، وتحويل إلى تدرج الرمادي، وتصحيحات غاما، والتعديلات، وتطبيق الفلاتر، تمكّن هذه الفئة من التلاعب الدقيق وتعزيز صور DjVu لتلبية احتياجات التطبيقات المتنوعة بسهولة ودقة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | ابدأ العمل مع صور DjVu بإنشاء نسخة جديدة من فئة [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) باستخدام معامل Stream. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | ابدأ العمل مع صور DjVu بسلاسة باستخدام هذا المُنشئ، الذي يُنشئ نسخة جديدة من فئة [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) باستخدام معاملَي Stream وLoadOptions. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | ابدأ العمل مع صور DjVu بسلاسة باستخدام هذا المُنشئ، الذي يُنشئ نسخة جديدة من فئة [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) باستخدام معاملَي Stream وLoadOptions. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | يحدث عندما تتغير قيمة الخاصية. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | حمّل مستند DjVu الخاص بك باستخدام هذه الطريقة. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | يحمّل المستند. |
| [getIdentifier()](#getIdentifier--) | يحصل على المعرف الفريد للمستند |
| [getPageCount()](#getPageCount--) | استرجع العدد الإجمالي للصفحات في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. |
| [getPages()](#getPages--) | الوصول إلى الصفحات الفردية في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. |
| [getDjvuPages()](#getDjvuPages--) | استرجع بسرعة جميع الصفحات الموجودة داخل مستند DjVu الخاص بك باستخدام هذه الخاصية. |
| [getActivePage()](#getActivePage--) | تنقل عبر مستند DjVu الخاص بك عن طريق الوصول إلى الصفحة النشطة حالياً أو تعيينها باستخدام هذه الخاصية. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | تنقل عبر مستند DjVu الخاص بك عن طريق الوصول إلى الصفحة النشطة حالياً أو تعيينها باستخدام هذه الخاصية. |
| [getFirstPage()](#getFirstPage--) | الوصول إلى الصفحة الأولى من مستند DjVu الخاص بك باستخدام هذه الخاصية. |
| [getLastPage()](#getLastPage--) | استرجع الصفحة الأخيرة من مستند DjVu الخاص بك باستخدام هذه الخاصية. |
| [getNextPage()](#getNextPage--) | تنقل عبر مستند DjVu الخاص بك عن طريق الوصول إلى الصفحة التالية باستخدام هذه الخاصية المريحة. |
| [getPreviousPage()](#getPreviousPage--) | تحرك بسرعة إلى الخلف في مهام عرض أو معالجة مستند DjVu الخاص بك عن طريق الوصول إلى الصفحة السابقة باستخدام هذه الخاصية المريحة. |
| [getFileFormat()](#getFileFormat--) | احصل على معلومات تنسيق الملف المرتبط بملف صورة DjVu الخاص بك. |
| [hasAlpha()](#hasAlpha--) | حدد بسرعة ما إذا كان ملف صورة DjVu الخاص بك يحتوي على قناة ألفا. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | قم بتدوير الصورة حول مركزها باستخدام طريقة Rotate من الفئة RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | قم بتغيير حجم الصورة باستخدام طريقة \`Resize\`، مما يوفر طريقة بسيطة وفعّالة لضبط أبعاد صورك وفقًا لمتطلباتك. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | توفر طريقة \`ResizeWidthProportionally\` حلاً مريحًا لضبط عرض صورتك مع الحفاظ على نسبة أبعادها. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | تتيح طريقة \`ResizeHeightProportionally\` لك ضبط ارتفاع صورتك مع الحفاظ على نسبة أبعادها. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | توفر طريقة \`RotateFlip\` خيارات معالجة متعددة لصورتك، مما يسمح لك بتدويرها أو عكسها أو تنفيذ كلا العمليتين على الإطار النشط بشكل مستقل. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | تطبق الدالة \"Dither\" تأثير التدرج على صورتك، مما يعزز جودتها البصرية عن طريق تقليل الخطوط المتدرجة وتحسين انتقالات الألوان. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | \"Crop\" تقص صورتك للتركيز على تفاصيل محددة أو لإزالة العناصر غير المرغوب فيها، مما يعزز تكوينها وتأثيرها البصري. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | تتيح لك خاصية Crop with shifts ضبط موضع وأبعاد المنطقة المقصوصة داخل الصورة بدقة. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | تقوم عملية التثنائي باستخدام عتبة محددة مسبقًا بتبسيط الصور المعقدة إلى تمثيلات ثنائية، حيث يتم تصنيف البكسلات إما كالسوداء أو الأبيض بناءً على شدة اللون مقارنةً بقيمة العتبة المحددة. |
| [binarizeOtsu()](#binarizeOtsu--) | التثنائي باستخدام عتبة Otsu هي تقنية تحسب تلقائيًا قيمة عتبة مثالية بناءً على مخطط الصورة. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | التثنائي باستخدام خوارزمية العتبة التكيفية لبرادلي مع عتبة الصورة المتكاملة هي طريقة تحسب عتبة محلية لكل بكسل بناءً على الجوار المحلي. |
| [grayscale()](#grayscale--) | تحويل التدرج الرمادي يحول الصورة إلى تمثيل أبيض وأسود، حيث يتم تمثيل شدة كل بكسل بقيمة واحدة تتراوح بين الأسود والأبيض. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | تصحيح جاما، خاصةً لقنوات الأحمر والأخضر والأزرق، يتضمن ضبط سطوع كل مكوّن لوني بشكل منفصل. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | يتم تطبيق تصحيح جاما على الصورة مع معلمات قابلة للتخصيص لقنوات الأحمر والأخضر والأزرق، مما يسمح بضبط دقيق لتوازن الألوان والسطوع. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | ضبط `brightness` لصورة باستخدام معلمة محددة، مما يوفر التحكم في مستويات الإضاءة للحصول على وضوح بصري مثالي. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | تحسين تباين [Image](../../com.aspose.imaging/image) لتحسين الوضوح البصري وإبراز التفاصيل باستخدام هذه الطريقة، التي تضبط الفرق في السطوع بين المناطق الفاتحة والداكنة. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | تطبيق الفلاتر على منطقة مستطيلة محددة داخل الصورة لتحسين أو تعديل مظهرها. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | تغيير حجم الصورة إلى العرض والارتفاع المحددين مع تطبيق إعدادات إضافية حسب الحاجة. |
| [cacheData()](#cacheData--) | تخزين البيانات مؤقتًا بشكل خاص لتحسين الأداء وتقليل الحاجة إلى استرجاع البيانات المتكرر من المصادر الخارجية. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من دفق ملف.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // حفظ كل صفحة كصورة PNG منفصلة.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // إنشاء اسم ملف بناءً على رقم الصفحة.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


ابدأ العمل مع صور DjVu عن طريق تهيئة نسخة جديدة من الفئة [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) باستخدام معلمة Stream. مثالي للمطورين الذين يرغبون في دمج سلس لمعالجة صور DjVu في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


ابدأ العمل مع صور DjVu بسلاسة باستخدام هذا المُنشئ، الذي يهيئ نسخة جديدة من الفئة [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) باستخدام معلمات Stream وLoadOptions. مثالي للمطورين الذين يرغبون في تحكم دقيق في خيارات تحميل صور DjVu مع الحفاظ على البساطة والكفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | الدفق للتحميل منه. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


ابدأ العمل مع صور DjVu بسلاسة باستخدام هذا المُنشئ، الذي يهيئ نسخة جديدة من الفئة [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) باستخدام معلمات Stream وLoadOptions. مثالي للمطورين الذين يرغبون في تحكم دقيق في خيارات تحميل صور DjVu مع الحفاظ على البساطة والكفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | com.aspose.ms.System.IO.Stream | الدفق للتحميل منه. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


يحدث عندما تتغير قيمة الخاصية.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


حمّل مستند DjVu الخاص بك باستخدام هذه الطريقة. سهل عمليتك من خلال الوصول السريع واستيراد ملفات DjVu إلى تطبيقك.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


يحمّل المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


يحصل على المعرف الفريد للمستند

**Returns:**
int - المعرف.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع العدد الإجمالي للصفحات في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. مثالي لتقييم حجم مستندك أو كتابك المخزن بصيغة DjVu بسرعة. حسّن كفاءة سير العمل لديك بمعلومات دقيقة عن عدد الصفحات.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public Image[] getPages()
```


الوصول إلى الصفحات الفردية في مجموعة صور DjVu الخاصة بك باستخدام هذه الخاصية. بسط التنقل والتعامل مع مستندك أو كتابك المخزن بصيغة DjVu من خلال الوصول إلى كل صفحة مباشرة. حسّن كفاءة سير العمل لديك باسترجاع الصفحات بسهولة.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من دفق ملف.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // حفظ كل صفحة كصورة PNG منفصلة.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // إنشاء اسم ملف بناءً على رقم الصفحة.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


استرجع بسرعة جميع الصفحات الموجودة في مستند DjVu الخاص بك باستخدام هذه الخاصية. بسط سير عمل معالجة المستندات من خلال الوصول السهل وإدارة الصفحات الفردية داخل ملفات DjVu. حسّن الكفاءة وسهّل مهامك باسترجاع الصفحات بسهولة.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - الصفحات.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


تصفح مستند DjVu الخاص بك من خلال الوصول إلى الصفحة النشطة حاليًا أو تعيينها باستخدام هذه الخاصية. انتقل بسلاسة بين الصفحات للتركيز على محتوى محدد وتعزيز تجربة عرض المستند.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من دفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد الصفحات: 2
//رقم الصفحة النشطة:    1
//رقم الصفحة الأولى:     1
//رقم الصفحة الأخيرة:      2
//--------------------------------------------------
//رقم الصفحة:     1
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
//--------------------------------------------------
//رقم الصفحة:     2
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


تصفح مستند DjVu الخاص بك من خلال الوصول إلى الصفحة النشطة حاليًا أو تعيينها باستخدام هذه الخاصية. انتقل بسلاسة بين الصفحات للتركيز على محتوى محدد وتعزيز تجربة عرض المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | الصفحة النشطة. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


الوصول إلى الصفحة الأولى من مستند DjVu الخاص بك باستخدام هذه الخاصية. استرجع بسرعة الصفحة الأولية لبدء عرض أو معالجة المستند بكفاءة.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من دفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد الصفحات: 2
//رقم الصفحة النشطة:    1
//رقم الصفحة الأولى:     1
//رقم الصفحة الأخيرة:      2
//--------------------------------------------------
//رقم الصفحة:     1
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
//--------------------------------------------------
//رقم الصفحة:     2
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


استرجع الصفحة الأخيرة من مستند DjVu الخاص بك باستخدام هذه الخاصية. وصول سريع إلى الصفحة النهائية للعرض أو المعالجة بسهولة.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة DJVU من دفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//قد يبدو الإخراج هكذا:
//إجمالي عدد الصفحات: 2
//رقم الصفحة النشطة:    1
//رقم الصفحة الأولى:     1
//رقم الصفحة الأخيرة:      2
//--------------------------------------------------
//رقم الصفحة:     1
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
//--------------------------------------------------
//رقم الصفحة:     2
//حجم الصفحة:       { Width = 2481, Height = 3508}
//تنسيق الصفحة الخام: RgbIndexed1Bpp, القنوات المستخدمة: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


تصفح مستند DjVu الخاص بك من خلال الوصول إلى الصفحة التالية باستخدام هذه الخاصية المريحة. تحرك بسرعة إلى الأمام في مهام عرض أو معالجة المستند.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


تحرك بسرعة إلى الخلف في مهام عرض أو معالجة مستند DjVu الخاص بك من خلال الوصول إلى الصفحة السابقة باستخدام هذه الخاصية المريحة. تنقل بكفاءة عبر المستند بسهولة.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


احصل على معلومات تنسيق الملف المرتبط بملف صورة DjVu الخاص بك. حدد بسرعة تنسيق ملفك لتكامل سلس في سير عملك.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


حدد بسرعة ما إذا كان ملف صورة DjVu الخاص بك يحتوي على قناة ألفا. بسط سير عملك من خلال التحقق من وجود معلومات الشفافية في صورك.

**Returns:**
boolean - يحتوي على قناة ألفا.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


قم بتدوير الصورة حول مركزها باستخدام طريقة Rotate من فئة RasterCachedMultipageImage. تتيح لك هذه الميزة المريحة تعديل اتجاه الصور بسهولة مع الحفاظ على موقع مركزها، مما يعزز قدراتك على معالجة الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تعديل وتُدور فقط محتويات الصورة ``. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


قم بتغيير حجم الصورة باستخدام طريقة \`Resize\`، مما يوفر طريقة بسيطة وفعّالة لضبط أبعاد صورك وفقًا لمتطلباتك. تمكّنك هذه الوظيفة المتعددة الاستخدامات من تكبير أو تصغير الصور بسهولة إلى الحجم المطلوب، مما يعزز قابلية استخدامها عبر مختلف المنصات والتطبيقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
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


توفر طريقة \`ResizeWidthProportionally\` حلاً مريحًا لضبط عرض صورتك مع الحفاظ على نسبة الأبعاد. من خلال تعديل العرض بشكل متناسب، يمكنك ضمان بقاء صورك جذابة بصريًا ومتسقة عبر مختلف الأجهزة وأحجام الشاشات، مما يعزز مرونتها وقابليتها للاستخدام في سياقات متعددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
يحمّل هذا المثال صورة DJVU ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد العرض فقط، ويتم حساب الارتفاع تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


تتيح طريقة \`ResizeHeightProportionally\` ضبط ارتفاع صورتك مع الحفاظ على نسبة الأبعاد. يضمن ذلك بقاء الصورة تحتفظ بنسبها، مما يمنع التشويه ويحافظ على سلامتها البصرية. سواءً كنت تُحسّن الصور لصفحات الويب أو التطبيقات المحمولة أو الوسائط المطبوعة، فإن هذه الطريقة تضمن أن تبدو صورك بأفضل شكل عبر مختلف المنصات والأجهزة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
يحمّل هذا المثال صورة DJVU ويعيد تحجيمها بشكل متناسب باستخدام طرق تحجيم مختلفة. يتم تحديد الارتفاع فقط، ويتم حساب العرض تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


توفر طريقة \`RotateFlip\` خيارات معالجة متعددة لصورتك، مما يتيح لك تدويرها أو قلبها أو تنفيذ العمليتين معًا على الإطار النشط بشكل مستقل. سواءً كنت تعدّل الصور، أو تنشئ رسومات، أو تحسّن الفن الرقمي، فإن هذه الطريقة توفر تحكمًا دقيقًا في اتجاه وتكوين صورك، مما يضمن تحقيق رؤيتك الإبداعية بسهولة وكفاءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع التدوير والقلب. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // قم بالدوران، القليب وحفظ إلى ملف الإخراج.
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


تطبق الدالة \"Dither\" تأثير التدرج المتناثر على صورتك، مما يعزز جودتها البصرية عن طريق تقليل الخطوط المتدرجة وتحسين انتقالات الألوان. سواءً كنت تعمل على فن رقمي أو تصوير فوتوغرافي أو مشاريع تصميم جرافيكي، تضيف هذه الميزة لمسة احترافية لصورك، تجعلها تبدو أكثر سلاسة وتفصيلًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // قم بتنفيذ تدرّج العتبة باستخدام لوحة ألوان 4‑بت تحتوي على 16 لونًا.
    // كلما زاد عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان ذات 1‑بت، 4‑بت و8‑بت فقط هي المدعومة حاليًا.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // قم بتنفيذ تدرّج Floyd باستخدام لوحة ألوان 1‑بت تحتوي فقط على لونين - الأسود والأبيض.
    // كلما زاد عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان ذات 1‑بت، 4‑بت و8‑بت فقط هي المدعومة حاليًا.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


\"Crop\" تقص صورتك لتُركز على تفاصيل محددة أو لإزالة العناصر غير المرغوب فيها، مما يعزز تكوينها وتأثيرها البصري. سواءً كنت تعدّل الصور لوسائل التواصل الاجتماعي، أو تنشئ لافتات مواقع ويب، أو تصمم مواد مطبوعة، تساعدك هذه الأداة على تحسين صورك بدقة ووضوح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |


**Example: The following example crops a DJVU image.**
المثال التالي يقتطع صورة DJVU. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


يتيح لك الاقتصاص مع الإزاحات ضبط موضع وأبعاد منطقة القص داخل الصورة بدقة. هذه الميزة لا تقدر بثمن لتصحيح التكوينات، ومحاذاة العناصر، وتأكيد نقاط التركيز في مرئياتك. من خلال دمج الإزاحات في عملية الاقتصاص، يمكنك تحقيق دقة بكسل مثالية وضبط إطار صورك بسهولة.

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


يُبسّط التحويل إلى ثنائي باستخدام عتبة محددة مسبقًا الصور المعقدة إلى تمثيلات ثنائية، حيث تُصنّف البكسلات إما كالسوداء أو الأبيض بناءً على شدة إضاءةها مقارنةً بقيمة العتبة المحددة. تُستخدم هذه التقنية عادةً في معالجة الصور لتعزيز الوضوح، وتبسيط التحليل، وإعداد الصور لمراحل معالجة إضافية مثل التعرف الضوئي على الأحرف (OCR). من خلال تطبيق عتبة ثابتة، يمكنك تحويل صور التدرج الرمادي إلى صيغة ثنائية بسرعة، مما يجعلها أسهل في الفهم واستخراج المعلومات ذات المعنى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة لبكسل أكبر من العتبة، سيتم تعيين القيمة 255 له، وإلا 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
المثال التالي يحول صورة DJVU إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // قم بتحويل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
    // إذا كانت القيمة الرمادية المقابلة للبكسل أكبر من 127، سيتم تعيين القيمة 255 له، وإلا ستكون 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


يُعد التحويل إلى ثنائي باستخدام عتبة أوتسو تقنية تحسب تلقائيًا قيمة عتبة مثالية استنادًا إلى هيستوغرام الصورة. تفصل الصورة إلى خلفية ومقدمة عن طريق تقليل التباين داخل الفئات. تُستخدم طريقة أوتسو على نطاق واسع لتقسيم الصور إلى صيغة ثنائية، خاصةً عندما يكون توزيع شدة البكسلات ثنائي أو متعدد القمم. هذا النهج مفيد لمهام مثل اكتشاف الكائنات، وتقسيم الصور، واستخراج الميزات، حيث يكون التحديد الدقيق بين المقدمة والخلفية أمرًا حاسمًا.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
المثال التالي يحول صورة DJVU إلى ثنائية باستخدام عتبة أوتسو. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // قم بتحويل الصورة إلى ثنائية باستخدام عتبة أوتسو.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


يستخدم التحويل إلى ثنائي باستخدام خوارزمية عتبة برادلي التكيفية مع عتبة الصورة المتكاملة طريقة تحسب عتبة محلية لكل بكسل بناءً على الجوار المحلي. تتكيف مع تغيرات الإضاءة عبر الصورة، مما يجعلها مناسبة للصور ذات الإضاءة غير المتساوية. من خلال حساب العتبة باستخدام الصور المتكاملة، تتعامل بكفاءة مع أجواء واسعة، مما يجعلها قابلة للتطبيق في التطبيقات الفورية. تُستَخدم هذه التقنية عادةً في معالجة المستندات، والتعرف الضوئي على الأحرف (OCR)، ومهام تقسيم الصور حيث يكون التحويل إلى ثنائي الدقيق ضروريًا للتحليل اللاحق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s بكسل متمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s بكسل متمركزة حول هذا البكسل. |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
المثال التالي يحول صورة DJVU إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية مع حجم النافذة المحدد. الصور الثنائية تحتوي فقط على لونين - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // حوّل الصورة إلى ثنائية بفارق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


تحويل الصورة إلى تدرج الرمادي يحولها إلى تمثيل أبيض-أسود، حيث يُمثَّل شدة كل بكسل بقيمة واحدة تتراوح بين الأسود والأبيض. تُزيل هذه العملية معلومات اللون، مما ينتج صورة أحادية اللون. تُستخدم صور التدرج الرمادي عادةً في التطبيقات التي لا تكون فيها الألوان ضرورية أو حيث يُفضَّل البساطة، مثل مسح المستندات، والطباعة، وبعض أنواع تحليل الصور.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
المثال التالي يحول صورة DJVU ملونة إلى تمثيلها بتدرج الرمادي. تتكون صور التدرج الرمادي حصريًا من درجات اللون الرمادي وتحمل فقط معلومات الشدة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


تصحيح جاما، خاصةً لقنوات الأحمر والأخضر والأزرق، يتضمن تعديل سطوع كل مكوّن لوني بشكل منفصل. من خلال تطبيق معاملات جاما مختلفة على قنوات RGB، يمكنك ضبط السطوع والتباين العام للصورة بدقة. تضمن هذه التقنية تمثيلًا لونيًا دقيقًا وتحسين جودة الصورة البصرية عبر مختلف أجهزة العرض.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما لقنوات الأحمر والأخضر والأزرق |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // تعيين معامل غاما لقنوات الأحمر والأخضر والأزرق.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


يُطبق تصحيح الجاما على الصورة مع معلمات قابلة للتخصيص لقنوات الأحمر والأخضر والأزرق، مما يسمح بضبط دقيق لتوازن الألوان والسطوع. تعزز هذه الطريقة جودة الصورة من خلال تحسين تمثيل الألوان، وضمان عرض مثالي عبر مختلف أجهزة العرض. تحسين قيم الجاما للقنوات الفردية يحسن توازن الألوان والجاذبية البصرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما لقناة الأحمر |
| gammaGreen | float | معامل غاما لقناة الأخضر |
| gammaBlue | float | معامل غاما لقناة اللون الأزرق |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // تعيين معاملات غاما الفردية لقنوات الأحمر والأخضر والأزرق.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


قم بضبط `brightness` للصورة باستخدام معلمة محددة، مما يوفر تحكمًا في مستويات الإضاءة لتحقيق وضوح بصري مثالي. تعزز هذه الطريقة أو تقلل السطوع العام للصورة، مما يسمح بتعديلات دقيقة لتحقيق التأثيرات الضوئية المطلوبة. من خلال تعديل السطوع، يمكن للمستخدمين تحسين وضوح الصورة وتعزيز إعادة إنتاج التفاصيل لتجربة مشاهدة محسنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


عزّز تباين [Image](../../com.aspose.imaging/image) لتحسين الوضوح البصري وإبراز التفاصيل باستخدام هذه الطريقة، التي تعدل الفرق في السطوع بين المناطق الفاتحة والداكنة. من خلال ضبط مستويات التباين بدقة، يمكن للمستخدمين الحصول على صور أكثر حيوية وتأثيرًا، مما يعزز جودة الصورة العامة ويزيد من وضوح التفاصيل. يساعد هذا التعديل على إظهار الفروق الدقيقة في اللون والملمس، مما ينتج صورًا أكثر ديناميكية وجاذبية بصريًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // حدد قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


طبق فلاتر على منطقة مستطيلة محددة داخل الصورة لتعزيز أو تعديل مظهرها. من خلال استهداف مناطق معينة، تسمح هذه الطريقة بإجراء تعديلات دقيقة، مثل التمويه أو الشحذ أو تطبيق تأثيرات فنية، لتحقيق النتائج البصرية المطلوبة. يتيح ضبط الفلاتر على المناطق المختارة للمستخدمين تخصيص جمالية الصورة، تحسين الوضوح، وإنشاء تأثيرات فنية تتناسب مع تفضيلاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // طبق مرشح متوسط بحجم مستطيل 5 على الصورة بأكملها.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // طبق مرشح تمهيد ثنائي الجانب بحجم نواة 5 على الصورة بأكملها.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // طبق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // طبق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بأكملها.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // طبق مرشح واينر حركي بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بأكملها.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // طبق مرشح شحذ بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بأكملها.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


قم بتغيير حجم الصورة إلى العرض والارتفاع المحددين مع تطبيق الإعدادات الإضافية حسب الحاجة. تمكّن هذه الطريقة المستخدمين من ضبط أبعاد الصورة مع الحفاظ على الخصائص المطلوبة مثل نسبة العرض إلى الارتفاع، جودة الصورة، وإعدادات الضغط. من خلال توفير مرونة في خيارات تغيير الحجم، يمكن للمستخدمين تعديل الصورة لتتناسب مع المتطلبات المحددة وتحسين مظهرها لتطبيقات ومنصات مختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة النسبية الموزونة والمختلطة وتداخل lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// المرشح المستطيل الصغير
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// عدد الألوان في لوحة الألوان.
resizeSettings.setEntriesCount(256);

// لم يتم استخدام تقليل ألوان.
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// الطريقة الإقليدية
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات متكيفة.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // حفظ إلى PNG
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


قم بتخزين البيانات بشكل خاص لتحسين الأداء وتقليل الحاجة إلى استرجاع البيانات المتكرر من المصادر الخارجية. يساعد هذا النهج أيضًا في الحفاظ على الموارد، خاصةً في السيناريوهات التي يكون فيها الوصول إلى البيانات متكررًا أو الموارد محدودة.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// تحميل صورة من ملف DJVU.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // هذه العملية تخزن جميع الصفحات مؤقتًا بحيث لن يتم تحميل أي بيانات إضافية من تدفق البيانات الأساسي.
    image.cacheData();

    // أو يمكنك تخزين الصفحات مؤقتًا بشكل فردي.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

