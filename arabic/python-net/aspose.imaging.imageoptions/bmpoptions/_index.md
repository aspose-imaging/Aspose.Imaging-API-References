---
title: "فئة BmpOptions"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.imageoptions/bmpoptions/
---

**Summary:** The API for BMP and DIB raster image format creation options provides developers<br/>            with a versatile toolset for generating custom Bitmap (BMP) and Device<br/>            Independent Bitmap (DIB) images. With this API, you can precisely define<br/>            image characteristics such as bits per pixel, compression level and compression<br/>            type, tailoring the output to meet specific requirements. This feature-rich<br/>            API empowers developers to create high-quality, customized raster images<br/>            with ease and flexibility for diverse applications.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BmpOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | ينشئ مثيلاً جديدًا للفئة [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | ينشئ مثيلاً جديدًا للفئة [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| [bits_per_pixel](#bits_per_pixel1) | int | r/w | يحصل أو يضبط عدد البتات لكل بكسل في الصورة. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [compression](#compression2) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r/w | يحصل أو يضبط نوع الضغط. النوع الافتراضي للضغط هو [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)، الذي يسمح بحفظ [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) مع الشفافية. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
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


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

ينشئ مثيلاً جديدًا للفئة [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/)


**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

ينشئ مثيلاً جديدًا للفئة [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| bmp_options | [BmpOptions](/imaging/python-net/aspose.imaging.imageoptions/bmpoptions/) | خيارات BMP. |

### Property: bits_per_pixel {#bits_per_pixel1}

يحصل أو يضبط عدد البتات لكل بكسل في الصورة.

**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 3](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...


### Property: compression {#compression2}

يحصل أو يضبط نوع الضغط. النوع الافتراضي للضغط هو [BitmapCompression.BITFIELDS](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/)، الذي يسمح بحفظ [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) مع الشفافية.

**See also:**

**[Example # 1](#example_91)**: The following example loads a BMP image and saves it back to BMP using variou...

**[Example # 2](#example_92)**: The following example creates a palettized grayscale BMP image and then saves...

**[Example # 3](#example_208)**: Decompress BMP image which was previously compressed using DXT1 compression a...

**[Example # 4](#example_225)**: The example shows how to export a BMP from a PNG file while keeping the alpha...

**[Example # 5](#example_226)**: The example shows how to export a BMP with the RGB compression type.


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
### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#إنشاء مثيل من `BmpOptions` وتعيين خصائصه المتنوعة
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#إنشاء مثيل من `FileCreateSource` وتعيينه كـ `source` لمثيل `BmpOptions`
	#المعامل `Boolean` الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#إنشاء مثيل من Image وتهيئته بمثيل BmpOptions عن طريق استدعاء طريقة Create
	with Image.create(bmp_options, 500, 500) as image:
		#قم ببعض معالجة الصورة
		# احفظ جميع التغييرات
		image.save()


```

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

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# إنشاء صورة BMP بحجم 100 × 100 بكسل.
with BmpImage(100, 100) as bmpImage:
	# التدرج الخطي من الزاوية اليسرى العليا إلى الزاوية اليمنى السفلى للصورة.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# املأ الصورة بالكامل بفرشاة التدرج الخطي.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# احصل على أقرب لوحة ألوان 8‑بت تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة الملونة باللوحة
	# تقريبًا لا يمكن تمييزها بصريًا عن صورة BMP بدون لوحة ألوان
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# لوحة ألوان 8‑بت تحتوي على حد أقصى 256 لونًا.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# المخرجات تبدو هكذا:
# حجم الصورة مع اللوحة هو 11078 بايت.
# حجم الصورة بدون لوحة هو 40054 بايت.

```

### The following example loads a BMP image and saves it back to BMP using various save options. {#example_91}
``` python
from aspose.imaging import Image, RasterImage, ColorPaletteHelper, ResolutionSetting
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
import os
import aspose.pycore as aspycore

directory = "c:\\temp\\"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	
	rasterImage = aspycore.as_of(image, RasterImage)

	# إنشاء BmpOptions
	saveOptions = BmpOptions()

	# استخدم 8 بتات لكل بكسل لتقليل حجم الصورة الناتجة.
	saveOptions.bits_per_pixel = 8

	# عيّن أقرب لوحة ألوان 8‑بت تغطي الحد الأقصى لعدد بكسلات الصورة، بحيث تكون الصورة الملونة باللوحة
	# يكاد يكون غير قابل للتمييز بصريًا عن نسخة غير مُلوَّنة.
	saveOptions.palette = ColorPaletteHelper.get_close_image_palette(rasterImage, 256)

	# احفظ دون ضغط.
	# يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
	saveOptions.compression = BitmapCompression.RGB

	# عيّن الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
	saveOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

	image.save(os.path.join(directory, "sample.bmpoptions.bmp"), saveOptions)


```

### The following example creates a palettized grayscale BMP image and then saves it to a file. {#example_92}
``` python

from os.path import join as path_join
from aspose.imaging import Image, ColorPaletteHelper, ResolutionSetting, Graphics, Point, Color
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.brushes import LinearGradientBrush

directory = "c:\\temp\\"
createOptions = BmpOptions()

# احفظ إلى ملف
createOptions.source = FileCreateSource(path_join(directory, "output.palette8bit.bmp"), False)
	
# استخدم 8 بتات لكل بكسل لتقليل حجم الصورة الناتجة.
createOptions.bits_per_pixel = 8

# عيّن لوحة ألوان التدرج الرمادي القياسية 8‑بت التي تغطي جميع ألوان التدرج الرمادي.
# إذا كانت الصورة المعالجة تحتوي فقط على ألوان التدرج الرمادي، فإن نسختها الملوَّنة
# غير قابلة للتمييز بصريًا عن نسخة غير ملوَّنة.
createOptions.palette = ColorPaletteHelper.create_8_bit_grayscale(False)

# احفظ دون ضغط.
# يمكنك أيضًا استخدام ضغط RLE-8 لتقليل حجم الصورة الناتجة.
createOptions.compression = BitmapCompression.RGB

# عيّن الدقة الأفقية والعمودية إلى 96 نقطة في البوصة.
createOptions.resolution_settings = ResolutionSetting(96.0, 96.0)

# أنشئ صورة BMP بحجم 100 × 100 بكسل واحفظها إلى ملف.
with Image.create(createOptions, 100, 100) as image:
	graphics = Graphics(image)
	gradientBrush = LinearGradientBrush(Point(0, 0), Point(image.width, image.height), Color.black, Color.white)
	# املأ الصورة بتدرج رمادي
	graphics.fill_rectangle(gradientBrush, image.bounds)
	image.save()


```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

### The example shows how to export a BMP from a PNG file while keeping the alpha channel, save a BMP file with transparency. {#example_225}
``` python
from aspose.imaging import Image
from aspose.imaging.fileformats.png import BmpOptions

source_path = "input.png"
output_path_def = "result_def.bmp"
output_path_def_2 = "result_def-2.bmp"
output_path_bitfields = "result_bitfields.bmp"
# تحميل صورة PNG من ملف.
with Image.load(source_path) as pngImage:
	# يتم حفظ صورة BMP مع دعم الشفافية افتراضيًا.
	# إذا كنت تريد تحديد هذا الوضع صراحةً، يجب ضبط خاصية `compression` في BmpOptions إلى BitmapCompression.BITFIELDS.
	# طريقة الضغط BitmapCompression.BITFIELDS هي طريقة الضغط الافتراضية في BmpOptions.
	# لذلك يمكن تحقيق نفس نتيجة تصدير صورة Bmp مع الشفافية بإحدى الطرق التالية.
	# مع خيارات افتراضية ضمنية:
	pngImage.save(output_path_def)
	# مع خيارات افتراضية صريحة:
	pngImage.save(output_path_def_2, BmpOptions())
	# تحديد طريقة الضغط BitmapCompression.BITFIELDS:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.BITFIELDS
	pngImage.save(output_path_bitfields, bmp_options)


```

### The example shows how to export a BMP with the RGB compression type. {#example_226}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BitmapCompression
from aspose.imaging.imageoptions import BmpOptions

source_path = "input.png"
output_path = "output.png"
# تحميل صورة PNG من ملف.
with Image.load(source_path) as pngImage:
	# يتم حفظ صورة BMP مع دعم الشفافية افتراضيًا، ويتم ذلك باستخدام طريقة الضغط BitmapCompression.BITFIELDS.
	# لحفظ صورة BMP باستخدام طريقة الضغط RGB، يجب تحديد BmpOptions مع خاصية `compression` مضبوطة على BitmapCompression.RGB.
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.RGB
	pngImage.save(output_path, bmp_options)


```

