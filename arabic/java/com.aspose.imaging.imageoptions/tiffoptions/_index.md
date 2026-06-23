---
title: "TiffOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات صيغة ملف TIFF."
type: docs
weight: 48
url: /ar/java/com.aspose.imaging.imageoptions/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
[com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffOptions extends ImageOptionsBase implements IMetadataContainer
```

خيارات تنسيق ملف TIFF. لاحظ أن وسوم العرض والارتفاع سيتم استبدالها عند إنشاء الصورة بواسطة معلمات العرض والارتفاع لذا لا حاجة لتحديدها مباشرة. لاحظ أن العديد من الخيارات تُعيد قيمة افتراضية لكن هذا لا يعني أن هذا الخيار تم تعيينه صراحة كقيمة للوسم. للتحقق من وجود الوسم استخدم الخاصية Tags أو الطريقة المقابلة IsTagPresent.

`تحذير! لا تقم بتعديل خيارات TIFF أثناء الحفظ لأن ذلك قد يسبب آثارًا جانبية وأخطاء يصعب العثور عليها. تم ترك السطر التالي مُعَلَّقًا خصيصًا لأنه تسبب في تحديد غير صحيح لبداية البيانات. الخيارات الممررة لم تحتوي على spp (على الرغم من أن الخيارات غير صحيحة في هذه الحالة لكن هذا السيناريو لا يزال يسبب أخطاء) والسطر التالي تسبب في إضافة وسم +spp ووسم +bpp وعندما كتبت الخيارات بعد كتابة البيانات بالكامل تم استبدال بداية البيانات للترميز غير المضغوط!!! راجع TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;`
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | ينشئ نسخة جديدة من الفئة `TiffOptions`. |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | ينشئ نسخة جديدة من الفئة `TiffOptions`. |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | ينشئ نسخة جديدة من الفئة `TiffOptions`. |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | ينشئ نسخة جديدة من الفئة `TiffOptions`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل على عدد الوسوم الصالحة. |
| [getTagCount()](#getTagCount--) | يحصل على عدد الوسوم. |
| [getFileStandard()](#getFileStandard--) | يحصل أو يضبط معيار ملف TIFF. |
| [setFileStandard(int value)](#setFileStandard-int-) | يحصل أو يضبط معيار ملف TIFF. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | يحصل أو يضبط الحد الافتراضي لتخصيص الذاكرة. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | يحصل أو يضبط الحد الافتراضي لتخصيص الذاكرة. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا. |
| [isValid()](#isValid--) | يحصل على قيمة تشير إلى ما إذا تم تكوين `TiffOptions` بشكل صحيح. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | يحصل أو يضبط عوامل التقليل الفرعي للتمثيل الضوئي YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | يحصل أو يضبط عوامل التقليل الفرعي للتمثيل الضوئي YCbCr. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | يحصل أو يضبط YCbCrCoefficients. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | يحصل أو يضبط YCbCrCoefficients. |
| [isTiled()](#isTiled--) | يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى بلاطات. |
| [getArtist()](#getArtist--) | يحصل أو يضبط الفنان. |
| [setArtist(String value)](#setArtist-java.lang.String-) | يحصل أو يضبط الفنان. |
| [isTagPresent(int tag)](#isTagPresent-int-) | يحدد ما إذا كان الوسم موجودًا في الخيارات أم لا. |
| [getByteOrder()](#getByteOrder--) | يحصل أو يضبط قيمة تشير إلى ترتيب البايتات في TIFF. |
| [setByteOrder(int value)](#setByteOrder-int-) | يحصل أو يضبط قيمة تشير إلى ترتيب البايتات في TIFF. |
| [getIccProfile()](#getIccProfile--) | يحصل على تدفق ملف تعريف ICC. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | يضبط تدفق ملف تعريف ICC. |
| [isDisableIccExport()](#isDisableIccExport--) | يحصل على قيمة تشير إلى ما إذا تم تعطيل تصدير ملف تعريف ICC (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا). |
| [setDisableIccExport(boolean value)](#setDisableIccExport-boolean-) | يضبط قيمة تشير إلى ما إذا تم تعطيل تصدير ملف تعريف ICC (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا). |
| [getBitsPerSample()](#getBitsPerSample--) | يحصل على عدد البتات لكل عينة. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | يضبط عدد البتات لكل عينة. |
| [getExtraSamples()](#getExtraSamples--) | يحصل على قيم العينات الإضافية. |
| [getCompression()](#getCompression--) | يحصل على الضغط. |
| [setCompression(int value)](#setCompression-int-) | يضبط الضغط. |
| [getCompressedQuality()](#getCompressedQuality--) | يحصل على جودة الصورة المضغوطة. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | يضبط جودة الصورة المضغوطة. |
| [getCopyright()](#getCopyright--) | يحصل على حقوق النشر. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | يضبط حقوق النشر. |
| [getColorMap()](#getColorMap--) | يحصل أو يضبط خريطة الألوان. |
| [setColorMap(int[] value)](#setColorMap-int---) | يحصل أو يضبط خريطة الألوان. |
| [getPalette()](#getPalette--) | يحصل أو يضبط لوحة الألوان. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | يحصل أو يضبط لوحة الألوان. |
| [getDateTime()](#getDateTime--) | يحصل أو يضبط التاريخ والوقت. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | يحصل أو يضبط التاريخ والوقت. |
| [getDocumentName()](#getDocumentName--) | يحصل أو يضبط اسم المستند. |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | يحصل أو يضبط اسم المستند. |
| [getAlphaStorage()](#getAlphaStorage--) | يحصل أو يضبط خيار تخزين ألفا. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | يحصل أو يضبط خيار تخزين ألفا. |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة. |
| [getFillOrder()](#getFillOrder--) | يحصل أو يضبط ترتيب تعبئة بتات البايت. |
| [setFillOrder(int value)](#setFillOrder-int-) | يحصل أو يضبط ترتيب تعبئة بتات البايت. |
| [getHalfToneHints()](#getHalfToneHints--) | يحصل أو يضبط تلميحات نصف اللون. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | يحصل أو يضبط تلميحات نصف اللون. |
| [getImageDescription()](#getImageDescription--) | يحصل أو يضبط وصف الصورة. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | يحصل أو يضبط وصف الصورة. |
| [getInkNames()](#getInkNames--) | يحصل أو يضبط أسماء الحبر. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | يحصل أو يضبط أسماء الحبر. |
| [getScannerManufacturer()](#getScannerManufacturer--) | يحصل أو يضبط شركة تصنيع الماسح. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | يحصل أو يضبط شركة تصنيع الماسح. |
| [getMaxSampleValue()](#getMaxSampleValue--) | يحصل أو يضبط قيمة العينة القصوى. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | يحصل أو يضبط قيمة العينة القصوى. |
| [getMinSampleValue()](#getMinSampleValue--) | يحصل أو يضبط قيمة العينة الدنيا. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | يحصل أو يضبط قيمة العينة الدنيا. |
| [getScannerModel()](#getScannerModel--) | يحصل أو يضبط طراز الماسح. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | يحصل أو يضبط طراز الماسح. |
| [getOrientation()](#getOrientation--) | يحصل أو يضبط الاتجاه. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل أو يضبط الاتجاه. |
| [getPageName()](#getPageName--) | يحصل أو يضبط اسم الصفحة. |
| [setPageName(String value)](#setPageName-java.lang.String-) | يحصل أو يضبط اسم الصفحة. |
| [getPageNumber()](#getPageNumber--) | يحصل أو يضبط وسم رقم الصفحة. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | يحصل أو يضبط وسم رقم الصفحة. |
| [getPhotometric()](#getPhotometric--) | يحصل أو يضبط الفوتومتري. |
| [setPhotometric(int value)](#setPhotometric-int-) | يحصل أو يضبط الفوتومتري. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | يحصل أو يضبط تكوين المستوى. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | يحصل أو يضبط تكوين المستوى. |
| [getResolutionUnit()](#getResolutionUnit--) | يحصل أو يضبط وحدة الدقة. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | يحصل أو يضبط وحدة الدقة. |
| [getRowsPerStrip()](#getRowsPerStrip--) | يحصل أو يضبط الصفوف لكل شريط. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | يحصل أو يضبط الصفوف لكل شريط. |
| [getTileWidth()](#getTileWidth--) | يحصل ot يضبط عرض البلاطة. |
| [setTileWidth(long value)](#setTileWidth-long-) | يحصل ot يضبط عرض البلاطة. |
| [getTileLength()](#getTileLength--) | يحصل ot يضبط طول البلاطة. |
| [setTileLength(long value)](#setTileLength-long-) | يحصل ot يضبط طول البلاطة. |
| [getSampleFormat()](#getSampleFormat--) | يحصل أو يضبط تنسيق العينة. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | يحصل أو يضبط تنسيق العينة. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | يحصل على العينات لكل بكسل. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | يحصل أو يضبط قيمة العينة القصوى. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | يحصل أو يضبط قيمة العينة القصوى. |
| [getSminSampleValue()](#getSminSampleValue--) | يحصل أو يضبط قيمة العينة الدنيا. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | يحصل أو يضبط قيمة العينة الدنيا. |
| [getSoftwareType()](#getSoftwareType--) | يحصل أو يضبط نوع البرنامج. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | يحصل أو يضبط نوع البرنامج. |
| [getStripByteCounts()](#getStripByteCounts--) | يحصل أو يضبط عدد بايتات الشريط. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | يحصل أو يضبط عدد بايتات الشريط. |
| [getStripOffsets()](#getStripOffsets--) | يحصل أو يضبط إزاحات الشريط. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | يحصل أو يضبط إزاحات الشريط. |
| [getTileByteCounts()](#getTileByteCounts--) | يحصل أو يضبط عدد بايتات البلاطة. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | يحصل أو يضبط عدد بايتات البلاطة. |
| [getTileOffsets()](#getTileOffsets--) | يحصل أو يضبط إزاحات البلاطة. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | يحصل أو يضبط إزاحات البلاطة. |
| [getSubFileType()](#getSubFileType--) | يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [setSubFileType(long value)](#setSubFileType-long-) | يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي. |
| [getTargetPrinter()](#getTargetPrinter--) | يحصل أو يضبط الطابعة المستهدفة. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | يحصل أو يضبط الطابعة المستهدفة. |
| [getThreshholding()](#getThreshholding--) | يحصل أو يضبط العتبة. |
| [setThreshholding(int value)](#setThreshholding-int-) | يحصل أو يضبط العتبة. |
| [getTotalPages()](#getTotalPages--) | يحصل على إجمالي الصفحات. |
| [getXposition()](#getXposition--) | يحصل أو يضبط موضع x. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط موضع x. |
| [getResolutionSettings()](#getResolutionSettings--) | يحصل أو يضبط إعدادات الدقة. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.imaging.ResolutionSetting-) | يحصل أو يضبط إعدادات الدقة. |
| [getXresolution()](#getXresolution--) | يحصل أو يضبط دقة x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة x. |
| [getYposition()](#getYposition--) | يحصل أو يضبط موضع y. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط موضع y. |
| [getYresolution()](#getYresolution--) | يحصل أو يضبط دقة y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | يحصل أو يضبط دقة y. |
| [getFaxT4Options()](#getFaxT4Options--) | يحصل أو يضبط خيارات الفاكس t4. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | يحصل أو يضبط خيارات الفاكس t4. |
| [getPredictor()](#getPredictor--) | يحصل أو يضبط المتنبئ لضغط LZW. |
| [setPredictor(int value)](#setPredictor-int-) | يحصل أو يضبط المتنبئ لضغط LZW. |
| [getImageLength()](#getImageLength--) | يحصل أو يضبط طول الصورة. |
| [setImageLength(long value)](#setImageLength-long-) | يحصل أو يضبط طول الصورة. |
| [getImageWidth()](#getImageWidth--) | يحصل أو يضبط عرض الصورة. |
| [setImageWidth(long value)](#setImageWidth-long-) | يحصل أو يضبط عرض الصورة. |
| [getExifIfd()](#getExifIfd--) | يحصل أو يعيّن المؤشر إلى EXIF IFD. |
| [getTags()](#getTags--) | يحصل أو يضبط العلامات. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يحصل أو يضبط العلامات. |
| [getValidTagCount()](#getValidTagCount--) | يحصل على عدد العلامات الصالحة. |
| [getBitsPerPixel()](#getBitsPerPixel--) | يحصل على عدد البتات لكل بكسل. |
| [getXPTitle()](#getXPTitle--) | يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | يضبط معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [getXPComment()](#getXPComment--) | يحصل على التعليق على الصورة، التي يستخدمها مستكشف Windows. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | يضبط التعليق على الصورة، التي يستخدمه مستكشف Windows. |
| [getXPAuthor()](#getXPAuthor--) | يحصل على مؤلف الصورة، الذي يستخدمه مستكشف Windows. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | يضبط مؤلف الصورة، الذي يستخدمه مستكشف Windows. |
| [getXPKeywords()](#getXPKeywords--) | يحصل على موضوع الصورة، الذي يستخدمه مستكشف Windows. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | يضبط موضوع الصورة، الذي يستخدمه مستكشف Windows. |
| [getXPSubject()](#getXPSubject--) | يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | يضبط معلومات حول الصورة، التي يستخدمها مستكشف Windows. |
| [getExifData()](#getExifData--) | يحصل على بيانات Exif. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | يضبط بيانات Exif. |
| [removeTag(int tag)](#removeTag-int-) | يزيل العلامة. |
| [removeTags(int[] tags)](#removeTags-int...-) | يزيل العلامات. |
| [validate()](#validate--) | يتحقق مما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | يضيف العلامات. |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-) | يضيف علامة جديدة. |
| [getTagByType(int tagKey)](#getTagByType-int-) | يحصل على مثيل العلامة حسب النوع. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
يوضح هذا المثال استخدام فئات مختلفة من مساحة الأسماء SaveOptions لأغراض التصدير. يتم تحميل صورة من نوع Gif إلى مثيل من الفئة Image ثم تُصدَّر إلى عدة صيغ.
``` java
String dir = "c:\\temp\\";

//حمّل صورة موجودة (من نوع Gif) في مثيل من الفئة Image.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية.
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية.
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية.
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية.
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to TIFF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.tiff";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // تصدير الصفحتين الأوليتين فقط. سيتم عرض هاتين الصفحتين كإطارات في ملف TIFF الناتج.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


ينشئ نسخة جديدة من الفئة `TiffOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | int | تنسيق ملف TIFF المتوقع. |
| byteOrder | int | ترتيب بايتات تنسيق ملف TIFF. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


يُنشئ نسخة جديدة من الفئة `TiffOptions`. بشكل افتراضي، يُستخدم نظام little endian.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| expectedFormat | int | تنسيق ملف TIFF المتوقع. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


ينشئ نسخة جديدة من الفئة `TiffOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | الخيارات التي يتم النسخ منها. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


ينشئ نسخة جديدة من الفئة `TiffOptions`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | العلامات التي تُستخدم لتهيئة الخيارات. |

### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


يحصل على عدد الوسوم الصالحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | العلامات التي يتم التحقق منها. |

**Returns:**
int - عدد العلامات الصالحة.
### getTagCount() {#getTagCount--}
```
public final int getTagCount()
```


يحصل على عدد الوسوم.

**Returns:**
int - عدد العلامات.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


يحصل أو يضبط معيار ملف TIFF.

**Returns:**
int - معيار ملف TIFF.
### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


يحصل أو يضبط معيار ملف TIFF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | معيار ملف TIFF. |

### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


يحصل أو يضبط الحد الافتراضي لتخصيص الذاكرة.

**Returns:**
int - حد تخصيص الذاكرة الافتراضي.
### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


يحصل أو يضبط الحد الافتراضي لتخصيص الذاكرة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | حد تخصيص الذاكرة الافتراضي. |

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا.

**Returns:**
boolean - `true` إذا كان يجب ضرب المكونات مسبقًا؛ وإلا `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ضرب المكونات مسبقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `true` إذا كان يجب ضرب المكونات مسبقًا؛ وإلا `false`. |

### isValid() {#isValid--}
```
public boolean isValid()
```


يحصل على قيمة تشير إلى ما إذا كان `TiffOptions` تم تكوينه بشكل صحيح. استخدم طريقة Validate للعثور على سبب الفشل.

**Returns:**
boolean - `true` إذا تم تكوين TiffOptions بشكل صحيح؛ وإلا `false`.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


يحصل أو يضبط عوامل التقليل الفرعي للتمثيل الضوئي YCbCr.

**Returns:**
int[] - عوامل التقسيم الفرعي للضوء الفوتومتري YCbCr.
### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


يحصل أو يضبط عوامل التقليل الفرعي للتمثيل الضوئي YCbCr.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | عوامل التقسيم الفرعي للضوء الفوتومتري YCbCr. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// عيّن 8 بتات لكل مكوّن لوني.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// عيّن ترتيب البايت Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// قم بتعيين ضغط LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// السماح بتقليل حجم الصور ذات النغمة المستمرة.
// حاليًا يتم استخدام هذا الحقل فقط مع ترميز LZW لأن LZW ربما يكون نظام الترميز الوحيد لملفات TIFF.
// الذي يستفيد بشكل كبير من خطوة التنبؤ.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// قم بتعيين نموذج اللون RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// بالنسبة إلى YCbCr، يمكنك استخدام أحد الخيارات التالية:
// حقل YCbCrSubSampling   عوامل أخذ عينات JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// إنشاء إطار TIFF بحجم 100×100 بكسل.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


يحصل أو يضبط YCbCrCoefficients.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - معاملات YCbCrCoefficients.
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


يحصل أو يضبط YCbCrCoefficients.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | معاملات YCbCrCoefficients. |

### isTiled() {#isTiled--}
```
public boolean isTiled()
```


يحصل على قيمة تشير إلى ما إذا كانت الصورة مقسمة إلى بلاطات.

**Returns:**
boolean - `true` إذا كانت الصورة مقسمة إلى بلاطات؛ وإلا `false`.
### getArtist() {#getArtist--}
```
public String getArtist()
```


يحصل أو يضبط الفنان.

**Returns:**
java.lang.String - الفنان.
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


يحصل أو يضبط الفنان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الفنان. |

### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


يحدد ما إذا كان الوسم موجودًا في الخيارات أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| علامة | int | معرف العلامة للتحقق منه. |

**Returns:**
boolean - `true` إذا كانت العلامة موجودة؛ وإلا `false`.
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


يحصل أو يضبط قيمة تشير إلى ترتيب البايتات في TIFF.

**Returns:**
int
### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


يحصل أو يضبط قيمة تشير إلى ترتيب البايتات في TIFF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// عيّن 8 بتات لكل مكوّن لوني.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// عيّن ترتيب البايت Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// قم بتعيين ضغط LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// السماح بتقليل حجم الصور ذات النغمة المستمرة.
// حاليًا يتم استخدام هذا الحقل فقط مع ترميز LZW لأن LZW ربما يكون نظام الترميز الوحيد لملفات TIFF.
// الذي يستفيد بشكل كبير من خطوة التنبؤ.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// قم بتعيين نموذج اللون RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// بالنسبة إلى YCbCr، يمكنك استخدام أحد الخيارات التالية:
// حقل YCbCrSubSampling   عوامل أخذ عينات JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// إنشاء إطار TIFF بحجم 100×100 بكسل.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


يحصل على تدفق ملف تعريف ICC.

**Returns:**
byte[] - ملف تعريف icc.
### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


يضبط تدفق ملف تعريف ICC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[] | ملف تعريف icc. |

### isDisableIccExport() {#isDisableIccExport--}
```
public final boolean isDisableIccExport()
```


يحصل على قيمة تشير إلى ما إذا تم تعطيل تصدير ملف تعريف ICC (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا).

**Returns:**
boolean - قيمة تشير إلى ما إذا كان تصدير ملف تعريف ICC معطلاً (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا).
### setDisableIccExport(boolean value) {#setDisableIccExport-boolean-}
```
public final void setDisableIccExport(boolean value)
```


يضبط قيمة تشير إلى ما إذا تم تعطيل تصدير ملف تعريف ICC (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كان تصدير ملف تعريف ICC معطلاً (يتم تطبيق ملف تعريف ICC على بكسلات المصدر مسبقًا). |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


يحصل على عدد البتات لكل عينة.

**Returns:**
int[] - قيمة البتات لكل عينة.

عند ضبط هذه القيمة، ضع في اعتبارك أنها ستضبط أيضًا قيمة SamplesPerPixel إلى طول المصفوفة. هاتان الخاصيتان مرتبطتان ارتباطًا وثيقًا جدًا لذا قد يتم ضبطهما معًا فقط.
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


يضبط عدد البتات لكل عينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | int[] | قيمة البتات لكل عينة. |

عند ضبط هذه القيمة، ضع في اعتبارك أنها ستضبط أيضًا قيمة SamplesPerPixel إلى طول المصفوفة. هاتان الخاصيتان مرتبطتان ارتباطًا وثيقًا جدًا لذا قد يتم ضبطهما معًا فقط. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم، وليس مؤقتًا.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // ملء الإطار النشط بفرشاة تدرج خطية.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // خيارات التدرج الرمادي
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // إنشاء نسخة بتدرج رمادي من الإطار النشط.
    // يتم الحفاظ على بيانات البكسل ولكنها تُحوَّل إلى الصيغة المطلوبة.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // إضافة الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getExtraSamples() {#getExtraSamples--}
```
public final int[] getExtraSamples()
```


يحصل على قيم العينات الإضافية.

القيمة: قيمة العينات الإضافية.

**Returns:**
int[] - قيم العينات الإضافية.
### getCompression() {#getCompression--}
```
public int getCompression()
```


يحصل على الضغط.

**Returns:**
int - الضغط.
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


يضبط الضغط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الضغط. |


**Example: This example shows how to create a TIFF image with 2 frames and save it to a file.**

``` java
String dir = "c:\\temp\\";

// خيارات الإطار الأول
com.aspose.imaging.imageoptions.TiffOptions createOptions1 =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// عيّن 8 بتات لكل مكوّن لوني.
createOptions1.setBitsPerSample(new int[]{8, 8, 8});

// عيّن ترتيب البايت Big Endian (Motorola)
createOptions1.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// قم بتعيين ضغط LZW.
createOptions1.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// قم بتعيين نموذج اللون RGB.
createOptions1.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
createOptions1.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// إنشاء الإطار الأول بصيغة TIFF بحجم 100×100 بكسل.
// لاحظ أنه لا يلزمك تحرير الإطارات صراحةً إذا تم تضمينها في TiffImage.
// عند تحرير الحاوية سيتم تحرير جميع الإطارات تلقائيًا.
com.aspose.imaging.fileformats.tiff.TiffFrame frame1 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions1, 100, 100);

// املأ الإطار الأول بتدرج اللون الأزرق-الأصفر.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(frame1.getWidth(), frame1.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(frame1);
graphics.fillRectangle(gradientBrush, frame1.getBounds());

// خيارات الإطار الأول
com.aspose.imaging.imageoptions.TiffOptions createOptions2
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// ضبط 1 بت لكل بكسل لصورة أبيض وأسود.
createOptions2.setBitsPerSample(new int[]{1});

// ضبط ترتيب البايت Little Endian (Intel)
createOptions2.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.LittleEndian);

// ضبط ضغط CCITT Group 3 Fax.
createOptions2.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.CcittFax3);

// ضبط نموذج اللون أبيض وأسود حيث 0 هو الأسود، 1 هو الأبيض.
createOptions2.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);

// إنشاء الإطار الثاني بصيغة TIFF بحجم 200×200 بكسل.
com.aspose.imaging.fileformats.tiff.TiffFrame frame2 = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions2, 200, 200);

// املأ الإطار الثاني بتدرج اللون الأزرق-الأصفر.
// سيتم تحويله تلقائيًا إلى تنسيق أبيض وأسود بسبب الإعدادات المقابلة للإطار.
com.aspose.imaging.Graphics graphics2 = new com.aspose.imaging.Graphics(frame2);
graphics2.fillRectangle(gradientBrush, frame2.getBounds());

// إنشاء صورة TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(
        new com.aspose.imaging.fileformats.tiff.TiffFrame[]{frame1, frame2});
try {
    tiffImage.save(dir + "output.mutliframe.tif");
} finally {
    tiffImage.dispose();
}
```

### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


يحصل على جودة الصورة المضغوطة. يُستخدم مع ضغط Jpeg.

**Returns:**
int - جودة الصورة المضغوطة.
### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


يضبط جودة الصورة المضغوطة. يُستخدم مع ضغط Jpeg.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | جودة الصورة المضغوطة. |


**Example: This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality.**

``` java

try (com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load("c:\\temp\\zeebra.tif"))
{
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    // قم بتعيين نموذج اللون RGB.
    tiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
    // ضبط ضغط Jpeg.
    tiffOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Jpeg);
    tiffOptions.setCompressedQuality(50);
    // عيّن 8 بتات لكل مكوّن لوني.
    tiffOptions.setBitsPerSample(new int[]{8, 8, 8});

    image.save("zeebra.tif-50.tiff", tiffOptions);
}

```

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


يحصل على حقوق النشر.

**Returns:**
java.lang.String - حقوق النشر.
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


يضبط حقوق النشر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | حقوق النشر. |

### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


يحصل أو يضبط خريطة الألوان.

**Returns:**
int[] - خريطة الألوان.
### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


يحصل أو يضبط خريطة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | خريطة الألوان. |

### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


يحصل أو يضبط لوحة الألوان.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


يحصل أو يضبط لوحة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | لوحة الألوان. |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


يحصل أو يضبط التاريخ والوقت.

**Returns:**
java.lang.String - التاريخ والوقت.
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


يحصل أو يضبط التاريخ والوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | التاريخ والوقت. |

### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


يحصل أو يضبط اسم المستند.

**Returns:**
java.lang.String - اسم المستند.
### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


يحصل أو يضبط اسم المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | اسم المستند. |

### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


يحصل أو يضبط خيار تخزين ألفا. تُستخدم الخيارات غير `TiffAlphaStorage.Unspecified` عندما يكون هناك أكثر من 3 `SamplesPerPixel` معرفة.

**Returns:**
int - خيار تخزين ألفا.
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


يحصل أو يضبط خيار تخزين ألفا. تُستخدم الخيارات غير `TiffAlphaStorage.Unspecified` عندما يكون هناك أكثر من 3 `SamplesPerPixel` معرفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | خيار تخزين ألفا. |

### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


يحصل على قيمة تشير إلى ما إذا كانت العينات الإضافية موجودة.

**Returns:**
boolean - `true` إذا كان العينة الإضافية موجودة؛ وإلا `false`.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


يحصل أو يضبط ترتيب تعبئة بتات البايت.

**Returns:**
int - ترتيب تعبئة بتات البايت.
### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


يحصل أو يضبط ترتيب تعبئة بتات البايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | ترتيب تعبئة بتات البايت. |

### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


يحصل أو يضبط تلميحات نصف اللون.

**Returns:**
int[] - تلميحات نصف النغمة.
### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


يحصل أو يضبط تلميحات نصف اللون.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | تلميحات نصف النغمة. |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


يحصل أو يضبط وصف الصورة.

**Returns:**
java.lang.String - وصف الصورة.
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


يحصل أو يضبط وصف الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | وصف الصورة. |

### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


يحصل أو يضبط أسماء الحبر.

**Returns:**
java.lang.String - أسماء الحبر.
### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


يحصل أو يضبط أسماء الحبر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | أسماء الحبر. |

### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


يحصل أو يضبط شركة تصنيع الماسح.

**Returns:**
java.lang.String - شركة تصنيع الماسح.
### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


يحصل أو يضبط شركة تصنيع الماسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | شركة تصنيع الماسح. |

### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


يحصل أو يضبط قيمة العينة القصوى.

**Returns:**
int[] - قيمة العينة القصوى.
### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


يحصل أو يضبط قيمة العينة القصوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | قيمة العينة القصوى. |

### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


يحصل أو يضبط قيمة العينة الدنيا.

**Returns:**
int[] - قيمة العينة الدنيا.
### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


يحصل أو يضبط قيمة العينة الدنيا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | قيمة العينة الدنيا. |

### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


يحصل أو يضبط طراز الماسح.

**Returns:**
java.lang.String - نموذج الماسح الضوئي.
### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


يحصل أو يضبط طراز الماسح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | نموذج الماسح الضوئي. |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


يحصل أو يضبط الاتجاه.

**Returns:**
int - الاتجاه [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations).
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


يحصل أو يضبط الاتجاه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الاتجاه [TiffOrientations](../../com.aspose.imaging.fileformats.tiff.enums/tifforientations). |

### getPageName() {#getPageName--}
```
public String getPageName()
```


يحصل أو يضبط اسم الصفحة.

**Returns:**
java.lang.String - اسم الصفحة.
### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


يحصل أو يضبط اسم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | اسم الصفحة. |

### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


يحصل أو يضبط وسم رقم الصفحة.

**Returns:**
int[] - وسم رقم الصفحة.
### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


يحصل أو يضبط وسم رقم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | وسم رقم الصفحة. |

### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


يحصل أو يضبط الفوتومتري.

**Returns:**
int - الفوتومتري.
### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


يحصل أو يضبط الفوتومتري.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الفوتومتري. |


**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// إنشاء مصدر ملف دائم، وليس مؤقتًا.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // ملء الإطار النشط بفرشاة تدرج خطية.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // خيارات التدرج الرمادي
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // إنشاء نسخة بتدرج رمادي من الإطار النشط.
    // يتم الحفاظ على بيانات البكسل ولكنها تُحوَّل إلى الصيغة المطلوبة.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // إضافة الإطار الذي تم إنشاؤه حديثًا إلى صورة TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


يحصل أو يضبط تكوين المستوى.

**Returns:**
int - تكوين المستوى.
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


يحصل أو يضبط تكوين المستوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | تكوين المستوى. |


**Example: This example shows how to create a TIFF image from scratch and save it to a file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// عيّن 8 بتات لكل مكوّن لوني.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// عيّن ترتيب البايت Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// قم بتعيين ضغط LZW.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// قم بتعيين نموذج اللون RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// إنشاء إطار TIFF بحجم 100×100 بكسل.
// لاحظ أنك لا تحتاج إلى تحرير إطار صراحةً إذا كان مُدرجًا في TiffImage.
// عند تحرير الحاوية سيتم تحرير جميع الإطارات تلقائيًا.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// املأ الإطار بالكامل بالتدرج الأزرق‑الأصفر.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// إنشاء صورة TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


يحصل أو يضبط وحدة الدقة.

**Returns:**
int - وحدة الدقة.
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


يحصل أو يضبط وحدة الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | وحدة الدقة. |

### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


يحصل أو يضبط الصفوف لكل شريط.

**Returns:**
long - الصفوف لكل شريط.
### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


يحصل أو يضبط الصفوف لكل شريط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | الصفوف لكل شريط. |

### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


يحصل ot يضبط عرض البلاطة.

**Returns:**
long
### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


يحصل ot يضبط عرض البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


يحصل ot يضبط طول البلاطة.

**Returns:**
long
### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


يحصل ot يضبط طول البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


يحصل أو يضبط تنسيق العينة.

**Returns:**
int[] - تنسيق العينة.
### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


يحصل أو يضبط تنسيق العينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int[] | تنسيق العينة. |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


يحصل على العينات لكل بكسل. لتغيير قيمة هذه الخاصية استخدم مُعيّن الخاصية `BitsPerSample`.

**Returns:**
int - العينات لكل بكسل.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


يحصل أو يضبط قيمة العينة القصوى. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long).

**Returns:**
long[] - قيمة العينة القصوى.
### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


يحصل أو يضبط قيمة العينة القصوى. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] | قيمة العينة القصوى. |

### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


يحصل أو يضبط قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long).

**Returns:**
long[] - قيمة العينة الدنيا.
### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


يحصل أو يضبط قيمة العينة الدنيا. القيمة لها نوع حقل يتطابق بأفضل شكل مع بيانات العينة (Byte أو Short أو Long).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] | قيمة العينة الدنيا. |

### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


يحصل أو يضبط نوع البرنامج.

**Returns:**
java.lang.String - نوع البرنامج.
### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


يحصل أو يضبط نوع البرنامج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | نوع البرنامج. |

### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


يحصل أو يضبط عدد بايتات الشريط.

**Returns:**
long[] - عدد بايتات الشريط.
### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


يحصل أو يضبط عدد بايتات الشريط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] | عدد بايتات الشريط. |

### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


يحصل أو يضبط إزاحات الشريط.

**Returns:**
long[] - إزاحات الشريط.
### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


يحصل أو يضبط إزاحات الشريط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] | إزاحات الشريط. |

### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


يحصل أو يضبط عدد بايتات البلاطة.

**Returns:**
long[]
### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


يحصل أو يضبط عدد بايتات البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] |  |

### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


يحصل أو يضبط إزاحات البلاطة.

**Returns:**
long[]
### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


يحصل أو يضبط إزاحات البلاطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long[] |  |

### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي.

**Returns:**
long - الإشارة العامة لنوع البيانات الموجودة في هذا الملف الفرعي.
### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


يحصل أو يضبط إشارة عامة لنوع البيانات الموجودة في هذا الملف الفرعي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | الإشارة العامة لنوع البيانات الموجودة في هذا الملف الفرعي. |

### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


يحصل أو يضبط الطابعة المستهدفة.

**Returns:**
java.lang.String - الطابعة المستهدفة.
### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


يحصل أو يضبط الطابعة المستهدفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الطابعة المستهدفة. |

### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


يحصل أو يضبط العتبة.

**Returns:**
int - العتبة.
### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


يحصل أو يضبط العتبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | العتبة. |

### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


يحصل على إجمالي الصفحات.

**Returns:**
int - إجمالي الصفحات.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


يحصل أو يضبط موضع x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x position.
### setXposition(TiffRational value) {#setXposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


يحصل أو يضبط موضع x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | موضع x. |

### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


يحصل أو يضبط إعدادات الدقة.

**Returns:**
[ResolutionSetting](../../com.aspose.imaging/resolutionsetting)
### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.imaging.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


يحصل أو يضبط إعدادات الدقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.imaging/resolutionsetting) |  |

### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


يحصل أو يضبط دقة x.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The x resolution.
### setXresolution(TiffRational value) {#setXresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


يحصل أو يضبط دقة x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | دقة x. |

### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


يحصل أو يضبط موضع y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y position.
### setYposition(TiffRational value) {#setYposition-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


يحصل أو يضبط موضع y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | موضع y. |

### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


يحصل أو يضبط دقة y.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The y resolution.
### setYresolution(TiffRational value) {#setYresolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


يحصل أو يضبط دقة y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | دقة y. |

### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


يحصل أو يضبط خيارات الفاكس t4.

**Returns:**
long - خيارات الفاكس t4.
### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


يحصل أو يضبط خيارات الفاكس t4.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | خيارات الفاكس t4. |

### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


يحصل أو يضبط المتنبئ لضغط LZW.

**Returns:**
int - نوع المتنبئ.
### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


يحصل أو يضبط المتنبئ لضغط LZW.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | نوع المتنبئ. |


**Example: This example shows how to save a raster image to the TIFF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions saveOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// عيّن 8 بتات لكل مكوّن لوني.
saveOptions.setBitsPerSample(new int[]{8, 8, 8});

// عيّن ترتيب البايت Big Endian (Motorola)
saveOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// قم بتعيين ضغط LZW.
saveOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// السماح بتقليل حجم الصور ذات النغمة المستمرة.
// حاليًا يتم استخدام هذا الحقل فقط مع ترميز LZW لأن LZW ربما يكون نظام الترميز الوحيد لملفات TIFF.
// الذي يستفيد بشكل كبير من خطوة التنبؤ.
saveOptions.setPredictor(com.aspose.imaging.fileformats.tiff.enums.TiffPredictor.Horizontal);

// قم بتعيين نموذج اللون RGB.
saveOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// بالنسبة إلى YCbCr، يمكنك استخدام أحد الخيارات التالية:
// حقل YCbCrSubSampling   عوامل أخذ عينات JPEG
// ----------------------------------------------
// 1,1                      1x1, 1x1, 1x1
// 2,1                      2x1, 1x1, 1x1
// 2,2(default value)       2x2, 1x1, 1x1
// saveOptions.YCbCrSubsampling = new ushort[] { 2, 2 };

// سيتم تخزين جميع مكونات اللون داخل مستوى واحد.
saveOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// إنشاء إطار TIFF بحجم 100×100 بكسل.
com.aspose.imaging.Image image = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // املأ الصورة بالكامل بالتدرج الأزرق-الأصفر.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(image.getWidth(), image.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);
    graphics.fillRectangle(gradientBrush, image.getBounds());

    image.save(dir + "output.tif", saveOptions);
} finally {
    image.dispose();
}
```

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


يحصل أو يضبط طول الصورة.

**Returns:**
long - طول الصورة.
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


يحصل أو يضبط طول الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | طول الصورة. |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


يحصل أو يضبط عرض الصورة.

**Returns:**
long - عرض الصورة.
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


يحصل أو يضبط عرض الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | long | عرض الصورة. |

### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


يحصل أو يعيّن المؤشر إلى EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.imaging.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


يحصل أو يضبط العلامات.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[] - العلامات.
### setTags(TiffDataType[] value) {#setTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


يحصل أو يضبط العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | العلامات. |

### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


يحصل على عدد العلامات الصالحة. هذا ليس إجمالي عدد العلامات بل عدد العلامات التي يمكن حفظها.

**Returns:**
int - عدد العلامات الصالحة.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


يحصل على عدد البتات لكل بكسل.

**Returns:**
int - عدد البتات لكل بكسل.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows.

القيمة: معلومات حول الصورة، تُستخدم بواسطة Windows Explorer. يتم تجاهل `XPTitle`(`\\#getXPTitle`/\\#setXPTitle(String).setXPTitle(String)) من قبل Windows Explorer إذا كان وسم `ImageDescription`(\\#getImageDescription.getImageDescription/\\#setImageDescription(String).setImageDescription(String)) موجودًا.

**Returns:**
java.lang.String - معلومات حول الصورة، تُستخدم بواسطة Windows Explorer.
### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


يضبط معلومات حول الصورة، التي يستخدمها مستكشف Windows.

القيمة: معلومات حول الصورة، تُستخدم بواسطة Windows Explorer. يتم تجاهل `XPTitle`(\\#getXPTitle.getXPTitle/`\\#setXPTitle(String)`) من قبل Windows Explorer إذا كان وسم `ImageDescription`(\\#getImageDescription.getImageDescription/\\#setImageDescription(String).setImageDescription(String)) موجودًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | معلومات حول الصورة، تُستخدم بواسطة Windows Explorer. |

### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


يحصل على التعليق على الصورة، التي يستخدمها مستكشف Windows.

القيمة: تعليق على الصورة، يُستخدم بواسطة Windows Explorer.

**Returns:**
java.lang.String - تعليق على الصورة، يُستخدم بواسطة Windows Explorer.
### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


يضبط التعليق على الصورة، التي يستخدمه مستكشف Windows.

القيمة: تعليق على الصورة، يُستخدم بواسطة Windows Explorer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | تعليق على الصورة، يُستخدم بواسطة Windows Explorer. |

### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


يحصل على مؤلف الصورة، الذي يستخدمه مستكشف Windows.

القيمة: مؤلف الصورة، يُستخدم بواسطة Windows Explorer. يتم تجاهل `XPAuthor`(`\\#getXPAuthor`/\\#setXPAuthor(String).setXPAuthor(String)) من قبل Windows Explorer إذا كان وسم `Artist`(\\#getArtist.getArtist/\\#setArtist(String).setArtist(String)) موجودًا.

**Returns:**
java.lang.String - مؤلف الصورة، يُستخدم بواسطة Windows Explorer.
### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


يضبط مؤلف الصورة، الذي يستخدمه مستكشف Windows.

القيمة: مؤلف الصورة، يُستخدم بواسطة Windows Explorer. يتم تجاهل `XPAuthor`(\\#getXPAuthor.getXPAuthor/`\\#setXPAuthor(String)`) من قبل Windows Explorer إذا كان وسم `Artist`(\\#getArtist.getArtist/\\#setArtist(String).setArtist(String)) موجودًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | مؤلف الصورة، يُستخدم بواسطة Windows Explorer. |

### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


يحصل على موضوع الصورة، الذي يستخدمه مستكشف Windows.

القيمة: موضوع الصورة، يُستخدم بواسطة Windows Explorer.

**Returns:**
java.lang.String - موضوع الصورة، يُستخدم بواسطة Windows Explorer.
### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


يضبط موضوع الصورة، الذي يستخدمه مستكشف Windows.

القيمة: موضوع الصورة، يُستخدم بواسطة Windows Explorer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | موضوع الصورة، يُستخدم بواسطة Windows Explorer. |

### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


يحصل على معلومات حول الصورة، التي يستخدمها مستكشف Windows.

القيمة: معلومات حول الصورة، تُستخدم بواسطة Windows Explorer.

**Returns:**
java.lang.String - معلومات حول الصورة، تُستخدم بواسطة Windows Explorer.
### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


يضبط معلومات حول الصورة، التي يستخدمها مستكشف Windows.

القيمة: معلومات حول الصورة، تُستخدم بواسطة Windows Explorer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | معلومات حول الصورة، تُستخدم بواسطة Windows Explorer. |

### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


يحصل على بيانات Exif.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


يضبط بيانات Exif.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | بيانات Exif. |

### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


يزيل العلامة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| علامة | int | الوسم المراد إزالته. |

**Returns:**
boolean - صحيح إذا تم الإزالة بنجاح
### removeTags(int[] tags) {#removeTags-int...-}
```
public final boolean removeTags(int[] tags)
```


يزيل العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الوسوم | int[] | الوسوم المراد إزالتها. |

**Returns:**
boolean - `` إذا تغير حجم مجموعة الوسوم.
### validate() {#validate--}
```
public void validate()
```


يتحقق مما إذا كانت الخيارات تحتوي على تركيبة صالحة من العلامات

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


يضيف العلامات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | الوسوم المراد إضافتها. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


يضيف علامة جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | الوسم المراد إضافته. |

### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


يحصل على مثيل العلامة حسب النوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tagKey | int | مفتاح العلامة. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
