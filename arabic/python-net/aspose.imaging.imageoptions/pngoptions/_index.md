---
title: "فئة PngOptions"
type: docs
weight: 250
url: /ar/python-net/aspose.imaging.imageoptions/pngoptions/
---

**Summary:** Create high-quality Portable Network Graphics (PNG) raster images effortlessly<br/>            with our API, offering customizable options for compression levels,<br/>            bits per pixel depths, and alpha bits. Seamlessly process XMP metadata containers,<br/>            ensuring comprehensive image metadata management, and empowering you to tailor<br/>            PNG images to your exact specifications with ease.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PngOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | يقوم بإنشاء نسخة جديدة من الفئة [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | يقوم بإنشاء نسخة جديدة من الفئة [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r | مستوى الضغط الافتراضي. |
| bit_depth | System.Byte | r/w | يحصل أو يعيّن قيم عمق البت في النطاق 1، 2، 4، 8، 16.<br/>            <br/><br/>            انتبه إلى الحدود التالية:<br/>            <br/><br/>[PngColorType.INDEXED_COLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) يدعم عمق البت 1، 2، 4، 8.<br/>            <br/><br/>[PngColorType.GRAYSCALE](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.GRAYSCALE_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) يدعمان عمق البت 8.<br/>            <br/><br/>[PngColorType.TRUECOLOR](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/), [PngColorType.TRUECOLOR_WITH_ALPHA](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) يدعمان عمق البت 8، 16.<br/>            <br/> |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [color_type](#color_type1) | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | r/w | يحصل أو يعيّن نوع اللون. |
| [compression_level](#compression_level2) | int | r/w | يحصل أو يعيّن مستوى ضغط [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| filter_type | [PngFilterType](/imaging/python-net/aspose.imaging.fileformats.png/pngfiltertype/) | r/w | يحصل أو يعيّن نوع الفلتر المستخدم أثناء عملية حفظ ملف png. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| png_compression_level | [PngCompressionLevel](/imaging/python-net/aspose.imaging.imageoptions/pngcompressionlevel/) | r/w | يحصل أو يعيّن مستوى ضغط [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [progressive](#progressive3) | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) تقدميًا. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

يقوم بإنشاء نسخة جديدة من الفئة [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

يقوم بإنشاء نسخة جديدة من الفئة [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | خيارات PNG. |

### Property: color_type {#color_type1}

يحصل أو يعيّن نوع اللون.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: compression_level {#compression_level2}

يحصل أو يعيّن مستوى ضغط [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


### Property: progressive {#progressive3}

يحصل أو يعيّن قيمة تشير إلى ما إذا كان [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) تقدميًا.

**See also:**

**[Example # 1](#example_21)**: The following example shows how to compress a PNG image, using indexed color ...


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
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#ينشئ مثيلاً من تدفق الملف.
with open(r"C:\temp\output.png", "w+b") as stream:
	#إنشاء مثيل من PngOptions وتعيين خصائصه المتنوعة.
	pngOptions = PngOptions()
	#تعيين المصدر لـ PngOptions.
	pngOptions.source = StreamSource(stream)
	#إنشاء مثيل من Image.
	with Image.create(pngOptions, 500, 500) as image:
		#إنشاء وتهيئة مثيل من فئة Graphics.
		graphics = Graphics(image)
		#مسح سطح Graphics.
		graphics.clear(Color.wheat);
		#ارسم قوسًا بتحديد كائن Pen الذي لديه لون أسود،
		#مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#ارسم منحنى Bezier بتحديد كائن Pen الذي لديه لون أزرق ونقاط الإحداثيات.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#ارسم منحنى عن طريق تحديد كائن Pen ذو اللون الأخضر ومصفوفة من Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#ارسم إهليلجًا باستخدام كائن Pen ومستطيل محيط
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#ارسم خطًا
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#ارسم قطعة فطيرة
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#ارسم مضلعًا بتحديد كائن Pen ذو اللون الأحمر ومصفوفة من Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#ارسم مستطيلًا
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
		brush = SolidBrush()
		brush.color = Color.purple
		#ارسم نصًا باستخدام كائن SolidBrush و Font، عند نقطة محددة
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# احفظ جميع التغييرات.
		image.save();

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

### The following example shows how to compress a PNG image, using indexed color with best fit palette {#example_21}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper, RasterImage, PaletteMiningMethod
from aspose.imaging.fileformats.png import PngColorType

# يحمّل صورة PNG        
sourceFilePath = "OriginalRings.png"
outputFilePath = "OriginalRingsOutput.png"
with Image.load(sourceFilePath) as image:
	png_options = PngOptions()
	png_options.progressive = True
	# استخدم نوع اللون المفهرس
	png_options.color_type = PngColorType.INDEXED_COLOR
	# استخدم أقصى ضغط
	png_options.compression_level = 9
	# احصل على أقرب لوحة ألوان 8‑بت، تغطي أكبر عدد ممكن من البكسلات، بحيث تكون الصورة
	# مع لوحة ألوان تقريبًا لا يمكن تمييزها بصريًا عن صورة بدون لوحة ألوان.
	png_options.palette = ColorPaletteHelper.get_close_image_palette(
						as_of(image, RasterImage), 256, 
						PaletteMiningMethod.HISTOGRAM)
		 
	image.save(outputFilePath, png_options);
}
# يجب تقليل حجم ملف الإخراج بشكل كبير

```

