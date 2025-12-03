---
title: DicomOptions Class
type: docs
weight: 60
url: /python-net/aspose.imaging.imageoptions/dicomoptions/
---

**Summary:** The API for Digital Imaging and Communications in Medicine (DICOM) raster image<br/>            format creation is a specialized tool tailored for medical device applications.<br/>            It enables the seamless generation of DICOM images, crucial for storing medical<br/>            data and containing vital identification information. With features to<br/>            and set compression, define color types, and embed XMP metadata, developers<br/>            can ensure compliance and flexibility in managing DICOM images for medical<br/>            imaging purposes.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.DicomOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DicomOptions()](#DicomOptions__1) | Initializes a new instance of the [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [color_type](#color_type1) | [ColorType](/imaging/python-net/aspose.imaging.fileformats.dicom/colortype/) | r/w | Gets or sets the type of the color. |
| [compression](#compression2) | [Compression](/imaging/python-net/aspose.imaging.fileformats.dicom/compression/) | r/w | Gets or sets the compression. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: DicomOptions() {#DicomOptions__1}


```
 DicomOptions() 
```

Initializes a new instance of the [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) class.

### Property: color_type {#color_type1}

Gets or sets the type of the color.

**See also:**

**[Example # 1](#example_208)**: Use JPEG compression in DICOM image.

**[Example # 2](#example_209)**: Use JPEG 2000 compression in DICOM image.

**[Example # 3](#example_210)**: Use RLE compression in DICOM image.

**[Example # 4](#example_211)**: Change the color type in DICOM compression.


### Property: compression {#compression2}

Gets or sets the compression.

**See also:**

**[Example # 1](#example_208)**: Use JPEG compression in DICOM image.

**[Example # 2](#example_209)**: Use JPEG 2000 compression in DICOM image.

**[Example # 3](#example_210)**: Use RLE compression in DICOM image.

**[Example # 4](#example_211)**: Change the color type in DICOM compression.


### Method: clone() {#clone__1}


```
 clone() 
```

Creates a memberwise clone of this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | A memberwise clone of this instance. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_2}


```
 try_set_metadata(metadata) 
```

Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | The metadata. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True, if the [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) instance supports and/or implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance; otherwise, false. |


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

# The next code sample converts JPEG image to DICOM file format
with Image.load(inputFileNameSingle) as image:
	image.save(outputFileNameSingleDcm, DicomOptions())

# DICOM format supports multipage images. You can convert GIF or TIFF images to DICOM in the same way as JPEG images
with Image.load(inputFileNameMultipage) as image_multiple:
	image_multiple.save(outputFileNameMultipageDcm, DicomOptions())


```

### Use JPEG compression in DICOM image. {#example_208}
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

### Use JPEG 2000 compression in DICOM image. {#example_209}
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

### Use RLE compression in DICOM image. {#example_210}
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

### Change the color type in DICOM compression. {#example_211}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import ColorType

with Image.load("original.jpg") as inputImage:
	options = DicomOptions()
	options.color_type = ColorType.GRAYSCALE_8_BIT
	inputImage.save("original_8Bit.dcm", options)


```

