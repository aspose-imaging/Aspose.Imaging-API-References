---
title: "فئة ApngOptions"
type: docs
weight: 10
url: /ar/python-net/aspose.imaging.imageoptions/apngoptions/
---

**Summary:** The API for Animated PNG (Animated Portable Network Graphics) image file format<br/>            creation is a dynamic tool for developers seeking to generate captivating<br/>            animated images. With customizable options such as frame duration and the<br/>            number of times to loop, this API allows for fine-tuning animated content<br/>            according to specific needs. Whether creating engaging web graphics or<br/>            interactive visuals, you can leverage this API to seamlessly incorporate<br/>            APNG images with precise control over animation parameters.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.ApngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, PngOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ApngOptions()](#ApngOptions__1) | ينشئ مثيلاً جديداً من الفئة [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | مستوى الضغط الافتراضي. |
| bit_depth | System.Byte | r/w | يحصل أو يعيّن قيم عمق البت في النطاق 1، 2، 4، 8، 16.<br/>            <br/><br/>            انتبه إلى الحدود التالية:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) يدعم عمق البت 1، 2، 4، 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) يدعمان عمق البت 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) يدعمان عمق البت 8، 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | يحصل أو يعيّن نوع اللون. |
| compression_level | int | r/w | يحصل أو يعيّن مستوى ضغط [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [default_frame_time](#default_frame_time1) | int | r/w | يحصل أو يعيّن مدة الإطار الافتراضية. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن كائن Exif. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | يحصل أو يعيّن نوع الفلتر المستخدم أثناء عملية حفظ ملف png. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| [num_plays](#num_plays2) | int | r/w | يحصل أو يعيّن عدد مرات تكرار الرسوم المتحركة.<br/>            0 يدل على تكرار لا نهائي. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | يحصل أو يعيّن مستوى ضغط [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| progressive | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) تقدميًا. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: ApngOptions() {#ApngOptions__1}


```
 ApngOptions() 
```

ينشئ مثيلاً جديداً من الفئة [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/).

### Property: default_frame_time {#default_frame_time1}

يحصل أو يعيّن مدة الإطار الافتراضية.

**See also:**

**[Example # 1](#example_198)**: The following example shows how to export apng APNG file format from other no...


### Property: num_plays {#num_plays2}

يحصل أو يعيّن عدد مرات تكرار الرسوم المتحركة.<br/>            0 يدل على تكرار لا نهائي.

**See also:**

**[Example # 1](#example_197)**: The following example shows how to export to APNG file format.


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
| bool | صحيح إذا كان _metadata_ غير فارغ وكانت نسخة [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            تدعم و/أو تنفذ نسخة [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); وإلا، خطأ. |


## **Examples**
### The following example shows how to export to APNG file format. {#example_197}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.imageoptions import *

with Image.load("Animation1.webp") as image:
	# تصدير إلى رسوم متحركة APNG مع دورات رسوم متحركة غير محدودة كإعداد افتراضي
	image.save("Animation1.webp.png", ApngOptions())
	# إعداد دورات الرسوم المتحركة
	obj_init = ApngOptions()
	# 5 دورات
	obj_init.num_plays = 5
	image.save("Animation2.webp.png", obj_init)


```

### The following example shows how to export apng APNG file format from other non-animated multi-page format. {#example_198}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import ApngOptions

with Image.load("img4.tif") as image:
	# إعداد مدة الإطار الافتراضية
	obj_init = ApngOptions()
	# 500 مللي ثانية
	obj_init.default_frame_time = 500
	image.save("img4.tif.500ms.png", obj_init)
	obj_init2 = ApngOptions()
	# 250 مللي ثانية
	obj_init2.default_frame_time = 250
	image.save("img4.tif.250ms.png", obj_init2)


```

