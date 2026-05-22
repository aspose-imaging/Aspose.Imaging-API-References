---
title: "DicomOptions 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.imageoptions/dicomoptions/
---

**Summary:** The API for Digital Imaging and Communications in Medicine (DICOM) raster image<br/>            format creation is a specialized tool tailored for medical device applications.<br/>            It enables the seamless generation of DICOM images, crucial for storing medical<br/>            data and containing vital identification information. With features to<br/>            and set compression, define color types, and embed XMP metadata, developers<br/>            can ensure compliance and flexibility in managing DICOM images for medical<br/>            imaging purposes.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DicomOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DicomOptions()](#DicomOptions__1) | 初始化一个新的 [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [color_type](#color_type1) | [ColorType](/imaging/python-net/aspose.imaging.fileformats.dicom/colortype/) | r/w | 获取或设置颜色的类型。 |
| [compression](#compression2) | [Compression](/imaging/python-net/aspose.imaging.fileformats.dicom/compression/) | r/w | 获取或设置压缩。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| full_frame | bool | r/w | 获取或设置一个值，指示是否为 [full frame]。 |
| keep_metadata | bool | r/w | 获取一个值，指示在导出时是否保留原始图像元数据。 |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | 多页选项 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。 |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 创建此实例的成员逐个克隆。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |


### Constructor: DicomOptions() {#DicomOptions__1}


```
 DicomOptions() 
```

初始化一个新的 [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) 类实例。

### Property: color_type {#color_type1}

获取或设置颜色的类型。

**See also:**

**[Example # 1](#example_211)**: Use JPEG compression in DICOM image.

**[Example # 2](#example_212)**: Use JPEG 2000 compression in DICOM image.

**[Example # 3](#example_213)**: Use RLE compression in DICOM image.

**[Example # 4](#example_214)**: Change the color type in DICOM compression.


### Property: compression {#compression2}

获取或设置压缩。

**See also:**

**[Example # 1](#example_211)**: Use JPEG compression in DICOM image.

**[Example # 2](#example_212)**: Use JPEG 2000 compression in DICOM image.

**[Example # 3](#example_213)**: Use RLE compression in DICOM image.

**[Example # 4](#example_214)**: Change the color type in DICOM compression.


### Method: clone() {#clone__1}


```
 clone() 
```

创建此实例的成员逐个克隆。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 此实例的成员逐个克隆。 |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | 元数据。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


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

# 下面的代码示例将 JPEG 图像转换为 DICOM 文件格式
with Image.load(inputFileNameSingle) as image:
	image.save(outputFileNameSingleDcm, DicomOptions())

# DICOM 格式支持多页图像。您可以像转换 JPEG 图像一样将 GIF 或 TIFF 图像转换为 DICOM。
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

