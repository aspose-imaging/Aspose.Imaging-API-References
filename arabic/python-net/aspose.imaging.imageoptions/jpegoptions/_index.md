---
title: "فئة JpegOptions"
type: docs
weight: 160
url: /ar/python-net/aspose.imaging.imageoptions/jpegoptions/
---

**Summary:** Create high-quality JPEG images effortlessly with our API, offering adjustable<br/>            levels of compression to optimize storage size without compromising image quality.<br/>            Benefit from support for various compression types, near lossless coding,<br/>            RGB and CMYK color profiles, as well as EXIF, JFIF image data, and XMP<br/>            containers, ensuring versatile and customizable options for your image creation needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.JpegOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IHasJpegExifData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | يقوم بإنشاء نسخة جديدة من الفئة [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | يقوم بإنشاء نسخة جديدة من الفئة [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bits_per_channel | System.Byte | r/w | يحصل أو يعيّن عدد البتات لكل قناة لصورة jpeg غير مضغوطة. الآن ندعم من 2 إلى 8 بتات لكل قناة. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | ملف تعريف اللون CMYK الوجهة لصور jpeg بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بـ RGBColorProfile للتحويل اللوني الصحيح. |
| color_type | [JpegCompressionColorMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressioncolormode/) | r/w | يحصل أو يعيّن نوع اللون لصورة jpeg. |
| تعليق | string | r/w | يحصل أو يعيّن تعليق ملف jpeg. |
| compression_type | [JpegCompressionMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegcompressionmode/) | r/w | يحصل أو يعيّن نوع الضغط. |
| default_memory_allocation_limit | int | r/w | يحصل أو يعيّن حد تخصيص الذاكرة الافتراضي. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | احصل أو عيّن حاوية بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| horizontal_sampling | System.Byte | r/w | يحصل أو يعيّن العينات الفرعية الأفقية لكل مكوّن. |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata/) | r/w | يحصل أو يعيّن jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | يحصل أو يعيّن حد الفرق لـ JPEG-LS للترميز القريب من غير الفاقد (معامل NEAR من مواصفة JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/) | r/w | يحصل أو يعيّن وضع التداخل لـ JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | يحصل أو يعيّن معلمات الإعداد المسبق لـ JPEG-LS. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| preblend_alpha_if_present | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب خلط مكونات الأحمر والأخضر والأزرق مع لون الخلفية، إذا كان قناة ألفا موجودة. |
| quality | int | r/w | يحصل أو يعيّن جودة الصورة. |
| rd_opt_settings | [RdOptimizerSettings](/imaging/python-net/aspose.imaging.imageoptions/rdoptimizersettings/) | r/w | يحصل أو يعيّن إعدادات مُحسّن RD. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| resolution_unit | [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | r/w | يحصل أو يضبط وحدة الدقة. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | ملف تعريف اللون RGB الوجهة لصور jpeg بنظام CMYK. يُستخدم لحفظ الصور. يجب أن يكون مقترنًا بـ CMYKColorProfile للتحويل اللوني الصحيح. |
| sample_rounding_mode | [SampleRoundingMode](/imaging/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/) | r/w | يحصل أو يعيّن وضع تقريب العينة لتلائم قيمة 8-بت مع قيمة n-بت. _JpegOptions.BitsPerChannel_ |
| scaled_quality | int | r | الجودة المقيّسة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| vertical_sampling | System.Byte | r/w | يحصل أو يضبط العينات العمودية الفرعية لكل مكوّن. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

يقوم بإنشاء نسخة جديدة من الفئة [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

يقوم بإنشاء نسخة جديدة من الفئة [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | خيارات JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينشئ نسخة متماثلة لهذا الكائن.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | نسخة متماثلة لهذا الكائن. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) .

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | البيانات الوصفية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | صحيح، إذا كان كائن [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) يدعم و/أو ينفّذ كائن [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); وإلا، خطأ. |


## **Examples**
### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#تحميل صورة gif موجودة كمثيل لفئة Image
with Image.load(path_join(directory, "sample.gif")) as image:
	# تصدير إلى تنسيق ملف BMP باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# تصدير إلى تنسيق ملف JPEG باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# تصدير إلى تنسيق ملف PNG باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.png"), PngOptions())
	# تصدير إلى تنسيق ملف TIFF باستخدام الخيارات الافتراضية
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

