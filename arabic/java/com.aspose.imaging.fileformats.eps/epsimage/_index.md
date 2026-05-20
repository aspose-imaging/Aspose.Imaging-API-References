---
title: "EpsImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات لدعم تنسيق ملف صورة Encapsulated PostScript EPS قدرات قوية لمعالجة التركيبات التي تشمل النص والرسومات والصور."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

توفر واجهة برمجة التطبيقات لدعم تنسيق ملف صورة Encapsulated PostScript (EPS) قدرات قوية لمعالجة التركيبات التي تشمل النص والرسومات والصور. مع ميزات مثل معالجة صور المعاينة بتنسيق bitmap، وقلب الاتجاه، واسترجاع صندوق الحدود لتحديد حدود الرسوم التوضيحية، وإعادة التحجيم، وتدوير الصور، وإضافة صور المعاينة. تضمن هذه الواجهة معالجة سلسة وتكامل ملفات EPS في تطبيقات متعددة بدقة وتنوع.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | احصل على عدد صور المعاينة المتاحة بسهولة. |
| [getPreviewImages()](#getPreviewImages--) | استرجع صور المعاينة المرتبطة بملفك. |
| [getFileFormat()](#getFileFormat--) | احصل على تنسيق ملف الصورة باستخدام هذه الخاصية. |
| [getEpsType()](#getEpsType--) | احصل على قيمة النوع الفرعي لصورة EPS الخاصة بك وفسّرها، مما يبسط سير العمل ويعزز التوافق عبر المنصات. |
| [hasRasterPreview()](#hasRasterPreview--) | اكتشف وجود معاينة نقطية بسهولة باستخدام هذه الخاصية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | احصل على عمق البت الدقيق للصورة بسهولة باستخدام هذه الخاصية. |
| [getWidthF()](#getWidthF--) | استرجع عرض الصورة باستخدام هذه الخاصية المريحة. |
| [getHeightF()](#getHeightF--) | احصل على ارتفاع الصورة باستخدام هذه الخاصية. |
| [isCached()](#isCached--) | توفر هذه الخاصية طريقة مريحة للتحقق مما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. |
| [getPsStream()](#getPsStream--) | يحصل على الدفق الذي يحتوي على PostScript للتنفيذ. |
| [getPostScriptVersion()](#getPostScriptVersion--) | تسترجع هذه الخاصية إصدار PostScript المرتبط بكيان [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getTitle()](#getTitle--) | تسترجع هذه الخاصية العنوان المستخرج من تعليقات EPS Document Structuring Conventions (DSC) المضمنة داخل ملف EPS. |
| [getCreator()](#getCreator--) | توفر هذه الخاصية الوصول إلى معلومات المُنشئ المستقاة من تعليقات EPS Document Structuring Conventions (DSC) الموجودة داخل ملف EPS. |
| [getCreationDate()](#getCreationDate--) | من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات وصفية أساسية تشير إلى بداية ملف EPS. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات وصفية أساسية تشير إلى بداية ملف EPS. |
| [getBoundingBox()](#getBoundingBox--) | من خلال الوصول إلى صندوق الحدود الأصلي بوحدات نقاط مستقلة عن الجهاز، توفر هذه الخاصية معلومات هندسية حيوية حول أبعاد [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | تُعيد هذه الخاصية صندوق الحدود الأصلي لكيان [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بوحدات البكسل، مما يوفر بيانات هندسية أساسية للتصوير الدقيق والتلاعب. |
| [cacheData()](#cacheData--) | تُعيد هذه الخاصية صندوق الحدود الأصلي لكيان [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بوحدات البكسل، مما يوفر بيانات هندسية أساسية للتصوير الدقيق والتلاعب. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | تصل إلى صور المعاينة المرتبطة بكيان [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)، مما يتيح استرجاعًا سلسًا للفحص أو الاستخدام في التطبيقات. |
| [getPreviewImage()](#getPreviewImage--) | تسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو تُرجع `` إذا لم يتم العثور على أي صورة. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | تسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو تُرجع `` إذا لم يتم العثور على أي صورة. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | خصّص لوحات ألوان الصورة لتحقيق أنظمة ألوان فريدة وتعزيز الجاذبية البصرية. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// تحميل صورة EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    // تغيير حجم الصورة باستخدام طريقة الاستيفاء المكعب Mitchell
    image.resize(400, 400, ResizeType.Mitchell);

    // تصدير الصورة إلى تنسيق PNG
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// تحميل صورة EPS
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // تعيين وضع الاستيفاء
    resizeSettings.setMode(ResizeType.LanczosResample);
    // تعيين نوع الفلتر
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // يضبط طريقة مقارنة اللون
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // تعيين طريقة تمثيل اللون
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // تغيير حجم الصورة باستخدام إعدادات تغيير حجم متقدمة
    image.resize(400, 400, resizeSettings);

    // تصدير الصورة إلى تنسيق PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


احصل على عدد صور المعاينة المتاحة بسهولة. تتيح لك هذه الخاصية استرجاع عدد صور المعاينة المرتبطة بملفك دون جهد، مما يسهّل إدارة وتنقل معاينات الصور بفعالية. مثالية لتحسين سير العمل وتنظيم موارد الصور الخاصة بك بفعالية.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


استرجع صور المعاينة المرتبطة بملفك. توفر هذه الخاصية وصولًا سلسًا إلى مجموعة صور المعاينة، مما يتيح لك تصفحها وإدارتها بكفاءة حسب الحاجة. مثالية لمعاينة سريعة واختيار الصورة المناسبة لمشروعك.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


احصل على تنسيق ملف الصورة باستخدام هذه الخاصية. استرجع معلومات أساسية حول تنسيق ملف الصورة الخاص بك، مما يسهل التوافق والمعالجة الفعّالة. مثالية لتحديد تنسيق ملفات الصور لتكامل سلس في مشاريعك.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


الوصول إلى قيمة النوع الفرعي لصورة EPS الخاصة بك وتفسيرها، مما يبسط سير العمل لديك ويعزز التوافق عبر المنصات. مثالي لتحسين استرجاع النوع الفرعي لـ EPS في مشاريعك بدقة وكفاءة.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


اكتشف وجود معاينة نقطية بسهولة باستخدام هذه الخاصية. احصل على القيمة المنطقية التي تشير إلى ما إذا كانت نسخة [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) تتضمن معاينة نقطية، مما يعزز مهام معالجة الصور لديك بالوضوح والكفاءة. مثالي لتبسيط قرارات سير العمل بناءً على وجود أو عدم وجود معاينات نقطية في صور EPS.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


الوصول إلى عمق البت الدقيق للصورة بسهولة باستخدام هذه الخاصية. استرجع عدد البتات لكل بكسل، مما يوفر رؤى حاسمة حول عمق ألوان الصورة ويساعد في تحسين مهام المعالجة. مثالي للتطبيقات التي تتطلب تحكمًا دقيقًا في تعديل وتحليل الصور.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


استرجع عرض الصورة باستخدام هذه الخاصية المريحة. احصل على عرض الصورة بسهولة، مما يسهل حسابات التخطيط الدقيقة، عمليات التحجيم، والمهام المتعلقة بالأبعاد داخل تطبيقك. مثالي لضمان عرض وتصوير دقيق للصور عبر مختلف المنصات والأجهزة.

**Returns:**
float - عرض الصورة بالبكسل.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


الوصول إلى ارتفاع الصورة باستخدام هذه الخاصية. احصل على ارتفاع الصورة بسهولة، مما يتيح تعديل التخطيط بسلاسة، حساب نسب الأبعاد، وعرض دقيق عبر دقات شاشات مختلفة وبيئات العرض.

**Returns:**
float - ارتفاع الصورة بالبكسل.
### isCached() {#isCached--}
```
public boolean isCached()
```


توفر هذه الخاصية طريقة مريحة للتحقق مما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. إنها تقدم طريقة سريعة وفعالة لتحديد ما إذا كانت المعلومات المطلوبة متاحة فورًا، مما يحسن الأداء ويقلل من استهلاك الموارد في العمليات المكثفة للبيانات.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


يحصل على الدفق الذي يحتوي على PostScript للتنفيذ.

**Returns:**
java.io.InputStream - الدفق الذي يحتوي على PostScript للتنفيذ.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


تسترجع هذه الخاصية نسخة PostScript المرتبطة بنسخة [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). إنها توفر نظرة على نسخة لغة PostScript المحددة المستخدمة داخل ملف EPS، مما يساعد في تقييم التوافق ويسهل التكامل السلس مع البيئات المتوافقة مع PostScript.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


تسترجع هذه الخاصية العنوان المستخرج من تعليقات EPS Document Structuring Conventions (DSC) المضمنة داخل ملف EPS. إنها توفر بيانات وصفية قيمة حول محتوى ملف EPS، مما يساعد في تنظيم المستندات وتحديدها داخل التطبيقات البرمجية المتوافقة.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


توفر هذه الخاصية الوصول إلى معلومات المنشئ المستخرجة من تعليقات EPS Document Structuring Conventions (DSC) الموجودة داخل ملف EPS. فهم تفاصيل المنشئ يمنح رؤى حول البرنامج أو الأداة المستخدمة لإنشاء ملف EPS، مما يسهل تقييم التوافق عبر مختلف المنصات والتطبيقات.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات وصفية أساسية تشير إلى بداية ملف EPS. عبر الوصول إلى هذه المعلومات، يحصل المستخدمون على رؤى حول أصل الملف وتاريخه، مما يعزز إدارة وتنظيم الملفات.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات وصفية أساسية تشير إلى بداية ملف EPS. عبر الوصول إلى هذه المعلومات، يحصل المستخدمون على رؤى حول أصل الملف وتاريخه، مما يعزز إدارة وتنظيم الملفات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


من خلال الوصول إلى الصندوق الحدودي الأصلي بنقاط مستقلة عن الجهاز، توفر هذه الخاصية معلومات هندسية حاسمة حول أبعاد [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). عبر استرجاع هذه البيانات، يمكن للمستخدمين تقييم حجم الصورة ونسبة أبعادها بدقة، مما يسهل التخطيط الدقيق والتموضع في مختلف التطبيقات.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


تُعيد هذه الخاصية الصندوق الحدودي الأصلي لنسخة [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بالبكسل، مما يوفر بيانات هندسية أساسية للتصوير والتعديل الدقيق. باستخدام هذه المعلومات، يمكن للمستخدمين ضمان وضع وحجم دقيق لصور EPS في مشاريعهم، مما يعزز العرض البصري العام والجودة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


تُعيد هذه الخاصية الصندوق الحدودي الأصلي لنسخة [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بالبكسل، مما يوفر بيانات هندسية أساسية للتصوير والتعديل الدقيق. باستخدام هذه المعلومات، يمكن للمستخدمين ضمان وضع وحجم دقيق لصور EPS في مشاريعهم، مما يعزز العرض البصري العام والجودة.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


يصل إلى صور المعاينة المرتبطة بنسخة [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)، مما يسمح باسترجاع سلس للفحص أو الاستخدام في التطبيقات. توفر هذه الطريقة وصولًا مريحًا إلى صور المعاينة، مما يعزز تفاعل المستخدم مع بيانات الصورة.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - صور المعاينة.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


يسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو يُعيد `` إذا لم يتم العثور على أي منها. توفر هذه الطريقة مرونة في الوصول إلى صور المعاينة المخصصة لتنسيقات معينة، مما يحسن التوافق وإدارة الموارد داخل التطبيقات.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


يسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو يُعيد `` إذا لم يتم العثور على أي منها. توفر هذه الطريقة مرونة في الوصول إلى صور المعاينة المخصصة لتنسيقات معينة، مما يحسن التوافق وإدارة الموارد داخل التطبيقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التنسيق | long | تنسيق صورة معاينة EPS. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


خصص لوحات ألوان الصورة لتحقيق مخططات ألوان فريدة وتعزيز الجاذبية البصرية. عدّل الألوان لتأثيرات محددة وحسّن جودة الصورة عبر مختلف المنصات والأجهزة بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

