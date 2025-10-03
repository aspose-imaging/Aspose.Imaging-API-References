---
title: BigTiffOptions Class
type: docs
weight: 20
url: /python-net/aspose.imaging.imageoptions/bigtiffoptions/
---

**Summary:** The API for BigTIFF raster image format creation is specifically designed<br/>            to serve to the unique requirements of applications utilizing large-scale<br/>            imaging data from scanners. This API facilitates the seamless generation<br/>            of BigTIFF format, which combines multiple TIFF images into a single,<br/>            comprehensive image. It ensures efficient processing of extensive image<br/>            data, providing developers with a powerful tool for creating and<br/>            manipulating high-resolution, multi-image formats.

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.BigTiffOptions

**Inheritance:** IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, TiffOptions

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffOptions(expected_format)](#BigTiffOptions_expected_format_1) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. By default little endian convention is used. |
| [BigTiffOptions(expected_format, byte_order)](#BigTiffOptions_expected_format_byte_order_2) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. |
| [BigTiffOptions(options)](#BigTiffOptions_options_3) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. |
| [BigTiffOptions(tags)](#BigTiffOptions_tags_4) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. |
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
| compressed_quality | int | r/w | Gets or sets compressed image quality.<br/>            Used with the Jpeg compression. |
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
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets Xmp data. |
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
| [create_with_format(expected_format)](#create_with_format_expected_format_4) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. By default little endian convention is used. |
| [create_with_options(options)](#create_with_options_options_5) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. |
| [create_with_tags(tags)](#create_with_tags_tags_6) | Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_7) | Gets the instance of the tag by type. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_8) | Gets the valid tags count. |
| [is_tag_present(tag)](#is_tag_present_tag_9) | Determines whether tag is present in the options or not. |
| [remove_tag(tag)](#remove_tag_tag_10) | Removes the tag. |
| [remove_tags(tags)](#remove_tags_tags_11) | Removes the tags. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_12) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |
| validate() | Validates if options have valid combination of tags |


### Constructor: BigTiffOptions(expected_format) {#BigTiffOptions_expected_format_1}


```
 BigTiffOptions(expected_format) 
```

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. By default little endian convention is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | The expected Tiff file format. |

### Constructor: BigTiffOptions(expected_format, byte_order) {#BigTiffOptions_expected_format_byte_order_2}


```
 BigTiffOptions(expected_format, byte_order) 
```

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | The expected Tiff file format. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | The tiff file format byte order to use. |

### Constructor: BigTiffOptions(options) {#BigTiffOptions_options_3}


```
 BigTiffOptions(options) 
```

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | The options source. |

### Constructor: BigTiffOptions(tags) {#BigTiffOptions_tags_4}


```
 BigTiffOptions(tags) 
```

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tags for options initialization. |

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

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class. By default little endian convention is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffexpectedformat/) | The expected Tiff file format. |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | A new BigTiffOptions object. |


### Method: create_with_options(options)  [static] {#create_with_options_options_5}


```
 create_with_options(options) 
```

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/imaging/python-net/aspose.imaging.imageoptions/tiffoptions/) | The options source. |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | A copy of options. |


### Method: create_with_tags(tags)  [static] {#create_with_tags_tags_6}


```
 create_with_tags(tags) 
```

Initializes a new instance of the [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | The tags for options initialization. |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffOptions](/imaging/python-net/aspose.imaging.imageoptions/bigtiffoptions/) | A new BigTiffOptions object with tags. |


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
| bool | True if _metadata_ is not null and the [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) instance <br/>            supports and/or implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance; otherwise, false. |


