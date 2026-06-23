---
title: "EpsImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "توفر واجهة برمجة التطبيقات لدعم تنسيق ملف صورة Encapsulated PostScript EPS قدرات قوية لمعالجة التركيبات التي تتضمن نصًا ورسومات وصورًا."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

توفر واجهة برمجة التطبيقات لدعم تنسيق ملف صورة Encapsulated PostScript (EPS) قدرات قوية لمعالجة التركيبات التي تتضمن نصًا ورسومات وصورًا. تشمل الميزات معالجة صور المعاينة النقطية، وتدوير الاتجاه، واسترجاع صندوق الحدود للرسوم التوضيحية، وتغيير الحجم، وتدوير الصور، وإضافة صور المعاينة. تضمن هذه الواجهة معالجة سلسة وتكامل ملفات EPS في تطبيقات مختلفة بدقة وتنوع.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | احصل على عدد صور المعاينة المتاحة بسهولة. |
| [getPreviewImages()](#getPreviewImages--) | استرجع صور المعاينة المرتبطة بملفك. |
| [getFileFormat()](#getFileFormat--) | احصل على تنسيق ملف صورتك باستخدام هذه الخاصية. |
| [getEpsType()](#getEpsType--) | احصل على قيمة النوع الفرعي لصورة EPS الخاصة بك وتفسيرها، مما يبسط سير العمل الخاص بك ويعزز التوافق عبر المنصات. |
| [hasRasterPreview()](#hasRasterPreview--) | اكتشف وجود معاينة نقطية بسهولة باستخدام هذه الخاصية. |
| [getBitsPerPixel()](#getBitsPerPixel--) | احصل على عمق البت الدقيق للصورة بسهولة باستخدام هذه الخاصية. |
| [getWidthF()](#getWidthF--) | استرجع عرض الصورة باستخدام هذه الخاصية المريحة. |
| [getHeightF()](#getHeightF--) | احصل على ارتفاع الصورة باستخدام هذه الخاصية. |
| [isCached()](#isCached--) | توفر هذه الخاصية طريقة مريحة للتحقق مما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة إلى قراءة بيانات إضافية. |
| [getPsStream()](#getPsStream--) | يحصل على الدفق الذي يحتوي على PostScript للتنفيذ. |
| [getPostScriptVersion()](#getPostScriptVersion--) | تسترجع هذه الخاصية إصدار PostScript المرتبط بكيان [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getTitle()](#getTitle--) | تسترجع هذه الخاصية العنوان المستخرج من تعليقات EPS Document Structuring Conventions (DSC) المضمنة داخل ملف EPS. |
| [getCreator()](#getCreator--) | توفر هذه الخاصية الوصول إلى معلومات المنشئ المستخرجة من تعليقات EPS Document Structuring Conventions (DSC) الموجودة داخل ملف EPS. |
| [getCreationDate()](#getCreationDate--) | من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات تعريفية أساسية تشير إلى بداية ملف EPS. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | من خلال استرجاع تاريخ الإنشاء من تعليقات EPS Document Structuring Conventions (DSC)، توفر هذه الخاصية بيانات تعريفية أساسية تشير إلى بداية ملف EPS. |
| [getBoundingBox()](#getBoundingBox--) | عند الوصول إلى الصندوق الحدودي الأصلي بوحدات مستقلة عن الجهاز، توفر هذه الخاصية معلومات هندسية حيوية حول أبعاد [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | تُعيد هذه الخاصية الصندوق الحدودي الأصلي لكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بالبكسل، مُقدمةً بيانات هندسية أساسية للتصوير الدقيق والتلاعب. |
| [cacheData()](#cacheData--) | تُعيد هذه الخاصية الصندوق الحدودي الأصلي لكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بالبكسل، مُقدمةً بيانات هندسية أساسية للتصوير الدقيق والتلاعب. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | تُصل إلى صور المعاينة المرتبطة بكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)، مما يتيح استرجاعًا سلسًا للفحص أو الاستخدام في التطبيقات. |
| [getPreviewImage()](#getPreviewImage--) | تسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو تُعيد `` إذا لم تُعثر على أي صورة. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | تسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو تُعيد `` إذا لم تُعثر على أي صورة. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | خصّص لوحات ألوان الصورة لتحقيق مخططات ألوان فريدة وتعزيز الجاذبية البصرية. |

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
    // يضبط طريقة مقارنة الألوان
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // تعيين طريقة تمثيل الألوان
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // تغيير حجم الصورة باستخدام إعدادات تعديل متقدمة
    image.resize(400, 400, resizeSettings);

    // تصدير الصورة إلى تنسيق PNG
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


احصل على عدد صور المعاينة المتاحة بسهولة. تتيح لك هذه الخاصية استرجاع عدد صور المعاينة المرتبطة بملفك دون عناء، مما يُمكنك من إدارة وتنقل فعال لصور المعاينة. مثالية لتحسين سير العمل وتنظيم موارد الصور الخاصة بك بفعالية.

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


احصل على تنسيق ملف الصورة باستخدام هذه الخاصية. استرجع معلومات أساسية حول تنسيق ملف الصورة الخاص بك، مما يُسهل التوافق والمعالجة الفعّالة. مثالية لتحديد تنسيق ملفات الصور لتكامل سلس في مشاريعك.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


احصل على قيمة النوع الفرعي لصورة EPS الخاصة بك وفسّرها، مما يُبسّط سير العمل ويعزز التوافق عبر المنصات. مثالية لتحسين استرجاع النوع الفرعي لـ EPS في مشاريعك بدقة وكفاءة.

**Returns:**
قصير
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


اكتشف وجود معاينة نقطية بسهولة باستخدام هذه الخاصية. احصل على القيمة المنطقية التي تشير إلى ما إذا كان كائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) يتضمن معاينة نقطية، مما يُعزز مهام معالجة الصور بالوضوح والكفاءة. مثالية لتبسيط قرارات سير العمل بناءً على وجود أو عدم وجود معاينات نقطية في صور EPS.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


احصل على عمق البت الدقيق للصورة بسهولة باستخدام هذه الخاصية. استرجع عدد البتات لكل بكسل، مُقدمةً رؤى حيوية حول عمق ألوان الصورة ومُساعدةً في تحسين مهام المعالجة. مثالية للتطبيقات التي تتطلب تحكمًا دقيقًا في تعديل وتحليل الصور.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


استرجع عرض الصورة باستخدام هذه الخاصية المريحة. احصل على عرض الصورة بسهولة، مما يُسهل حسابات التخطيط الدقيقة، عمليات التحجيم، والمهام المتعلقة بالأبعاد داخل تطبيقك. مثالية لضمان عرض وتصوير دقيق للصور عبر مختلف المنصات والأجهزة.

**Returns:**
float - عرض الصورة بالبكسل.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


احصل على ارتفاع الصورة باستخدام هذه الخاصية. استخرج ارتفاع الصورة بسهولة، مما يُتيح تعديل تخطيط سلس، حساب نسبة الأبعاد، وعرض دقيق عبر شاشات بدقة مختلفة وبيئات عرض متنوعة.

**Returns:**
float - ارتفاع الصورة بالبكسل.
### isCached() {#isCached--}
```
public boolean isCached()
```


توفر هذه الخاصية طريقة مريحة للتحقق مما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا، مما يلغي الحاجة لقراءة بيانات إضافية. تُقدم طريقة سريعة وفعّالة لتحديد ما إذا كانت المعلومات المطلوبة متاحة فورًا، مما يُحسّن الأداء ويقلل من استهلاك الموارد في العمليات المكثفة للبيانات.

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


تسترجع هذه الخاصية نسخة PostScript المرتبطة بكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). تُوفر نظرة على نسخة لغة PostScript المستخدمة داخل ملف EPS، مما يُساعد في تقييم التوافق ويسهّل التكامل السلس مع البيئات المتوافقة مع PostScript.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


تسترجع هذه الخاصية العنوان المستخرج من تعليقات اتفاقيات هيكلة مستندات EPS (DSC) المضمنة داخل ملف EPS. تُقدم بيانات وصفية قيمة حول محتوى ملف EPS، مما يُساعد في تنظيم المستندات وتحديدها داخل التطبيقات البرمجية المتوافقة.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


توفر هذه الخاصية وصولًا إلى معلومات المُنشئ المستخرجة من تعليقات اتفاقيات هيكلة مستندات EPS (DSC) الموجودة داخل ملف EPS. فهم تفاصيل المُنشئ يُعطي نظرة على البرنامج أو الأداة المستخدمة لإنشاء ملف EPS، مما يُسهل تقييم التوافق عبر منصات وتطبيقات متعددة.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


من خلال استرجاع تاريخ الإنشاء من تعليقات اتفاقيات هيكلة مستندات EPS (DSC)، تُوفر هذه الخاصية بيانات وصفية أساسية تُظهر بداية ملف EPS. عبر الوصول إلى هذه المعلومات، يحصل المستخدمون على نظرة حول أصل الملف وتاريخه، مما يُحسّن إدارة وتنظيم الملفات.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


من خلال استرجاع تاريخ الإنشاء من تعليقات اتفاقيات هيكلة مستندات EPS (DSC)، تُوفر هذه الخاصية بيانات وصفية أساسية تُظهر بداية ملف EPS. عبر الوصول إلى هذه المعلومات، يحصل المستخدمون على نظرة حول أصل الملف وتاريخه، مما يُحسّن إدارة وتنظيم الملفات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


عند الوصول إلى الصندوق الحدودي الأصلي بوحدات مستقلة عن الجهاز، تُوفر هذه الخاصية معلومات هندسية حيوية حول أبعاد [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage). من خلال استرجاع هذه البيانات، يمكن للمستخدمين تقييم حجم الصورة ونسبة أبعادها بدقة، مما يُسهل التخطيط والتموضع الدقيق في تطبيقات مختلفة.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


تُعيد هذه الخاصية الصندوق الحدودي الأصلي لكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بالبكسل، مُقدمةً بيانات هندسية أساسية للتصوير الدقيق والتلاعب. باستخدام هذه المعلومات، يمكن للمستخدمين ضمان وضع وحجم دقيق لصور EPS في مشاريعهم، مما يُحسّن العرض البصري العام والجودة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


تُعيد هذه الخاصية الصندوق الحدودي الأصلي لكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) بالبكسل، مُقدمةً بيانات هندسية أساسية للتصوير الدقيق والتلاعب. باستخدام هذه المعلومات، يمكن للمستخدمين ضمان وضع وحجم دقيق لصور EPS في مشاريعهم، مما يُحسّن العرض البصري العام والجودة.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


تُصل إلى صور المعاينة المرتبطة بكائن [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage)، مما يتيح استرجاعًا سلسًا للفحص أو الاستخدام في التطبيقات. تُوفر هذه الطريقة وصولًا مريحًا إلى صور المعاينة، مما يُعزز تفاعل المستخدم مع بيانات الصورة.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - صور المعاينة.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


تسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو تُعيد `` إذا لم تُعثر على أي صورة. تُوفر هذه الطريقة مرونة في الوصول إلى صور المعاينة المخصصة لتنسيقات معينة، مما يُحسّن التوافق وإدارة الموارد داخل التطبيقات.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


تسترجع صورة المعاينة الموجودة بالتنسيق المحدد `format` أو تُعيد `` إذا لم تُعثر على أي صورة. تُوفر هذه الطريقة مرونة في الوصول إلى صور المعاينة المخصصة لتنسيقات معينة، مما يُحسّن التوافق وإدارة الموارد داخل التطبيقات.

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


قم بتخصيص لوحات ألوان الصورة لتحقيق مخططات ألوان فريدة وتعزيز الجاذبية البصرية. صمّم الألوان لتأثيرات محددة وحسّن جودة الصورة عبر مختلف المنصات والأجهزة بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

