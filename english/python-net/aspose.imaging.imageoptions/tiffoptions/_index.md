---
title: TiffOptions Class
type: docs
weight: 330
url: /python-net/aspose.imaging.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.TiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, ImageOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. By default little endian convention is used. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. |
| [TiffOptions(options)](#TiffOptions_options_3) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/) | r/w | Gets or sets the alpha storage option. Options other than [TiffAlphaStorage.UNSPECIFIED](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            are used when there are more than 3 [TiffOptions.samples_per_pixel](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) defined. |
| artist | string | r/w | Gets or sets the artist. |
| bits_per_pixel | int | r | Gets the bits per pixel. |
| bits_per_sample | int[] | r/w | Gets or sets the bits per sample. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Gets or sets a value indicating the tiff byte order. |
| color_map | int[] | r/w | Gets or sets the color map. |
| [compressed_quality](#compressed_quality1) | int | r/w | Gets or sets compressed image quality.<br/>            Used with the Jpeg compression. |
| compression | [TiffCompressions](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffcompressions/) | r/w | Gets or sets the compression. |
| copyright | string | r/w | Gets or sets the copyright. |
| date_time | string | r/w | Gets or sets the date and time. |
| default_memory_allocation_limit | int | r/w | Gets or sets the default memory allocation limit. |
| disable_icc_export | bool | r/w | Gets or sets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand). |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| document_name | string | r/w | Gets or sets the name of the document. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets Exif data. |
| exif_ifd | [TiffExifIfd](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffexififd/) | r | Gets or sets the pointer to EXIF IFD. |
| extra_samples | int[] | r | Gets the extra samples values. |
| fax_t4_options | [Group3Options](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/group3options/) | r/w | Gets or sets the fax t4 options. |
| file_standard | [TiffFileStandards](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffilestandards/) | r/w | Gets or sets the TIFF file standard. |
| fill_order | [TiffFillOrders](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifffillorders/) | r/w | Gets or sets the byte bits fill order. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| half_tone_hints | int[] | r/w | Gets or sets the halftone hints. |
| image_description | string | r/w | Gets or sets the image description. |
| image_length | int | r/w | Gets or sets the image length. |
| image_width | int | r/w | Gets or sets the image width. |
| ink_names | string | r/w | Gets or sets the ink names. |
| is_extra_samples_present | bool | r | Gets a value indicating whether the extra samples is present. |
| is_tiled | bool | r | Gets a value indicating whether image is tiled. |
| is_valid | bool | r | Gets a value indicating whether the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) have been properly configured. Use Validate method as to find the failure reason. |
| keep_metadata | bool | r/w | Gets a value whether to keep original image metadata on export. |
| max_sample_value | int[] | r/w | Gets or sets the max sample value. |
| min_sample_value | int[] | r/w | Gets or sets the min sample value. |
| multi_page_options | [MultiPageOptions](/imaging/python-net/aspose.imaging.imageoptions/multipageoptions/) | r/w | The multipage options |
| orientation | [TiffOrientations](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifforientations/) | r/w | Gets or sets the orientation. |
| page_name | string | r/w | Gets or sets the page name. |
| page_number | int[] | r/w | Gets or sets the page number tag. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. |
| photometric | [TiffPhotometrics](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffphotometrics/) | r/w | Gets or sets the photometric. |
| planar_configuration | [TiffPlanarConfigs](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Gets or sets the planar configuration. |
| predictor | [TiffPredictor](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffpredictor/) | r/w | Gets or sets the predictor for LZW compression. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether components must be premultiplied. |
| resolution_settings | [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | r/w | Gets or sets the resolution settings. |
| resolution_unit | [TiffResolutionUnits](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Gets or sets the resolution unit. |
| rows_per_strip | int | r/w | Gets or sets the rows per strip. |
| sample_format | [TiffSampleFormats[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffsampleformats/) | r/w | Gets or sets the sample format. |
| samples_per_pixel | int | r | Gets the samples per pixel. To change this property value use the [TiffOptions.bits_per_sample](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) property setter. |
| scanner_manufacturer | string | r/w | Gets or sets the scanner manufacturer. |
| scanner_model | string | r/w | Gets or sets the scanner model. |
| smax_sample_value | int[] | r/w | Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| smin_sample_value | int[] | r/w | Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| software_type | string | r/w | Gets or sets the software type. |
| source | [Source](/imaging/python-net/aspose.imaging/source/) | r/w | Gets or sets the source to create image in. |
| strip_byte_counts | int[] | r/w | Gets or sets the strip byte counts. |
| strip_offsets | int[] | r/w | Gets or sets the strip offsets. |
| sub_file_type | [TiffNewSubFileTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Gets or sets a general indication of the kind of data contained in this subfile. |
| tag_count | int | r | Gets the tag count. |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | r/w | Gets or sets the tags. |
| target_printer | string | r/w | Gets or sets the target printer. |
| threshholding | [TiffThresholds](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffthresholds/) | r/w | Gets or sets the threshholding. |
| tile_byte_counts | int[] | r/w | Gets or sets the tile byte counts. |
| tile_length | int | r/w | Gets ot sets tile length. |
| tile_offsets | int[] | r/w | Gets or sets the tile offsets. |
| tile_width | int | r/w | Gets ot sets tile width. |
| total_pages | int | r | Gets the total pages. |
| valid_tag_count | int | r | Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved. |
| vector_rasterization_options | [VectorRasterizationOptions](/imaging/python-net/aspose.imaging.imageoptions/vectorrasterizationoptions/) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
| xp_author | string | r/w | Gets or sets image author, which used by Windows Explorer. |
| xp_comment | string | r/w | Gets or sets comment on image, which used by Windows Explorer. |
| xp_keywords | string | r/w | Gets or sets subject image, which used by Windows Explorer. |
| xp_subject | string | r/w | Gets or sets information about image, which used by Windows Explorer. |
| xp_title | string | r/w | Gets or sets information about image, which used by Windows Explorer. |
| xposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Gets or sets the x position. |
| xresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Gets or sets the x resolution. |
| y_cb_cr_coefficients | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Gets or sets the YCbCrCoefficients. |
| y_cb_cr_subsampling | int[] | r/w | Gets or sets the subsampling factors for YCbCr photometric. |
| yposition | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Gets or sets the y position. |
| yresolution | [TiffRational](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Gets or sets the y resolution. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Adds a new tag. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Adds the tags. |
| [clone()](#clone__3) | Clones this instance. |
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. By default little endian convention is used. |
| [create_with_options(options)](#create_with_options_options_5) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Gets the instance of the tag by type. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Gets the valid tags count. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Determines whether tag is present in the options or not. |
| [remove_tag(tag)](#remove_tag_tag_10) | Removes the tag. |
| [remove_tags(tags)](#remove_tags_tags_11) | Removes the tags. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |
| validate() | Validates if options have valid combination of tags |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. By default little endian convention is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | The expected tiff file format. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | The expected tiff file format. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | The tiff file format byte order to use. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | The options to copy from. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tags to initialize options with. |

### Property: compressed_quality {#compressed_quality1}

Gets or sets compressed image quality.<br/>            Used with the Jpeg compression.

**See also:**

**[Example # 1](#example_117)**: This example shows how to create a TIFF image with the Jpeg compression and t...


### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Adds a new tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tag to add. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Adds the tags.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tags to add. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Returns a deep clone. |


### Method: create_with_format(expected_format)  [static] {#create_with_format_expected_format_4}


```
 create_with_format(expected_format) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class. By default little endian convention is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | The expected tiff file format. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | The options to copy from. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Initializes a new instance of the [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tags to initialize options with. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) |  |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_7}


```
 get_tag_by_type(tag_key) 
```

Gets the instance of the tag by type.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_key | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tag key. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Instance of the tag if exists or null otherwise. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_8}


```
 get_valid_tags_count(tags) 
```

Gets the valid tags count.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tags to validate. |

**Returns**

| Type | Description |
| :- | :- |
| int | The valid tags count. |


### Method: is_tag_present(tag) {#is_tag_present_tag_9}


```
 is_tag_present(tag) 
```

Determines whether tag is present in the options or not.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tag id to check. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if tag is present; otherwise, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_10}


```
 remove_tag(tag) 
```

Removes the tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tag to remove. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if successfully removed |


### Method: remove_tags(tags) {#remove_tags_tags_11}


```
 remove_tags(tags) 
```

Removes the tags.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffTags[]](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | The tags to remove. |

**Returns**

| Type | Description |
| :- | :- |
| bool | **True** if tag collection size changed. |


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_12}


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
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Create an instance of a file stream
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Create an instance of TiffOptions and set its various properties
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Set the source for the instance of ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Create an instance of Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		# Clear Graphics surface
		graphics.clear(Color.wheat);
		# Create an instance of GraphicsPath class
		graphics_path = GraphicsPath()
		# Create an instance of Figure class
		figure = Figure()
		# Add Shapes to Figure object
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Add Figure object to GraphicsPath
		graphics_path.add_figure(figure)
		# Draw path with Pen object of color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# save all changes.
		image.save()


```

### This example demonstrates the use of different classes from `imageoptions` package for export purposes. A gif image is loaded as an instance of Image and then exported out to several formats. {#example_15}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions, JpegOptions, PngOptions, TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from os.path import join as path_join

directory = "c:\\temp\\"
#Load an existing gif image as an instance of Image class
with Image.load(path_join(directory, "sample.gif")) as image:
	# Export to BMP file format using the default options
	image.save(path_join(directory, "output.bmp"), BmpOptions())
	# Export to JPEG file format using the default options
	image.save(path_join(directory, "output.jpg"), JpegOptions())
	# Export to PNG file format using the default options
	image.save(path_join(directory, "output.png"), PngOptions())
	# Export to TIFF file format using the default options
	image.save(path_join(directory, "output.tif"), TiffOptions(TiffExpectedFormat.DEFAULT))


```

### This example shows how to create a TIFF image with the Jpeg compression and the specified compressed image quality. {#example_117}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import TiffOptions   
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat, TiffPhotometrics, TiffCompressions

with aspycore.as_of(Image.load("zeebra.tif"), TiffImage) as image:
	tiff_options = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Set the RGB color model.
	tiff_options.photometric = TiffPhotometrics.RGB
	# Set the Jpeg compression.
	tiff_options.compression = TiffCompressions.JPEG
	tiff_options.compressed_quality = 50
	# Set 8 bits for each color component.
	tiff_options.bits_per_sample = [8, 8, 8]
	image.save("zeebra.tif-50.tiff", tiff_options)


```

