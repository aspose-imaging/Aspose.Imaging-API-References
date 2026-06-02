---
title: "فئة PsdOptions"
type: docs
weight: 260
url: /ar/python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | يُنشئ نسخة جديدة من فئة [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) |
| [PsdOptions(options)](#PsdOptions_options_2) | يُنشئ نسخة جديدة من فئة [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| channel_bits_count | int | r/w | يحصل أو يضبط عدد البتات لكل قناة لون. |
| channels_count | int | r/w | يحصل أو يضبط عدد قنوات اللون. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | يحصل أو يضبط وضع لون PSD. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | يحصل أو يضبط طريقة ضغط PSD. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | يحصل أو يضبط إصدار تنسيق الملف. يمكن أن يكون PSD أو PSB. |
| refresh_image_preview_data | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان [refresh image preview data] - خيار يُستخدم لتعزيز التوافق مع عارضات صور PSD أخرى.<br/>            يرجى ملاحظة أن رسم طبقات النص إلى التخطيط النهائي غير مدعوم لمنصة Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان - إزالة مورد محرك النص العالمي - يُستخدم لبعض ملفات PSD ذات الطبقات النصية، في الحالة الوحيدة التي لا يمكن فتحها في Adobe Photoshop بعد المعالجة (غالبًا بسبب طبقات النص التي تفتقد الخطوط).<br/>            بعد استخدام هذا الخيار، يحتاج المستخدم إلى تنفيذ التالي في الملف المفتوح في Photoshop: القائمة \"Text\" -&gt; \"Process absent fonts\". بعد هذه العملية سيظهر كل النص مرة أخرى.<br/>            يرجى ملاحظة أن هذه العملية قد تتسبب في بعض تغييرات التخطيط النهائي. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل PSD إلى متجهات. |
| الإصدار | int | r/w | يحصل أو يضبط إصدار ملف PSD. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | احصل أو اضبط حاوية بيانات XMP |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

يُنشئ نسخة جديدة من فئة [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/)

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

يُنشئ نسخة جديدة من فئة [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | الخيارات. |

### Property: color_mode {#color_mode1}

يحصل أو يضبط وضع لون PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


### Property: compression_method {#compression_method2}

يحصل أو يضبط طريقة ضغط PSD.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of `aspose.imaging` API to convert Images t...


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
### This example demonstrates the use of `aspose.imaging` API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#ينشئ نسخة من فئة الصورة ويُهيئها بملف موجود عبر مسار الملف
with Image.load(path_join(directory, "sample.bmp")) as image:
	#إنشاء نسخة من فئة PsdOptions
	psdOptions = PsdOptions()
	#عيّن CompressionMethod كـ RLE
	#ملاحظة: طريقة الضغط المدعومة الأخرى هي CompressionMethod.RAW [بدون ضغط]
	psdOptions.compression_method = CompressionMethod.RLE
	#اضبط ColorMode إلى GRAYSCALE
	#ملاحظة: الأنماط المدعومة الأخرى لـ ColorModes هي ColorModes.BITMAP و ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#احفظ الصورة في موقع القرص باستخدام إعدادات PsdOptions المقدمة
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

