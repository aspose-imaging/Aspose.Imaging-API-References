---
title: "فئة Html5CanvasOptions"
type: docs
weight: 130
url: /ar/python-net/aspose.imaging.imageoptions/html5canvasoptions/
---

**Summary:** Create HTML5 Canvas files effortlessly with our API, allowing you to seamlessly<br/>            combine elements like forms, text, images, animations, and links. Benefit from<br/>            robust features including tag identifier and encoding settings support,<br/>            ensuring optimal performance and customization for your web projects.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.Html5CanvasOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Html5CanvasOptions()](#Html5CanvasOptions__1) | يُنشئ مثلاً جديداً من الفئة [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| canvas_tag_id | string | r/w | يحصل أو يعيّن معرف علامة القماش. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| encoding | string | r/w | يحصل أو يضبط الترميز. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن بيانات Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| full_html_page | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب إنشاء صفحة HTML كاملة. |
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


### Constructor: Html5CanvasOptions() {#Html5CanvasOptions__1}


```
 Html5CanvasOptions() 
```

يُنشئ مثلاً جديداً من الفئة [Html5CanvasOptions](/imaging/python-net/aspose.imaging.imageoptions/html5canvasoptions/).

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
### Any vector image (SVG, WMF, CMX, etc.) can be used as a source for your Canvas images. The following code creates a simple Canvas image. {#example_199}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	export_options = Html5CanvasOptions()
	export_options.vector_rasterization_options = SvgRasterizationOptions()
	image.save("Canvas.html", export_options)


```

### You can embed more than one Canvas image within HTML page or update already exsiting page. In order to do that you need to export only the Canvas tag. {#example_200}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import Html5CanvasOptions, SvgRasterizationOptions

with Image.load("Sample.svg") as image:
	options = Html5CanvasOptions()
	options.vector_rasterization_options = SvgRasterizationOptions()
	options.full_html_page = False
	image.save("Canvas.html", options)


```

