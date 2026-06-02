---
title: "فئة SvgOptions"
type: docs
weight: 300
url: /ar/python-net/aspose.imaging.imageoptions/svgoptions/
---

**Summary:** Create Scalar Vector Graphics (SVG) image files with our API, utilizing versatile<br/>            options for color types and compression levels. Seamlessly customize your<br/>            SVG images with precision, ensuring optimal quality and compatibility for your design needs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.SvgOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [SvgOptions()](#SvgOptions__1) | ينشئ مثلاً جديداً من [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| callback | [ISvgResourceKeeperCallback](/imaging/python-net/aspose.imaging.fileformats.svg/isvgresourcekeepercallback/) | r/w | يسترجع أو يعيّن استراتيجية التخزين للموارد المضمنة في [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) مثل الخطوط والرسوم النقطية المتداخلة. |
| color_type | [SvgColorMode](/imaging/python-net/aspose.imaging.fileformats.svg/svgcolormode/) | r/w | يسترجع أو يعيّن نوع اللون لصورة SVG. |
| [compress](#compress1) | bool | r/w | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان يجب ضغط صورة الإخراج. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| [text_as_shapes](#text_as_shapes2) | bool | r/w | يسترجع أو يعيّن قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط حاوية بيانات التعريف XMP. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: SvgOptions() {#SvgOptions__1}


```
 SvgOptions() 
```

ينشئ مثلاً جديداً من [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/).

### Property: compress {#compress1}

يسترجع أو يعيّن قيمة تشير إلى ما إذا كان يجب ضغط صورة الإخراج.

**See also:**

**[Example # 1](#example_196)**: The following example shows how to convert a svg images to svgz format


### Property: text_as_shapes {#text_as_shapes2}

يسترجع أو يعيّن قيمة تشير إلى ما إذا كان يجب عرض النص كأشكال.

**See also:**

**[Example # 1](#example_173)**: This example shows how to load a WMF image from a file and convert it to SVG ...


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
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# استخدام Aspose.Imaging.Image.Load هو طريقة موحدة لتحميل جميع أنواع الصور بما في ذلك WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# سيتم تحويل النص إلى أشكال.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# لون الخلفية لسطح الرسم.
	rasterizationOptions.background_color = Color.white_smoke
	# حجم الصفحة.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# إذا كان هناك emf مضمّن، فقم بعرض emf؛ وإلا عرض wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

### The following example shows how to convert a svgz images to svg fromat {#example_193}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions
from os.path import join

file: str = "example.svgz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".svg"
with Image.load(input_file) as image:
	obj_init = SvgRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a svg images to svgz format {#example_196}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions

file = "juanmontoya_lingerie.svg"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".svgz"
with Image.load(input_file) as image:
	vector_rasterization_options = SvgRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

