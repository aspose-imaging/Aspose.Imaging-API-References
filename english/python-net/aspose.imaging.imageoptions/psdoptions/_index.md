---
title: PsdOptions Class
type: docs
weight: 260
url: /python-net/aspose.imaging.imageoptions/psdoptions/
---

**Summary:** Create Photoshop Document (PSD) images with our API, offering versatile options<br/>            with different format versions, compression methods, color modes, and<br/>            bits counts per color channel. Seamlessly handle XMP metadata containers,<br/>            ensuring comprehensive image processing with the power of PSD format features<br/>            like image layers, layer masks, and file information for customization<br/>            and creativity in your designs.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PsdOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class. |
| [PsdOptions(options)](#PsdOptions_options_2) | Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| channel_bits_count | int | r/w | Gets or sets the bits count per color channel. |
| channels_count | int | r/w | Gets or sets the color channels count. |
| [color_mode](#color_mode1) | [ColorModes](/imaging/python-net/aspose.imaging.fileformats.psd/colormodes/) | r/w | Gets or sets the psd color mode. |
| [compression_method](#compression_method2) | [CompressionMethod](/imaging/python-net/aspose.imaging.fileformats.psd/compressionmethod/) | r/w | Gets or sets the psd compression method. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| psd_version | [PsdVersion](/imaging/python-net/aspose.imaging.fileformats.psd/psdversion/) | r/w | Gets or sets the file format version. It can be PSD or PSB. |
| refresh_image_preview_data | bool | r/w | Gets or sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers.<br/>            Please note, text layers drawing to final layout is not supported for Compact Framework platform |
| remove_global_text_engine_resource | bool | r/w | Gets or sets a value indicating whether - Remove the global text engine resource - Used for some text-layered psd files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related).<br/>            After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -&gt; "Process absent fonts". After that operation all text will appear again.<br/>            Please note, that this operation may cause some final layout changes. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| vectorization_options | [PsdVectorizationOptions](/imaging/python-net/aspose.imaging.imageoptions/psdvectorizationoptions/) | r/w | Gets or sets the PSD vectorization options. |
| version | int | r/w | Gets or sets the psd file version. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Get or set XMP data container |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a memberwise clone of this instance. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_2) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class.

### Constructor: PsdOptions(options) {#PsdOptions_options_2}


```
 PsdOptions(options) 
```

Initializes a new instance of the [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [PsdOptions](/imaging/python-net/aspose.imaging.imageoptions/psdoptions/) | The options. |

### Property: color_mode {#color_mode1}

Gets or sets the psd color mode.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of Aspose.Imaging API to convert Images to ...


### Property: compression_method {#compression_method2}

Gets or sets the psd compression method.

**See also:**

**[Example # 1](#example_11)**: This example demonstrates the use of Aspose.Imaging API to convert Images to ...


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
### This example demonstrates the use of Aspose.Imaging API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format. {#example_11}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from os.path import join as path_join

directory = "c:\\temp\\"

#Creates an instance of image class and initialize it with an existing file through File path
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Create an instance of PsdOptions class
	psdOptions = PsdOptions()
	#Set the CompressionMethod as RLE
	#Note: Other supported CompressionMethod is CompressionMethod.RAW [No Compression]
	psdOptions.compression_method = CompressionMethod.RLE
	#Set the ColorMode to GRAYSCALE
	#Note: Other supported ColorModes are ColorModes.BITMAP and ColorModes.RGB
	psdOptions.color_mode = ColorModes.GRAYSCALE
	#Save the image to disk location with supplied PsdOptions settings
	image.save(path_join(directory, "output.psd"), psdOptions)
}

```

