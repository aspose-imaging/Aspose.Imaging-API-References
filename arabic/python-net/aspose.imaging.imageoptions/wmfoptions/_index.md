---
title: "فئة WmfOptions"
type: docs
weight: 370
url: /ar/python-net/aspose.imaging.imageoptions/wmfoptions/
---

**Summary:** The wmf options.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.WmfOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, MetafileOptions

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WmfOptions()](#WmfOptions__1) | يُنشئ نسخة جديدة من فئة WmfOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| compress | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا [ICompressedOptions](/imaging/python-net/aspose.fileformats.core.imageoptions/icompressedoptions/) مضغوطًا. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | يحصل أو يعيّن كائن Exif. |
| full_frame | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [full frame]. |
| keep_metadata | bool | r/w | يحصل على قيمة ما إذا كان يجب الاحتفاظ ببيانات التعريف الأصلية للصورة عند التصدير. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | خيارات الصفحات المتعددة |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | يحصل أو يضبط لوحة الألوان. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | يحصل أو يضبط إعدادات الدقة. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | يحصل أو يضبط المصدر لإنشاء الصورة فيه. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | يحصل أو يضبط خيارات تحويل المتجه إلى نقطية. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | يحصل أو يضبط بيانات Xmp. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينشئ نسخة متماثلة لهذا الكائن. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | يحاول ضبط مثال _metadata_، إذا كان مثال هذا [Image](/imaging/python-net/aspose.imaging/image/) يدعم ويطبق مثال [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) . |


### Constructor: WmfOptions() {#WmfOptions__1}


```
 WmfOptions() 
```

يُنشئ نسخة جديدة من فئة WmfOptions

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
### The following example shows how to convert a wmz images to wmf fromat {#example_192}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions
from os.path import join

file: str = "example.wmz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".wmf"
with Image.load(input_file) as image:
	obj_init = WmfRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a wmf images to wmz format {#example_195}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions

file = "castle.wmf"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".wmz"
with Image.load(input_file) as image:
	vector_rasterization_options = WmfRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

