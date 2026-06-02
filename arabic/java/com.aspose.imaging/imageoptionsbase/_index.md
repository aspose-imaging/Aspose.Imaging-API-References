---
title: "ImageOptionsBase"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات الأساس للصورة."
type: docs
weight: 62
url: /ar/java/com.aspose.imaging/imageoptionsbase/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class ImageOptionsBase extends DisposableObject implements IMetadataContainer
```

خيارات الأساس للصورة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isKeepMetadata()](#isKeepMetadata--) | يحصل على قيمة تحدد ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [setKeepMetadata(boolean value)](#setKeepMetadata-boolean-) | قيمة تحدد ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير. |
| [getXmpData()](#getXmpData--) | يسترجع حاوية بيانات التعريف XMP. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | يضبط حاوية بيانات التعريف XMP. |
| [getExifData()](#getExifData--) | يحصل على بيانات Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | يضبط بيانات Exif. |
| [getSource()](#getSource--) | يسترجع المصدر لإنشاء الصورة فيه. |
| [setSource(Source value)](#setSource-com.aspose.imaging.Source-) | يسترجع أو يضبط المصدر لإنشاء الصورة فيه. |
| [getPalette()](#getPalette--) | يحصل على لوحة الألوان. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | يضبط لوحة الألوان. |
| [getResolutionSettings()](#getResolutionSettings--) | يسترجع إعدادات الدقة. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | يضبط إعدادات الدقة. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | يسترجع خيارات تحويل المتجه إلى نقطية. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | يضبط خيارات تحويل المتجه إلى نقطية. |
| [getBufferSizeHint()](#getBufferSizeHint--) | يحصل على تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | يضبط تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [getMultiPageOptions()](#getMultiPageOptions--) | خيارات الصفحات المتعددة |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-) | خيارات الصفحات المتعددة |
| [getFullFrame()](#getFullFrame--) | يسترجع قيمة تشير إلى ما إذا كان [full frame]. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | يضبط قيمة تشير إلى ما إذا كان [full frame]. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يسترجع معالج حدث التقدم. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | يضبط معالج حدث التقدم. |
| [deepClone()](#deepClone--) | ينسخ هذه المثيلة. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | يحاول تعيين كائن `metadata` إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat). |
### isKeepMetadata() {#isKeepMetadata--}
```
public final boolean isKeepMetadata()
```


يحصل على قيمة تحدد ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير.
### setKeepMetadata(boolean value) {#setKeepMetadata-boolean-}
```
public final void setKeepMetadata(boolean value)
```


قيمة تحدد ما إذا كان يجب الاحتفاظ ببيانات تعريف الصورة الأصلية عند التصدير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |

### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


يسترجع حاوية بيانات التعريف XMP.

القيمة: حاوية بيانات XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the XMP metadata container.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


يضبط حاوية بيانات التعريف XMP.

القيمة: حاوية بيانات XMP.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | حاوية بيانات التعريف XMP. |

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

### getSource() {#getSource--}
```
public Source getSource()
```


يسترجع المصدر لإنشاء الصورة فيه.

**Returns:**
[Source](../../com.aspose.imaging/source) - The source to create image in.
### setSource(Source value) {#setSource-com.aspose.imaging.Source-}
```
public void setSource(Source value)
```


يسترجع أو يضبط المصدر لإنشاء الصورة فيه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Source](../../com.aspose.imaging/source) | المصدر لإنشاء الصورة فيه. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل على لوحة الألوان.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يضبط لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |


**Example: The following example shows how to palletize a BMP image to reduce its output size.**

``` java

// إنشاء صورة BMP بحجم 100 × 100 بكسل.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلية للصورة.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // ملء الصورة بالكامل بفرشاة التدرج الخطي.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);
    gr.fillRectangle(brush, bmpImage.getBounds());

    // احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملوّنة باللوحة
    // تكاد تكون غير قابلة للتمييز بصريًا عن صورة غير ملوّنة باللوحة.
    com.aspose.imaging.IColorPalette palette = com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette(bmpImage, 256);

    // لوحة ألوان 8‑بت تحتوي على ما لا يزيد عن 256 لونًا.
    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();
    saveOptions.setPalette(palette);
    saveOptions.setBitsPerPixel(8);

    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream, saveOptions);
        System.out.println("The palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }

    stream = new java.io.ByteArrayOutputStream();
    try {
        bmpImage.save(stream);
        System.out.println("The non-palettized image size is " + stream.size() + " bytes.");
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}

// المخرجات تبدو هكذا:
// حجم الصورة الملونة باللوحة هو 11078 بايت.
// حجم الصورة غير الملونة باللوحة هو 40054 بايت.
```

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


يسترجع إعدادات الدقة.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


يضبط إعدادات الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |


**Example: The following example loads a BMP image and saves it to JPEG using various save options.**

``` java
String dir = "c:\\temp\\";

// حمّل صورة BMP من ملف.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // قم ببعض معالجة الصورة.

    // استخدم خيارات إضافية لتحديد معلمات الصورة المطلوبة.
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();

    // عدد البتات لكل قناة هو 8.
    // عند استخدام لوحة ألوان، يتم تخزين فهرس اللون في بيانات الصورة بدلاً من اللون نفسه.
    saveOptions.setBitsPerChannel((byte) 8);

    // حدد نوع الضغط المتدرج.
    saveOptions.setCompressionType(com.aspose.imaging.fileformats.jpeg.JpegCompressionMode.Progressive);

    // حدد جودة الصورة. إنها قيمة بين 1 و 100.
    saveOptions.setQuality(100);

    // حدد الدقة الأفقية/العمودية إلى 96 نقطة لكل بوصة.
    saveOptions.setResolutionSettings(new com.aspose.imaging.ResolutionSetting(96.0, 96.0));
    saveOptions.setResolutionUnit(com.aspose.imaging.ResolutionUnit.Inch);

    // إذا كانت الصورة المصدر ملونة، فسيتم تحويلها إلى تدرجات الرمادي.
    saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Grayscale);

    // استخدم لوحة ألوان لتقليل حجم الإخراج.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.create8BitGrayscale(false));

    image.save(dir + "sample.palettized.jpg", saveOptions);
} finally {
    image.dispose();
}
```

### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public VectorRasterizationOptions getVectorRasterizationOptions()
```


يسترجع خيارات تحويل المتجه إلى نقطية.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The vector rasterization options.
### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


يضبط خيارات تحويل المتجه إلى نقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | خيارات تحويل المتجه إلى نقطية. |

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

### getMultiPageOptions() {#getMultiPageOptions--}
```
public MultiPageOptions getMultiPageOptions()
```


خيارات الصفحات المتعددة

**Returns:**
[MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions)
### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.imaging.imageoptions.MultiPageOptions-}
```
public void setMultiPageOptions(MultiPageOptions value)
```


خيارات الصفحات المتعددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.imaging.imageoptions/multipageoptions) |  |

### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


يسترجع قيمة تشير إلى ما إذا كان [full frame].

القيمة: `true` إذا كان [full frame]؛ وإلا `false`.

**Returns:**
منطقية - قيمة تشير إلى ما إذا كان [full frame].
### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان [full frame].

القيمة: `true` إذا كان [full frame]؛ وإلا `false`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان [full frame]. |

### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


يسترجع معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler.
### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


يضبط معالج حدث التقدم.

القيمة: معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | معالج حدث التقدم. |


**Example: The following example shows how to print information about progress events for load/export operations.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// مثال على استخدام معالجات أحداث تقدم العملية المنفصلة لعمليات التحميل/التصدير
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// قد يبدو سجل STDOUT هكذا:
//        حدث التحميل Initialization : 1/4
//        حدث التحميل PreProcessing : 2/4
//        حدث التحميل Processing : 3/4
//        حدث التحميل Finalization : 4/4
//        حدث التصدير Initialization : 1/4
//        حدث التصدير PreProcessing : 2/4
//        حدث التصدير Processing : 3/4
//        حدث التصدير RelativeProgress : 1/1
//        حدث التحميل RelativeProgress : 1/1
//        حدث التصدير Finalization : 4/4
```

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


ينسخ هذه المثيلة.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns shallow copy of this instance
### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public final boolean trySetMetadata(IImageMetadataFormat metadata)
```


يحاول تعيين كائن `metadata` إذا كان كائن [Image](../../com.aspose.imaging/image) هذا يدعم ويطبق كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | البيانات الوصفية. |

**Returns:**
منطقية - True إذا كان كائن [IMetadataContainer](../../com.aspose.imaging/imetadatacontainer) يدعم و/أو ينفّذ كائن [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)؛ وإلا false.
