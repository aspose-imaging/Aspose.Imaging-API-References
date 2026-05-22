---
title: "فئة Jpeg2000Options"
type: docs
weight: 150
url: /ar/python-net/aspose.imaging.imageoptions/jpeg2000options/
---

**Summary:** Create JPEG2000 (JP2) image files with our API, utilizing advanced wavelet technology<br/>            for coding lossless content. Benefit from support for various codecs, including<br/>            irreversible and lossless compression, as well as XMP metadata containers, ensuring<br/>            versatility and high-quality image creation tailored to your needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Jpeg2000Options

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [codec](#codec1) | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r/w | يحصل أو يعيّن مشفر JPEG2000 |
| التعليقات | string[] | r/w | يحصل أو يعيّن علامات تعليقات Jpeg. |
| compression_ratios | int[] | r/w | يحصل أو يعيّن مصفوفة نسب الضغط.<br/>            نسب ضغط مختلفة للطبقات المتتابعة.<br/>            المعدل المحدد لكل مستوى جودة هو العامل المطلوب<br/>            للضغط.<br/>            مطلوب نسب منخفضة. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| [irreversible](#irreversible2) | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخدام DWT غير العكسي 9-7 (true) أو استخدام ضغط DWT غير الفاقد 5-3 (default). |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

ينشئ مثلاً جديداً من الفئة [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | خيارات تنسيق ملف Jpeg2000 لنسخ الإعدادات منها. |

### Property: codec {#codec1}

يحصل أو يعيّن مشفر JPEG2000

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Property: irreversible {#irreversible2}

يحصل أو يعيّن قيمة تشير إلى ما إذا كان سيتم استخدام DWT غير العكسي 9-7 (true) أو استخدام ضغط DWT غير الفاقد 5-3 (default).

**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


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
### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# استخدام تحويل الموجة المتقطعة غير القابل للعكس 9-7
create_options.irreversible = True
# JP2 هو تنسيق \"الحاوية\" لتدفقات JPEG 2000.
# J2K هو بيانات مضغوطة خام، بدون غلاف.
create_options.codec = Jpeg2000Codec.J2K
# إنشاء صورة JPEG2000 بحجم 100×100 بكسل.
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# ملء الصورة بالكامل باللون الأحمر.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# احفظ إلى ملف
	jpeg2000_image.save(path_join(dir_, "sample.output.j2k"))


```

### This example shows how to create a PNG image and save it to JPEG2000 with the desired options. {#example_163}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec
from aspose.imaging.fileformats.png import PngImage
from os.path import join as path_join


dir_ = "c:\\temp"
# أنشئ صورة PNG بحجم 100 × 100 بكسل.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# ملء الصورة بالكامل باللون الأحمر.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# استخدام تحويل الموجة المتقطعة غير القابل للعكس 9-7
	save_options.irreversible = True
	# JP2 هو تنسيق \"الحاوية\" لتدفقات JPEG 2000.
	# J2K هو بيانات مضغوطة خام، بدون غلاف.
	save_options.codec = Jpeg2000Codec.J2K
	# احفظ إلى ملف
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

