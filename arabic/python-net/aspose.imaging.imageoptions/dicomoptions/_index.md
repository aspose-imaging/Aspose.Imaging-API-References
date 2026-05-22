---
title: "فئة DicomOptions"
type: docs
weight: 60
url: /ar/python-net/aspose.imaging.imageoptions/dicomoptions/
---

**Summary:** The API for Digital Imaging and Communications in Medicine (DICOM) raster image<br/>            format creation is a specialized tool tailored for medical device applications.<br/>            It enables the seamless generation of DICOM images, crucial for storing medical<br/>            data and containing vital identification information. With features to<br/>            and set compression, define color types, and embed XMP metadata, developers<br/>            can ensure compliance and flexibility in managing DICOM images for medical<br/>            imaging purposes.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DicomOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [DicomOptions()](#DicomOptions__1) | يقوم بإنشاء نسخة جديدة من الفئة [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرف كأقصى حجم مسموح به لجميع المخازن الداخلية. |
| [color_type](#color_type1) | [ColorType](/imaging/python-net/aspose.imaging.fileformats.dicom/colortype/) | r/w | يحصل أو يعيّن نوع اللون. |
| [compression](#compression2) | [Compression](/imaging/python-net/aspose.imaging.fileformats.dicom/compression/) | r/w | يحصل أو يضبط الضغط. |
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


### Constructor: DicomOptions() {#DicomOptions__1}


```
 DicomOptions() 
```

يقوم بإنشاء نسخة جديدة من الفئة [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/).

### Property: color_type {#color_type1}

يحصل أو يعيّن نوع اللون.

**See also:**

**[Example # 1](#example_211)**: Use JPEG compression in DICOM image.

**[Example # 2](#example_212)**: Use JPEG 2000 compression in DICOM image.

**[Example # 3](#example_213)**: Use RLE compression in DICOM image.

**[Example # 4](#example_214)**: Change the color type in DICOM compression.


### Property: compression {#compression2}

يحصل أو يضبط الضغط.

**See also:**

**[Example # 1](#example_211)**: Use JPEG compression in DICOM image.

**[Example # 2](#example_212)**: Use JPEG 2000 compression in DICOM image.

**[Example # 3](#example_213)**: Use RLE compression in DICOM image.

**[Example # 4](#example_214)**: Change the color type in DICOM compression.


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
### The following example shows export to DICOM file format (single and multipage). {#example_17}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions

fileName = "sample.jpg"
inputFileNameSingle = fileName
inputFileNameMultipage = "multipage.tif"
outputFileNameSingleDcm = "output.dcm"
outputFileNameMultipageDcm = "outputMultipage.dcm"

# عينة الشيفرة التالية تحول صورة JPEG إلى تنسيق ملف DICOM
with Image.load(inputFileNameSingle) as image:
	image.save(outputFileNameSingleDcm, DicomOptions())

# يدعم تنسيق DICOM الصور متعددة الصفحات. يمكنك تحويل صور GIF أو TIFF إلى DICOM بنفس طريقة صور JPEG.
with Image.load(inputFileNameMultipage) as image_multiple:
	image_multiple.save(outputFileNameMultipageDcm, DicomOptions())


```

### Use JPEG compression in DICOM image. {#example_211}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions, DicomOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode, SampleRoundingMode
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import Compression, ColorType, CompressionType

with Image.load("original.jpg") as input_image:
	obj_init = JpegOptions()
	obj_init.compression_type = JpegCompressionMode.BASELINE
	obj_init.sample_rounding_mode = SampleRoundingMode.TRUNCATE
	obj_init.quality = 50
	obj_init2 = Compression()
	obj_init2.type = CompressionType.JPEG
	obj_init2.jpeg = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG.dcm", options)


```

### Use JPEG 2000 compression in DICOM image. {#example_212}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import Jpeg2000Options, DicomOptions
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Compression, CompressionType, ColorType

with Image.load("original.jpg") as input_image:
	obj_init = Jpeg2000Options()
	obj_init.codec = Jpeg2000Codec.JP2
	obj_init.irreversible = False
	obj_init2 = Compression()
	obj_init2.type_ = CompressionType.JPEG2000
	obj_init2.jpeg2000 = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG2000.dcm", options)


```

### Use RLE compression in DICOM image. {#example_213}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import Compression, CompressionType, ColorType
from aspose.imaging.imageoptions import DicomOptions

with Image.load("original.jpg") as input_image:
	compr = Compression()
	compr.type_ = CompressionType.RLE
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = compr
	input_image.save("original_RLE.dcm", options)


```

### Change the color type in DICOM compression. {#example_214}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import ColorType

with Image.load("original.jpg") as inputImage:
	options = DicomOptions()
	options.color_type = ColorType.GRAYSCALE_8_BIT
	inputImage.save("original_8Bit.dcm", options)


```

