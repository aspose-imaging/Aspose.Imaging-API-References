---
title: "صورة"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الصورة هي الفئة الأساسية لجميع أنواع الصور."
type: docs
weight: 56
url: /ar/java/com.aspose.imaging/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.imaging.IObjectWithBounds](../../com.aspose.imaging/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler, [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler, IMetadataContainer
```

الصورة هي الفئة الأساسية لجميع أنواع الصور.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد وباختياريًا باستخدام خيارات الفتح المحددة. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد وباختياريًا باستخدام `loadOptions` المحددة. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.ImageOptionsBase-int-int-) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)](#create-com.aspose.imaging.ImageOptionsBase-int-int-int---) | ينشئ مثيلًا من [RasterImage](../../com.aspose.imaging/rasterimage) من مصفوفة البكسلات المقدمة. |
| [create(Image[] images)](#create-com.aspose.imaging.Image---) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات |
| [create(MultipageCreateOptions multipageCreateOptions)](#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-) | ينشئ خيارات إنشاء الصفحات المتعددة المحددة. |
| [create(String[] files, boolean throwExceptionOnLoadError)](#create-java.lang.String---boolean-) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(String[] files)](#create-java.lang.String---) | ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.imaging.Image---boolean-) | ينشئ صورة جديدة باستخدام الصور المحددة كصفحات. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | يحصل على تنسيق الملف. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.imaging.LoadOptions-) | يقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. |
| [load(String filePath)](#load-java.lang.String-) | يقوم بتحميل صورة جديدة من مسار الملف أو عنوان URL المحدد. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.imaging.LoadOptions-) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(InputStream stream)](#load-java.io.InputStream-) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | يحصل على تنسيق الملف. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-) | يحصل على المستطيل الذي يناسب الصورة الحالية. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | يحصل على عرض متناسب. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | يحصل على ارتفاع متناسب. |
| [removeMetadata()](#removeMetadata--) | يزيل البيانات الوصفية. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | يحاول تعيين نسخة `metadata`، إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق نوع [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد بتات الصورة لكل بكسل. |
| [getBounds()](#getBounds--) | يحصل على حدود الصورة. |
| [getContainer()](#getContainer--) | يحصل على حاوية `Image`. |
| [getPalette()](#getPalette--) | يحصل على لوحة الألوان. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | يضبط لوحة الألوان. |
| [isUsePalette()](#isUsePalette--) | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| [getSize()](#getSize--) | يحصل على حجم الصورة. |
| [getInterruptMonitor()](#getInterruptMonitor--) | يحصل على مراقب المقاطعة. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-) | يضبط مراقب المقاطعة. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | يضبط قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| [hasBackgroundColor()](#hasBackgroundColor--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| [getFileFormat()](#getFileFormat--) | استرجع بسهولة قيمة تنسيق الملف باستخدام هذه الخاصية السهلة الاستخدام. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل أو يضبط قيمة للون الخلفية. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يحصل أو يضبط قيمة للون الخلفية. |
| [getMetadata()](#getMetadata--) | يحصل على بيانات تعريف الصورة. |
| [getExifData()](#getExifData--) | يحصل على بيانات Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | يضبط بيانات Exif. |
| [getXmpData()](#getXmpData--) | يحصل على بيانات Xmp. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | يضبط بيانات Xmp. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | يحصل على معلومات معالج حدث التقدم. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | يحصل على معلومات معالج حدث التقدم. |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.imaging.ImageOptionsBase-) | يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | يُعيد تحجيم الصورة. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | يُعيد تحجيم الصورة. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | يُعيد تحجيم الصورة. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | يحصل على الخيارات الافتراضية. |
| [getOriginalOptions()](#getOriginalOptions--) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-) | يعيد تحجيم العرض بنسبة متناسبة. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-) | يعيد تحجيم الارتفاع بنسبة متناسبة. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | يدور، يقلب، أو يدور ويقلب الصورة. |
| [rotate(float angle)](#rotate-float-) | دوّر الصورة حول المركز. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص المستطيل المحدد. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | قص الصورة مع الإزاحات. |
| [save()](#save--) | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ الصورة إلى موقع الملف المحدد. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | يضبط لوحة ألوان الصورة. |
| [getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)](#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---) | يحول إلى aps. |

## Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.
هذا المثال ينشئ ملف صورة جديد في موقع قرصي معين كما هو محدد بواسطة خاصية Source لكائن BmpOptions. يتم تعيين عدة خصائص لكائن BmpOptions قبل إنشاء الصورة الفعلية. خاصةً خاصية Source التي تشير إلى الموقع القرصي الفعلي في هذه الحالة.
``` java
// إنشاء مثيل من BmpOptions وتعيين خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
// المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// إنشاء مثيل من Image وتهيئته بمثيل BmpOptions عن طريق استدعاء طريقة Create.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


## Example: Determine if the palette is used by the image.

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |

**Returns:**
منطقي - `true` إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا `false`.

**Example: This example determines whether image can be loaded from a file.**

``` java

// استخدم مسارًا مطلقًا للملف
boolean canLoad = com.aspose.imaging.Image.canLoad("c:\\temp\\sample.gif");
```

### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد وباختياريًا باستخدام خيارات الفتح المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

**Returns:**
منطقي - `true` إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا `false`.
### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | الدفق للتحميل منه. |

**Returns:**
منطقي - `true` إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا `false`.

**Example: This example determines whether image can be loaded from a file stream.**

``` java
String dir = "c:\\temp\\";

boolean canLoad;

// استخدم دفق ملف.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
try {
    canLoad = com.aspose.imaging.Image.canLoad(stream);
} finally {
    stream.close();
}

// البيانات التالية ليست دفق صورة صالح، لذا تُعيد CanLoad القيمة false.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    canLoad = com.aspose.imaging.Image.canLoad(stream);
}
```

### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد وباختياريًا باستخدام `loadOptions` المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | الدفق للتحميل منه. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

**Returns:**
منطقي - `true` إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا `false`.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الصورة. |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The newly created image.

**Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.**
هذا المثال ينشئ ملف صورة جديد في موقع قرصي معين كما هو محدد بواسطة خاصية Source لكائن BmpOptions. يتم تعيين عدة خصائص لكائن BmpOptions قبل إنشاء الصورة الفعلية. خاصةً خاصية Source التي تشير إلى الموقع القرصي الفعلي في هذه الحالة.
``` java
// إنشاء مثيل من BmpOptions وتعيين خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
// المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// إنشاء مثيل من Image وتهيئته بمثيل BmpOptions عن طريق استدعاء طريقة Create.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // قم ببعض معالجة الصورة.

    // احفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### create(ImageOptionsBase imageOptions, int width, int height, int[] pixels) {#create-com.aspose.imaging.ImageOptionsBase-int-int-int---}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```


ينشئ كائن [RasterImage](../../com.aspose.imaging/rasterimage) من مصفوفة البكسلات المقدمة. يتحقق من أن العرض والارتفاع المحددين يتطابقان مع أبعاد بيانات البكسل. لا يمكن استخدام هذه الطريقة إلا عندما تكون المكتبة في وضع الترخيص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | الخيارات المستخدمة لإنشاء [RasterImage](../../com.aspose.imaging/rasterimage). |
| width | int | عرض [RasterImage](../../com.aspose.imaging/rasterimage). |
| height | int | ارتفاع [RasterImage](../../com.aspose.imaging/rasterimage). |
| بكسلات | int[] | مصفوفة قيم البكسل المستخدمة لملء الصورة. |

**Returns:**
[Image](../../com.aspose.imaging/image) - A [RasterImage](../../com.aspose.imaging/rasterimage) populated with the provided pixel data.
### create(Image[] images) {#create-com.aspose.imaging.Image---}
```
public static Image create(Image[] images)
```


ينشئ صورة جديدة باستخدام الصور المحددة كصفحات

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | الصور. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### create(MultipageCreateOptions multipageCreateOptions) {#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-}
```
public static Image create(MultipageCreateOptions multipageCreateOptions)
```


ينشئ خيارات إنشاء الصفحات المتعددة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| multipageCreateOptions | [MultipageCreateOptions](../../com.aspose.imaging.imageoptions/multipagecreateoptions) | خيارات إنشاء الصفحات المتعددة. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files, boolean throwExceptionOnLoadError) {#create-java.lang.String---boolean-}
```
public static Image create(String[] files, boolean throwExceptionOnLoadError)
```


ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملفات | java.lang.String[] | الملفات. |
| throwExceptionOnLoadError | boolean | إذا تم تعيينه إلى `true` [throw exception on load error]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files) {#create-java.lang.String---}
```
public static Image create(String[] files)
```


ينشئ صورة متعددة الصفحات تحتوي على الملفات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملفات | java.lang.String[] | الملفات. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(Image[] images, boolean disposeImages) {#create-com.aspose.imaging.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


ينشئ صورة جديدة باستخدام الصور المحددة كصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | الصور. |
| disposeImages | boolean | إذا تم تعيينه إلى `true` [dispose images]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


يحصل على تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف. |

إن تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد التحميلات الزائدة لطريقة CanLoad لتحديد ما إذا كان يمكن تحميل الملف. |

**Returns:**
long - تنسيق الملف المحدد.

**Example: This example shows how to determine the image format without loading the entire image from a file.**

``` java
String dir = "c:\\temp\\";

// استخدم مسارًا مطلقًا للملف
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// تمثيل نصي لتنسيق الملف.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


يقوم بتحميل صورة جديدة من مسار الملف أو URL المحدد. إذا كان `filePath` مسار ملف، فإن الطريقة تفتح الملف فقط. إذا كان `filePath` URL، فإن الطريقة تقوم بتنزيل الملف، تخزينه مؤقتًا، ثم فتحه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف أو URL لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


يقوم بتحميل صورة جديدة من مسار الملف أو URL المحدد. إذا كان `filePath` مسار ملف، فإن الطريقة تفتح الملف فقط. إذا كان `filePath` URL، فإن الطريقة تقوم بتنزيل الملف، تخزينه مؤقتًا، ثم فتحه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف أو URL لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the loading of an existing Image file into an instance of com.**
يوضح هذا المثال تحميل ملف صورة موجود إلى كائن من com.aspose.imaging.Image باستخدام مسار الملف المحدد
``` java
// إنشاء كائن Image وتهيئته بملف صورة موجود من موقع القرص
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // قم ببعض معالجة الصورة.
} finally {
    image.dispose();
}
```

### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق البيانات لتحميل الصورة منه. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | خيارات التحميل. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق البيانات لتحميل الصورة منه. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the use of InputStream object to load an existing Image file**

``` java
// إنشاء نسخة من FileInputStream
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.bmp");
try {
    // إنشاء نسخة من فئة Image وتحميل ملف موجود عبر كائن FileStream عن طريق استدعاء طريقة Load
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(stream);
    try {
        // قم ببعض معالجة الصورة.
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


يحصل على تنسيق الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التدفق | java.io.InputStream | المجرى. |

تنسيق الملف المحدد لا يعني أن الصورة المحددة يمكن تحميلها. استخدم أحد التحميلات الزائدة لطريقة CanLoad لتحديد ما إذا كان يمكن تحميل الدفق. |

**Returns:**
long - تنسيق الملف المحدد.

**Example: This example shows how to determine the image format without loading the entire image from a file stream.**

``` java

// فئة المساعدة المستخدمة في المثال الرئيسي أدناه.
class Utils {
    // طريقة المساعدة للحصول على تمثيل نصي لتنسيق الملف.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// هنا المثال الرئيسي
Utils utils = new Utils();

String dir = "c:\\temp\\";

// استخدم دفق ملف.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// البيانات التالية ليست دفق صورة صالح، لذلك تُعيد GetFileFormat القيمة FileFormat.Undefined.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// قد يبدو الإخراج هكذا:
// تنسيق الملف هو BMP
// تنسيق الملف هو UNDEFINED
```

### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


يحصل على المستطيل الذي يناسب الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للحصول على المستطيل المناسب له. |
| العرض | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


يحصل على المستطيل الذي يناسب الصورة الحالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل للحصول على المستطيل المناسب له. |
| بكسلات | int[] | بكسلات ARGB 32-بت. |
| العرض | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


يحصل على عرض متناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |
| newHeight | int | الارتفاع الجديد. |

**Returns:**
int - العرض النسبي.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


يحصل على ارتفاع متناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض. |
| الارتفاع | int | الارتفاع. |
| newWidth | int | العرض الجديد. |

**Returns:**
int - الارتفاع النسبي.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


يزيل البيانات الوصفية.

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


يحاول تعيين نسخة `metadata`، إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق نوع [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | البيانات الوصفية. |

**Returns:**
boolean - صحيح، إذا كان كائن [Image](../../com.aspose.imaging/image) يدعم ويطبق النوع [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)؛ وإلا، false.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


يحصل على عدد بتات الصورة لكل بكسل.

**Returns:**
int - عدد بتات الصورة لكل بكسل.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


يحصل على حدود الصورة.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The image bounds.
### getContainer() {#getContainer--}
```
public Image getContainer()
```


يحصل على حاوية `Image`.

القيمة: حاوية `Image`.

إذا لم تكن هذه الخاصية null فهذا يدل على أن الصورة مضمَّنة داخل صورة أخرى.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل على لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يضبط لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |

### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.

القيمة: `true` إذا تم استخدام اللوحة في الصورة؛ وإلا، `false`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة.

**Example: Determine if the palette is used by the image.**

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### getSize() {#getSize--}
```
public Size getSize()
```


يحصل على حجم الصورة.

**Returns:**
[Size](../../com.aspose.imaging/size) - The image size.

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

### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


يحصل على مراقب المقاطعة.

**Returns:**
[InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) - the interrupt monitor.
### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


يضبط مراقب المقاطعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) | مراقب المقاطعة. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الإيجابية تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Returns:**
int - تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية.

القيمة: تلميح حجم المخزن المؤقت، بالميغابايت. القيمة غير الإيجابية تعني عدم وجود حد للذاكرة للمخازن المؤقتة الداخلية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | تلميح حجم المخزن المؤقت الذي يُعرّف الحد الأقصى المسموح به لجميع المخازن المؤقتة الداخلية. |

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


يحصل على قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا.

**Returns:**
boolean - `true` إذا تم تمكين تعديل لوحة الألوان تلقائيًا؛ وإلا `false`.
### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | `true` إذا تم تمكين تعديل لوحة الألوان تلقائيًا؛ وإلا `false`. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية.

**Returns:**
boolean
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


استرجع قيمة تنسيق الملف بسهولة باستخدام هذه الخاصية الصديقة للمستخدم. مثالية للمطورين الذين يبحثون عن وصول سريع إلى معلومات حول تنسيق الملف.

**Returns:**
long
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل أو يضبط قيمة للون الخلفية.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يحصل أو يضبط قيمة للون الخلفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


يحصل على بيانات تعريف الصورة.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


يحصل على بيانات Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


يضبط بيانات Exif.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | بيانات Exif. |

### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


يحصل على بيانات Xmp.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public final void setXmpData(XmpPacketWrapper value)
```


يضبط بيانات Xmp.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | بيانات Xmp. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public final ProgressEventHandler getIProgressEventHandler()
```


يحصل على معلومات معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


يحصل على معلومات معالج حدث التقدم.

القيمة: معلومات معالج حدث التقدم.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### canSave(ImageOptionsBase options) {#canSave-com.aspose.imaging.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


يحدد ما إذا كان يمكن حفظ الصورة بالتنسيق الملف المحدد الممثل بخيارات الحفظ الممررة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الحفظ التي سيتم استخدامها. |

**Returns:**
boolean - `true` إذا كان يمكن حفظ الصورة بالتنسيق المحدد الممثل بخيارات الحفظ الممررة؛ وإلا `false`.

**Example: This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    saveOptions.setQuality(50);

    // تحديد ما إذا كان يمكن حفظ الصورة بتنسيق Jpeg
    boolean canSave = image.canSave(saveOptions);
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


يقوم بتغيير حجم الصورة. يتم استخدام [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |


**Example: The following example shows how to resize a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";

String[] files = new String[]{"image3.emf", "image4.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Resize_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resize(image.getWidth() / 4, image.getHeight() / 4);
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```


**Example: The following example shows how to resize SVG image and save it to PNG.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1431\\";
String[] fileNames = new String[] {
                "Logotype.svg",
                "sample_car.svg",
                "rg1024_green_grapes.svg",
                "MidMarkerFigure.svg",
                "embeddedFonts.svg"
        };

com.aspose.imaging.PointF[] scales = new com.aspose.imaging.PointF[] {
                new com.aspose.imaging.PointF(0.5f, 0.5f),
                new com.aspose.imaging.PointF(1f, 1f),
                new com.aspose.imaging.PointF(2f, 2f),
                new com.aspose.imaging.PointF(3.5f, 9.2f),
        };

for (String inputFile : fileNames) {
    for (com.aspose.imaging.PointF scale : scales) {
        String outputFile = String.format("%s_%2.2f_%2.2f.png", inputFile, scale.getX(), scale.getY());
        com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + inputFile);
        try {
            image.resize((int) (image.getWidth() * scale.getX()), (int) (image.getHeight() * scale.getY()));
            image.save(dir + outputFile, new com.aspose.imaging.imageoptions.PngOptions());
        }
        finally {
            image.close();
        }
    }
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


يُعيد تحجيم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع تغيير الحجم. |


**Example: This example loads an image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
}
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
}
```


**Example: This example loads a multi-page ODG image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // حفظ كملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// خيارات تصدير القناع
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// استخدم تجميع GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// لون الخلفية سيكون شفافًا.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // تقليل حجم الصورة لتسريع عملية التجزئة
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // إنشاء نسخة من الفئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // الحصول على قناع المقدمة
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // زيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على قطاع مقدمة
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image and export it to PNG format.**

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

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


يُعيد تحجيم الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير الحجم. |


**Example: This example loads an image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات متكيفة.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing settings.**

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
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // قُم بتقليل الحجم بمقدار مرتين باستخدام إعادة أخذ عينات متكيفة.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image using advanced settings.**

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

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


يحصل على الخيارات الافتراضية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| args | java.lang.Object[] | المعلمات. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


يحصل على الخيارات بناءً على إعدادات الملف الأصلي. يمكن أن يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير. على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام الطريقة `DataStreamSupporter.Save(string)`، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل. لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها إلى الطريقة `Image.Save(string, ImageOptionsBase)` كمعامل ثاني.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


يعيد تحجيم العرض بنسبة متناسبة. يتم استخدام [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


يعيد تحجيم الارتفاع بنسبة متناسبة. يتم استخدام [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) الافتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
يقوم هذا المثال بتحميل صورة وتغيير حجمها بنسبة متناسبة باستخدام طرق تغيير حجم مختلفة. يتم تحديد العرض فقط، ويتم حساب الارتفاع تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
{
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


يعيد تحجيم الارتفاع بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| resizeType | int | نوع التحجيم. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
يقوم هذا المثال بتحميل صورة وتغيير حجمها بنسبة متناسبة باستخدام طرق تغيير حجم مختلفة. يتم تحديد الارتفاع فقط، ويتم حساب العرض تلقائيًا.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات أقرب جار.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تكبير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // تصغير بمقدار مرتين باستخدام إعادة أخذ عينات ثنائية الخطية.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// خيارات تصدير القناع
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// استخدم تجميع GraphCut.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// لون الخلفية سيكون شفافًا.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // تقليل حجم الصورة لتسريع عملية التجزئة
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // إنشاء نسخة من الفئة ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // قسّم الصورة المصدر إلى عدة مجموعات (قطاعات).
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // الحصول على قناع المقدمة
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // زيادة حجم القناع إلى حجم الصورة الأصلية
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // تطبيق القناع على الصورة الأصلية للحصول على قطاع مقدمة
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


يعيد تحجيم العرض بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newWidth | int | العرض الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير حجم الصورة. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


يعيد تحجيم الارتفاع بنسبة متناسبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newHeight | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | إعدادات تغيير حجم الصورة. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateFlipType | int | نوع دوران الانعكاس. |


**Example: This example demonstrates the use of Rotate operation on an image.**
هذا المثال يوضح استخدام عملية Rotate على صورة. يقوم المثال بتحميل ملف صورة موجود من موقع قرص ما ويجري عملية Rotate على الصورة وفقًا لقيمة Enum com.aspose.imaging.RotateFlipType
``` java
// إنشاء كائن من فئة image وتهيئته بملف صورة موجود عبر مسار الملف
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // دوّر الصورة بزاوية 180 درجة حول المحور X
    image.rotateFlip(com.aspose.imaging.RotateFlipType.Rotate180FlipX);

    // حفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


دوّر الصورة حول المركز.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران بالدرجات. القيم الموجبة تدور باتجاه عقارب الساعة. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


يقص المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل. |


**Example: The following example crops a raster image.**
المثال التالي يقتطع صورة نقطية. يتم تحديد منطقة القص عبر com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // قص الصورة. منطقة القص هي المنطقة المستطيلة المركزية في الصورة.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    image.crop(area);

    // احفظ الصورة المقتطعة بصيغة PNG
    image.save(dir + "sample.Crop.png");
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


قص الصورة مع الإزاحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftShift | int | الإزاحة اليسرى. |
| rightShift | int | الإزاحة اليمنى. |
| topShift | int | الإزاحة العلوية. |
| bottomShift | int | الإزاحة السفلية. |


**Example: The following example crops a raster image.**
المثال التالي يقتطع صورة نقطية. يتم تحديد منطقة القص عبر هوامش Left, Top, Right, Bottom.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // اقتطع مرة أخرى. ضع هامشًا بنسبة 10% من حجم الصورة.
    int horizontalMargin = rasterImage.getWidth() / 10;
    int verticalMargin = rasterImage.getHeight() / 10;
    image.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // احفظ الصورة المقتطعة إلى PNG.
    image.save(dir + "sample.Crop.png");
}
```

### save() {#save--}
```
public final void save()
```


يحفظ بيانات الصورة إلى الدفق الأساسي.


**Example: The following example shows how to save an entire BMP image or part of it to a file or stream.**

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // حوّل إلى صورة أبيض-أسود
    bmpImage.binarizeOtsu();

    // احفظ في نفس الموقع باستخدام الخيارات الافتراضية.
    image.save();

    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // تحتوي لوحة الألوان على لونين فقط: الأسود والأبيض في هذه الحالة.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.createMonochrome());

    // بالنسبة لجميع الصور أحادية اللون (بما في ذلك الصور أبيض-أسود) يكفي تخصيص 1 بت لكل بكسل.
    saveOptions.setBitsPerPixel(1);

    // احفظ إلى موقع آخر باستخدام الخيارات المحددة.
    image.save(dir + "sample.bw.palettized.bmp", saveOptions);

    // احفظ الجزء المركزي فقط من الصورة.
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(image.getWidth() / 4, image.getHeight() / 4, image.getWidth() / 2, image.getHeight() / 2);
    image.save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // احفظ الصورة بالكامل إلى تدفق الذاكرة
    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions);
        System.out.println("The size of the whole image in bytes: " + stream.size());
    } finally {
        stream.close();
    }

    // احفظ الجزء المركزي من الصورة إلى تدفق الذاكرة
    stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions, bounds);
        System.out.println("The size of the central part of the image in bytes: " + stream.size());
    } finally {
        stream.close();
    }
} finally {
    image.close();
}

//قد يبدو الإخراج هكذا:
//حجم الصورة بالكامل بالبايت: 1662
//حجم الجزء المركزي من الصورة بالبايت: 462
```

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


يحفظ الصورة إلى موقع الملف المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ الصورة إليه. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | الخيارات. |


**Example: This example shows the simple steps to Save an Image.**
هذا المثال يوضح الخطوات البسيطة لحفظ صورة. لتوضيح هذه العملية، نقوم بتحميل ملف موجود من موقع قرص ما ونحفظ الصورة بصيغة PSD.
``` java
// حمّل ملفًا موجودًا من القرص.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // احفظ الصورة كـ PSD إلى مسار الملف باستخدام إعدادات PsdOptions الافتراضية.
    image.save("C:\\temp\\output.psd", new com.aspose.imaging.imageoptions.PsdOptions());
} finally {
    image.dispose();
}
```

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | الخيارات. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |


**Example: The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // احفظ النصف العلوي من الصورة إلى ملف PNG.
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    image.save(dir + "output.png", saveOptions, bounds);
} finally {
    image.dispose();
}
```

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لحفظ بيانات الصورة فيه. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | الخيارات. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ملف | java.io.RandomAccessFile | الملف لحفظ بيانات الصورة فيه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الحفظ. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.OutputStream | المجرى لحفظ بيانات الصورة فيه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الحفظ. |


**Example: This example shows the process of saving an Image to memory buffer.**
يوضح هذا المثال عملية حفظ صورة إلى مخزن الذاكرة. لتوضيح هذه العملية، يقوم المثال بتحميل ملف موجود من موقع على القرص وحفظ الصورة بتنسيق PSD.
``` java
java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
try {            //Create an instance of image class and initialize it with an existing image file through File path
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
    try {
        //احفظ الصورة إلى مجرى الذاكرة بصيغة PSD باستخدام إعدادات PsdOptions الافتراضية
        image.save(stream, new com.aspose.imaging.imageoptions.PsdOptions());
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق الملف المحدد وفقًا لخيارات الحفظ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.OutputStream | المجرى لحفظ بيانات الصورة فيه. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الحفظ. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |


**Example: The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    java.io.OutputStream outputStream = new java.io.FileOutputStream(dir + "sample.output.png");
    try {
        // احفظ النصف العلوي من الصورة إلى مجرى ملف.
        image.save(outputStream, saveOptions, bounds);
    } finally {
        outputStream.close();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


يضبط لوحة ألوان الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان لتعيينها. |
| updateColors | boolean | إذا تم تعيينه إلى `true` سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستبقى فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

### getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber) {#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---}
```
public InputStream getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)
```


يحول إلى aps.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | خيارات الصورة. |
| clippingRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | مستطيل القص. |
| pageNumber | int[] | رقم الصفحة. |

**Returns:**
java.io.InputStream - المجرى المتسلسل
