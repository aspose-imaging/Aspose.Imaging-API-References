---
title: "DicomImage"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هذه الفئة تنفّذ دعم تنسيق صورة نقطية DICOM في التصوير الرقمي والاتصالات في الطب وتقدّم حلاً شاملاً لمعالجة صور DICOM بدقة ومرونة."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

هذه الفئة تنفّذ دعم تنسيق صورة نقطية DICOM (Digital Imaging and Communications in Medicine) وتقدّم حلاً شاملاً لمعالجة صور DICOM بدقة ومرونة. يمكنك تعديل صفحات الصورة بسلاسة، بما في ذلك عمليات الحصول على الصفحات أو إضافتها أو إزالتها، والتحكم في الصفحات الافتراضية والنشطة. مع القدرة على العمل مع قنوات ألفا، وتضمين بيانات XMP الوصفية، وتغيير الحجم، وتدوير، واقتطاع، وتحويل إلى ثنائي، وضبط، وتطبيق الفلاتر، وتحويل إلى تنسيقات نقطية أخرى. تتيح هذه الواجهة البرمجية للمطورين التعامل مع صور DICOM بفعالية مع تلبية متطلبات التطبيقات المتنوعة في سياق التصوير الطبي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | قم بتهيئة نسخة جديدة من فئة DicomImage بسهولة باستخدام هذا المُنشئ، مع الاستفادة من معلمات dicomOptions. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | ابدأ نسخة جديدة من فئة DicomImage بسلاسة عبر استخدام تدفق ومعلمات loadOptions في هذا المُنشئ. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | أنشئ نسخة جديدة من فئة DicomImage باستخدام معلمة التدفق في هذا المُنشئ. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageCount()](#getPageCount--) | استرجع العدد الإجمالي للصفحات في الصورة باستخدام هذه الخاصية البديهية. |
| [getPages()](#getPages--) | الوصول إلى صفحات الصورة باستخدام هذه الخاصية البديهية. |
| [getFileInfo()](#getFileInfo--) | استرجع معلومات الرأس القيمة من ملف DICOM بسهولة باستخدام هذه الخاصية البديهية. |
| [getDicomPages()](#getDicomPages--) | الوصول إلى صفحات الصورة باستخدام هذه الخاصية البديهية. |
| [getActivePage()](#getActivePage--) | الوصول إلى الصفحة النشطة للصورة باستخدام هذه الخاصية البديهية. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | إدارة الصفحة النشطة للصورة باستخدام هذه الخاصية البديهية. |
| [getActivePageIndex()](#getActivePageIndex--) | استرجع فهرس الصفحة النشطة بسهولة باستخدام هذه الخاصية البديهية. |
| [getFileFormat()](#getFileFormat--) | استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية البديهية. |
| [hasAlpha()](#hasAlpha--) | استرجع ما إذا كانت الصورة تحتوي على قناة ألفا بسهولة باستخدام هذه الخاصية البديهية. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | وسّع مجموعة صورك بإضافة صفحة جديدة باستخدام هذه الطريقة البديهية. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | احفظ بيانات الكائن عن طريق حفظها في الملف المحدد (المؤشر + اسم الملف) مع تنسيق الملف المحدد والخيارات. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | قم بضبط دقة هذا [RasterImage](../../com.aspose.imaging/rasterimage) بدقة باستخدام هذه الطريقة المبسطة. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | غيّر حجم الصورة مع الحفاظ على نسبة أبعادها باستخدام هذه الطريقة المريحة. |
| [addPage()](#addPage--) | أضف صفحة جديدة إلى نهاية قائمة صفحات الصورة باستخدام هذه الطريقة المبسطة. |
| [insertPage(int pageIndex)](#insertPage-int-) | أدرج صفحة جديدة في قائمة صفحات الصورة عند فهرس محدد باستخدام هذه الطريقة البديهية. |
| [removePage(int pageIndex)](#removePage-int-) | احذف الصفحة الموجودة عند الفهرس المحدد من قائمة الصفحات باستخدام هذه الطريقة المريحة. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | دوّر الصورة حول مركزها باستخدام هذه الطريقة المريحة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | قم بتعديل حجم الصورة باستخدام هذه الطريقة البسيطة. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | قم بتعديل عرض الصورة مع الحفاظ على نسبة الأبعاد باستخدام هذه الطريقة المريحة. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | قم بتعديل ارتفاع الصورة مع الحفاظ على نسبة الأبعاد باستخدام هذه الطريقة سهلة الاستخدام. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | قم بالتلاعب بسهولة بالإطار النشط عن طريق الدوران أو القلب، أو تنفيذ كلا الإجراءين معًا باستخدام هذه الطريقة البسيطة. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | حسّن الصورة الحالية بتطبيق تأثيرات التدرج باستخدام هذه الطريقة البسيطة. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | قم بقص الصورة لإزالة المناطق غير المرغوبة والتركيز على المحتوى الأساسي باستخدام هذه الطريقة البسيطة. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قم بتعديل منطقة القص في الصورة عن طريق تطبيق الإزاحات باستخدام هذه الطريقة المتعددة الاستخدامات. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | قم بتحويل الصورة بسهولة إلى صيغة ثنائية باستخدام عتبة محددة مسبقًا مع هذه الطريقة البسيطة. |
| [binarizeOtsu()](#binarizeOtsu--) | طبق طريقة عتبة أوتسو لتصنيف الصورة إلى ثنائية، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على مخطط الصورة. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | قم بتحويل الصور إلى ثنائية باستخدام خوارزمية عتبة برادلي التكيفية، مستفيدًا من عتبة الصورة المتكاملة لتحسين الأداء. |
| [grayscale()](#grayscale--) | حوّل الصور بسهولة إلى تمثيلها بالدرجات الرمادية، مما يبسط مهام التحليل البصري والمعالجة. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | حسّن جودة الصورة وقم بتعديلها باستخدام تصحيح غاما، وهي تقنية قوية لضبط المظهر البصري بدقة. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | احصل على تعديلات لونية دقيقة من خلال تطبيق تصحيح غاما بشكل مستقل على مكونات الأحمر والأخضر والأزرق في الصورة. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | حسّن إضاءة الصورة من خلال تعديل `brightness`، وهي طريقة معلمة تتيح للمطورين ضبط سطوع الصور بدقة. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | حسّن تباين [Image](../../com.aspose.imaging/image) باستخدام هذه الطريقة سهلة الاستخدام، التي تعدل الفارق بين المناطق المضيئة والظلامية. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | قم بتحسين مناطق محددة من صورتك بسهولة عن طريق تطبيق الفلاتر على المستطيلات المحددة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | قم بتعديل حجم صورتك باستخدام طريقة تغيير الحجم البسيطة هذه. |
| [cacheData()](#cacheData--) | تقوم هذه الطريقة بتخزين البيانات مؤقتًا بكفاءة، مما يحسن الأداء ويضمن وصولًا سريعًا عند الحاجة. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// تحميل صورة
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // ارسم شيئًا باستخدام الرسومات المتجهية
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // احفظ بكسلات الصورة المرسومة. أصبحت الآن على الصفحة الأولى من صورة Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // أضف بضع صفحات بعد ذلك، مما يجعلها أغمق
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // أضف بضع صفحات أمام الصفحة الرئيسية، مما يجعلها أكثر إشراقًا
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // احفظ الصورة متعددة الصفحات التي تم إنشاؤها إلى ملف الإخراج
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


قم بتهيئة نسخة جديدة من فئة DicomImage بسهولة باستخدام هذا المُنشئ، مع الاستفادة من معلمات dicomOptions. مثالي للمطورين الذين يرغبون في الغوص بسرعة وكفاءة في كائنات [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | خيارات dicom (متجاهلة الآن). |
| width | int | العرض. |
| height | int | الارتفاع. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


ابدأ نسخة جديدة من فئة DicomImage بسلاسة باستخدام تدفق ومعلمات loadOptions في هذا المُنشئ. مثالي للمطورين المتحمسين للبدء في العمل مع كائنات [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) بسرعة وفعالية في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


أنشئ نسخة جديدة من فئة DicomImage باستخدام معلمة تدفق في هذا المُنشئ. مثالي للمطورين الذين يبحثون عن طريقة مبسطة لتهيئة كائنات [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) من تدفقات البيانات الموجودة في مشاريعهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | java.io.InputStream | التدفق. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


استرجع العدد الإجمالي للصفحات في الصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يبحثون عن وصول سريع إلى عدد الصفحات داخل الصورة، مما يضمن تنقلًا وإدارةً فعّالة.

**Returns:**
int - عدد الصفحات.
### getPages() {#getPages--}
```
public Image[] getPages()
```


الوصول إلى صفحات الصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في التفاعل مع الصفحات الفردية داخل الصورة، مما يضمن تنقلًا وتعديلًا سلسًا.

**Returns:**
com.aspose.imaging.Image[] - الصفحات.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


استرجع معلومات رأسية قيمة من ملف DICOM بسهولة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يبحثون عن وصول سريع إلى التفاصيل الأساسية المتضمنة داخل ملف DICOM، مما يضمن استخراجًا فعالًا للبيانات وتحليلًا.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


الوصول إلى صفحات الصورة باستخدام هذه الخاصية البديهية. مثالي للمطورين الذين يرغبون في التفاعل مع الصفحات الفردية داخل الصورة، مما يضمن تنقلًا وتعديلًا سلسًا.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - الصفحات.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


الوصول إلى الصفحة النشطة للصورة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يرغبون في التبديل الديناميكي بين الصفحات داخل الصور متعددة الصفحات، مما يضمن تنقلًا ومعالجةً فعالين.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


إدارة الصفحة النشطة للصورة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يرغبون في التبديل الديناميكي بين الصفحات داخل الصور متعددة الصفحات، مما يضمن تنقلًا ومعالجةً فعالين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | الصفحة النشطة. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


استرجع فهرس الصفحة النشطة بسهولة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يبحثون عن وصول سريع إلى فهرس الصفحة الحالية داخل الصور متعددة الصفحات، مما يضمن تنقلًا ومعالجةً فعالين.

**Returns:**
int - فهرس الصفحة النشطة.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يبحثون عن وصول سريع إلى تنسيق ملف الصورة، مما يضمن معالجةً فعالةً بناءً على نوع الملف.

**Returns:**
long - قيمة تنسيق الملف [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


استرجع ما إذا كانت الصورة تحتوي على قناة ألفا بسهولة باستخدام هذه الخاصية البديهية. مثالية للمطورين الذين يرغبون في تحديد ما إذا كانت الصورة تحتوي على معلومات شفافية، مما يضمن معالجة دقيقة لبيانات قناة ألفا في مهام معالجة الصور.

**Returns:**
boolean - true إذا كانت الصورة تحتوي على قناة ألفا.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


وسّع مجموعة صورك بإضافة صفحة جديدة باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في إلحاق صفحات ديناميكيًا إلى الصور متعددة الصفحات، مما يضمن توسعًا سلسًا وتنظيمًا لمحتوى الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | الصفحة المراد إضافتها. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


احفظ بيانات الكائن عن طريق حفظها إلى الملف المحدد (المؤشر + اسم الملف) مع تنسيق الملف المحدد والخيارات. مثالية للمطورين الذين يرغبون في تخزين البيانات بأمان بتنسيقات مختلفة مع الحفاظ على المرونة والتحكم في معلمات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | الخيارات. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


ضبط دقة هذه [RasterImage](../../com.aspose.imaging/rasterimage) بدقة باستخدام هذه الطريقة المباشرة. مثالية للمطورين الذين يسعون لتكييف دقة الصورة وفقًا للمتطلبات المحددة، مما يضمن جودة عرض مثالية وإدارة حجم الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpiX | double | الدقة الأفقية، بوحدة النقاط لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | الدقة العمودية، بوحدة النقاط لكل بوصة، لـ [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


غيّر حجم الصورة مع الحفاظ على نسبة أبعادها باستخدام هذه الطريقة المريحة. مثالية للمطورين الذين يرغبون في تعديل أبعاد الصورة بشكل متناسب، مما يضمن الاتساق والحفاظ على نسب المحتوى الأصلي. سيقوم التحجيم المتناسب بتغيير حجم كل إطار وفقًا للنسبة بين `newWidth`/العرض و `newHeight`/الارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


أضف صفحة جديدة إلى نهاية قائمة صفحات الصورة باستخدام هذه الطريقة المباشرة. مثالية للمطورين الذين يرغبون في توسيع الصور متعددة الصفحات ديناميكيًا، مما يضمن دمجًا سلسًا وتنظيمًا لمحتوى الصورة.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


أدرج صفحة جديدة في قائمة صفحات الصورة عند فهرس محدد باستخدام هذه الطريقة البديهية. مثالية للمطورين الذين يرغبون في تحكم دقيق في ترتيب الصفحات في الصور متعددة الصفحات، مما يضمن تنظيمًا سلسًا وتخصيصًا لمحتوى الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageIndex | int | فهرس الصفحة. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // ارسم شيئًا باستخدام الرسومات المتجهية
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // احفظ بكسلات الصورة المرسومة. أصبحت الآن على الصفحة الأولى من صورة Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // أضف بضع صفحات بعد ذلك، مما يجعلها أغمق
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // أضف بضع صفحات أمام الصفحة الرئيسية، مما يجعلها أكثر إشراقًا
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // احفظ الصورة متعددة الصفحات التي تم إنشاؤها إلى ملف الإخراج
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


احذف الصفحة عند الفهرس المحدد من قائمة الصفحات باستخدام هذه الطريقة المريحة. مثالية للمطورين الذين يرغبون في تحكم دقيق في إدارة الصور متعددة الصفحات، مما يضمن تنظيمًا سلسًا وتخصيصًا لمحتوى الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageIndex | int | فهرس الصفحة. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


دوّر الصورة حول مركزها باستخدام هذه الطريقة المريحة. مثالية للمطورين الذين يرغبون في تعديل اتجاه الصورة ديناميكيًا، مما يضمن عرضًا مثاليًا ومحاذاة داخل تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة ستدور باتجاه عقارب الساعة. |
| resizeProportionally | boolean | إذا تم تعيينه إلى `true` سيتغير حجم الصورة وفقًا لإسقاطات المستطيل المدور (نقاط الزوايا)، وفي الحالة الأخرى تُترك الأبعاد دون تغيير وتُدور فقط `` image contents are rotated. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | لون الخلفية. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// حمّل صورة DICOM من تدفق ملف.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // دوّر الصورة حول المركز بزاوية 60 درجة باتجاه عقارب الساعة.
        // استخدم اللون الرمادي كلون خلفية.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // لاحظ أنه إذا كانت الصورة ملونة، فسيتم تحويلها تلقائيًا إلى صيغة التدرج الرمادي وفقًا للخيارات أدناه
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // إنشاء مصفوفة من إطارات TIFF.
        // عدد الإطارات يساوي عدد صفحات DJVU.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // احفظ كل صفحة كإطار TIFF منفصل.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // إنشاء إطار TIFF استنادًا إلى صفحة DICOM.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // تكوين صورة TIFF من الإطارات.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // حفظ إلى ملف.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


ضبط حجم الصورة باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تغيير حجم الصور ديناميكيًا، مع ضمان توافقها بسلاسة مع مختلف السياقات والتصاميم داخل تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ إلى PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


ضبط عرض الصورة مع الحفاظ على نسبة أبعادها باستخدام هذه الطريقة المريحة. مثالي للمطورين الذين يسعون إلى تغيير حجم الصور بشكل متناسب، مع ضمان نتائج ثابتة وجذابة بصريًا عبر بيئات العرض المختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
هذا المثال يحمل صورة DICOM ويعيد تحجيمها بشكل متناسب باستخدام طرق إعادة التحجيم المختلفة. يتم تحديد العرض فقط، ويتم حساب الارتفاع تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


ضبط ارتفاع الصورة مع الحفاظ على نسبة أبعادها باستخدام هذه الطريقة سهلة الاستخدام. مثالي للمطورين الذين يرغبون في تغيير حجم الصور ديناميكيًا مع الحفاظ على نسبها، لضمان عرض واستخدام أمثل في تطبيقاتهم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
هذا المثال يحمل صورة DICOM ويعيد تحجيمها بشكل متناسب باستخدام طرق إعادة التحجيم المختلفة. يتم تحديد الارتفاع فقط، ويتم حساب العرض تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // احفظ كـ PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


يمكنك بسهولة تعديل الإطار النشط عن طريق الدوران أو القلب، أو تنفيذ كلا الإجراءين معًا باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يحتاجون إلى تعديل اتجاه إطارات معينة داخل تسلسلات الصور ديناميكيًا، لضمان عرض ومحاذاة مثالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع القلب الدوراني. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

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
    // قم بالدوران، والقلّب، واحفظ إلى ملف الإخراج.
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
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


حسّن الصورة الحالية بتطبيق تأثيرات التمويه باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يهدفون إلى إضافة نسيج وعمق للصور، مما يحسن جودتها البصرية وجاذبيتها العامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ditheringMethod | int | طريقة التمويه. |
| bitsCount | int | عدد البتات النهائي للتمويه. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان المخصصة للتمويه. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // نفّذ تلوين بالعتبة باستخدام لوحة ألوان 4-بت تحتوي على 16 لونًا.
    // كلما زادت عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // نفّذ تلوين فلويد باستخدام لوحة ألوان 1-بت تحتوي فقط على لونين - أسود وأبيض.
    // كلما زادت عدد البتات المحددة، ارتفعت الجودة وزاد حجم الصورة الناتجة.
    // لاحظ أن لوحات الألوان 1-بت، 4-بت و8-بت فقط هي المدعومة حاليًا.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


قم بقص الصورة لإزالة المناطق غير المرغوبة والتركيز على المحتوى الأساسي باستخدام هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تخصيص التركيب البصري للصور، لضمان نقل الرسالة المطلوبة بفعالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |


**Example: The following example crops a DICOM image.**
المثال التالي يقتطع صورة DICOM. يتم تحديد منطقة القص عبر Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // قص الصورة. منطقة القص هي المنطقة المركزية المستطيلة للصورة.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


ضبط منطقة قص الصورة عن طريق تطبيق إزاحات باستخدام هذه الطريقة المتعددة الاستخدامات. مثالي للمطورين الذين يحتاجون إلى تحكم دقيق في عملية القص، لضمان الحفاظ على التفاصيل المهمة مع إزالة العناصر غير الضرورية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |


**Example: The following example crops a DICOM image.**
المثال التالي يقتطع صورة DICOM. يتم تحديد منطقة القص عبر هوامش اليسار، الأعلى، اليمين، الأسفل.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // اقتطع مرة أخرى. اضبط هامشًا بنسبة 10٪ من حجم الصورة.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // احفظ الصورة المقتطعة بصيغة PNG.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


يمكنك بسهولة تحويل الصورة إلى صيغة ثنائية باستخدام عتبة محددة مسبقًا مع هذه الطريقة البسيطة. مثالي للمطورين الذين يرغبون في تبسيط مهام معالجة الصور عن طريق تقسيم الصورة إلى مكونات المقدمة والخلفية بناءً على مستويات الشدة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| threshold | byte | قيمة العتبة. إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من العتبة، سيتم تعيين القيمة 255 لها، وإلا 0. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
المثال التالي يحول صورة DICOM إلى ثنائية باستخدام العتبة المحددة مسبقًا. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // حوّل الصورة إلى ثنائية باستخدام قيمة العتبة 127.
    // إذا كانت قيمة الرمادي المقابلة للبكسل أكبر من 127، سيتم تعيين قيمة 255 له، وإلا ستكون 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


تطبيق عتبة أوتسو لتثنائي الصورة، مع تحديد القيمة المثلى للعتبة تلقائيًا بناءً على هيستوغرام الصورة. مثالي للمطورين الذين يبحثون عن طريقة موثوقة لتقسيم الصور إلى مناطق المقدمة والخلفية بأقل تدخل يدوي.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
المثال التالي يحول صورة DICOM إلى ثنائية باستخدام عتبة أوتسو. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // حوّل الصورة إلى ثنائية باستخدام عتبة أوتسو.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


قم بتثنائي الصور باستخدام خوارزمية العتبة التكيفية لبرادلي، مستفيدًا من عتبة الصورة المتكاملة لتحسين الأداء. مثالي للمطورين الذين يرغبون في تقسيم الصور تلقائيًا بناءً على التغيرات المحلية في السطوع، لضمان اكتشاف واستخراج كائنات دقيقة في ظروف إضاءة متغيرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightnessDifference | double | فرق السطوع بين البكسل ومتوسط نافذة بحجم s × s من البكسلات المتمركزة حول هذا البكسل. |
| windowSize | int | حجم نافذة s × s من البكسلات المتمركزة حول هذا البكسل |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
المثال التالي يحول صورة DICOM إلى ثنائية باستخدام خوارزمية العتبة التكيفية لبرادلي مع حجم النافذة المحدد. الصور الثنائية تحتوي على لونين فقط - الأسود والأبيض.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // حوّل الصورة إلى ثنائية بفرق سطوع قدره 5. السطوع هو الفرق بين بكسل ومتوسط نافذة 10 × 10 بكسل متمركزة حول هذا البكسل.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


يمكنك بسهولة تحويل الصور إلى تمثيلها بتدرج الرمادي، مما يبسط تحليل الصور ومهام المعالجة. مثالي للمطورين الذين يسعون إلى تحسين وضوح الصورة، تقليل التعقيد، وتسهيل الخوارزميات القائمة على التدرج الرمادي لتطبيقات متنوعة.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
المثال التالي يحول صورة DICOM ملونة إلى تمثيلها بتدرج الرمادي. صور التدرج الرمادي تتكون حصريًا من درجات اللون الرمادي وتحمل فقط معلومات الشدة.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


حسّن جودة الصورة واضبطها باستخدام تصحيح جاما، وهي تقنية قوية لضبط المظهر البصري بدقة. مثالية للمطورين الذين يهدفون إلى تحسين عرض الصورة، وضبط توازن الألوان، وضمان عرض متسق عبر الأجهزة والبيئات المختلفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| غاما | float | معامل غاما للقنوات الحمراء والخضراء والزرقاء |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تعيين معامل غاما للقنوات الحمراء والخضراء والزرقاء.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


تحقق من ضبط الألوان بدقة عن طريق تطبيق تصحيح جاما بشكل مستقل على مكونات الأحمر والأخضر والأزرق في الصورة. تضمن هذه الطريقة توازنًا دقيقًا للألوان وإخراجًا بصريًا مثاليًا، موجهة للمطورين الذين يسعون إلى تحكم دقيق في عرض الصورة ودقة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| gammaRed | float | معامل غاما للقناة الحمراء |
| gammaGreen | float | معامل غاما للقناة الخضراء |
| gammaBlue | float | معامل غاما للقناة الزرقاء |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تعيين معاملات غاما الفردية للقنوات الحمراء والخضراء والزرقاء.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


حسّن إضاءة الصورة من خلال تعديل `brightness`، وهي طريقة معلمة تسمح للمطورين بضبط سطوع الصور بدقة. تمكّن هذه الدالة سهلة الاستخدام المطورين من تعديل سطوع الصورة بسلاسة، مما يوفر مرونة وتحكمًا في الجماليات البصرية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brightness | int | قيمة السطوع. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // حدد قيمة السطوع. القيم المقبولة للسطوع تقع في النطاق [-255، 255].
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


حسّن تباين [Image](../../com.aspose.imaging/image) باستخدام هذه الطريقة السهلة، التي تضبط الفارق بين المناطق الفاتحة والداكنة. حسّن الوضوح البصري والتفصيل بسهولة، مما يوفّر للمطورين تحكمًا بديهيًا في تباين الصورة للحصول على عرض مثالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| contrast | float | قيمة التباين (في النطاق [-100؛ 100]) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // حدد قيمة التباين. القيم المقبولة للتباين تقع في النطاق [-100f، 100f].
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


قم بتحسين مناطق محددة من صورتك بسهولة عن طريق تطبيق فلاتر على مستطيلات محددة. توفّر هذه الطريقة للمطورين تحكمًا دقيقًا في تعديل الصورة، مما يسمح بإجراء تعديلات مستهدفة لتحقيق التأثيرات البصرية المطلوبة بسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | الخيارات. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تطبيق مرشح متوسط بحجم مستطيل 5 على الصورة بالكامل.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تطبيق مرشح تنعيم ثنائي الجانب بحجم نواة 5 على الصورة بالكامل.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تطبيق مرشح تمويه غاوسي بنصف قطر 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تطبيق مرشح غاوس-واينر بنصف قطر 5 وقيمة تمهيد 4.0 على الصورة بالكامل.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تطبيق مرشح حركة واينر بطول 5، قيمة تمهيد 4.0 وزاوية 90.0 درجة على الصورة بالكامل.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // تطبيق مرشح تعزيز الحدة بحجم نواة 5 وقيمة سيغما 4.0 على الصورة بالكامل.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


اضبط حجم صورتك باستخدام طريقة تغيير الحجم البسيطة هذه. سواء كنت بحاجة لتصغير أو تكبير صورتك، تضمن هذه الدالة تلبية احتياجات تغيير الحجم بكفاءة ودقة، مما يجعلها مثالية للمطورين الذين يبحثون عن تعديل حجم الصورة بسرعة وسهولة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// الخوارزمية التكيفية المستندة إلى الدالة الكسرية الموزونة والمختلطة واستيفاء lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// المرشح المستطيل الصغير
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// عدد الألوان في لوحة الألوان.
resizeSettings.setEntriesCount(256);

// لم يتم استخدام تقليل ألوان الصورة
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// طريقة إقليدية
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات تكيفية.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // احفظ إلى PNG
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


تقوم هذه الطريقة بتخزين البيانات مؤقتًا بكفاءة، مما يحسن الأداء ويضمن وصولًا سريعًا عند الحاجة. مثالية للمطورين الذين يرغبون في تعزيز سرعة وكفاءة تطبيقاتهم من خلال إدارة موارد البيانات بذكاء.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// حمّل صورة من ملف DICOM.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // يقوم هذا الاستدعاء بتخزين جميع الصفحات مؤقتًا بحيث لا يتم تحميل بيانات إضافية من تدفق البيانات الأساسي.
    image.cacheData();

    // أو يمكنك تخزين الصفحات مؤقتًا بشكل فردي.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

