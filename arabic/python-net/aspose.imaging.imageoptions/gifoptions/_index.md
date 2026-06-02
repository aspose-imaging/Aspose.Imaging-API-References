---
title: "فئة GifOptions"
type: docs
weight: 120
url: /ar/python-net/aspose.imaging.imageoptions/gifoptions/
---

**Summary:** The API for Graphical Interchange Format (GIF) raster image file creation offers<br/>            developers comprehensive options for generating GIF images with precise<br/>            control. With features to set background color, color palette, resolution,<br/>            interlaced type, transparent color, XMP metadata container, and image<br/>            compression, this API ensures flexibility and efficiency in creating optimized<br/>            and visually appealing GIFs tailored to specific application requirements.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.GifOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | ينشئ مثيلاً جديداً من الفئة [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | ينشئ مثيلاً جديداً من الفئة [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | يحصل أو يعيّن لون الخلفية. |
| background_color_index | System.Byte | r/w | يحصل أو يعيّن فهرس لون خلفية GIF. |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| color_resolution | System.Byte | r/w | يحصل أو يعيّن دقة ألوان GIF. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| do_palette_correction | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان تصحيح لوحة الألوان مطبقاً. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| has_trailer | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان GIF يحتوي على مقطع نهائي. |
| has_transparent_color | System.Nullable`1[[System.Boolean]] | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت صورة GIF تحتوي على لون شفاف. <br/>            إذا كانت القيمة المرجعة هي **None**, يتم تجاوز هذه الخاصية بسياق الصورة المصدر. |
| interlaced | bool | r/w | True إذا كان يجب أن تكون الصورة متداخلة. |
| is_palette_sorted | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت مدخلات لوحة الألوان مرتبة. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| loops_count | int | r/w | يحصل أو يعيّن عدد الحلقات (الافتراضي حلقة واحدة). |
| max_diff | int | r/w | يحصل أو يعيّن الحد الأقصى المسموح به لاختلاف البكسل. إذا كان أكبر من الصفر، سيتم استخدام ضغط فقدان البيانات.<br/>            القيمة الموصى بها لضغط فقدان البيانات الأمثل هي 80. 30 يعني ضغط خفيف جداً، 200 يعني ضغط ثقيل.<br/>            يعمل بشكل أفضل عندما يُدخل فقدان بسيط فقط، وبسبب قيود خوارزمية الضغط لا تعطي مستويات فقدان عالية جداً الكثير من الفائدة.<br/>            نطاق القيم المسموح بها هو [0, 1000]. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| pixel_aspect_ratio | System.Byte | r/w | يحصل أو يعيّن نسبة أبعاد بكسل GIF. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

ينشئ مثيلاً جديداً من الفئة [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

ينشئ مثيلاً جديداً من الفئة [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| gif_options | [GifOptions](/imaging/python-net/aspose.imaging.imageoptions/gifoptions/) | خيارات GIF. |

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
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# إنشاء نسخة من MemoryStream
with strm_ext.create_memory_stream() as stream:
	#أنشئ مثيلًا من GifOptions واضبط خصائصه المتنوعة بما في ذلك خاصية Source.
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# إنشاء نسخة من Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# احصل على بكسلات الصورة بتحديد المنطقة كحدود الصورة.
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#تكرار عبر المصفوفة وتعيين لون البكسل المفهرس البديل.
			for index in range(pixel.length):
				if index % 2 == 0:
					#عيّن لون البكسل المفهرس إلى الأصفر.
					pixels[index] = yellow_color
				else:
					#عيّن لون البكسل المفهرس إلى الأزرق.
					pixels[index] = blue_color

			#طبق تغييرات البكسل على الصورة.
			image.save_pixels(image.bounds, pixels)

			# احفظ جميع التغييرات.
			image.save()

	# اكتب MemoryStream إلى ملف.
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

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

