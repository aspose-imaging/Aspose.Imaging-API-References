---
title: TiffOptions Class
type: docs
weight: 310
url: /python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/
---

The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Namespace:** [aspose.imaging.imageoptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/)

**Full Class Name:** aspose.imaging.imageoptions.TiffOptions

**Assembly:**  Aspose.Imaging Version: 23.3.0

The TiffOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|TiffOptions(expected_format, byte_order)|Initializes a new instance of the TiffOptions class|
|TiffOptions(expected_format)|Initializes a new instance of the TiffOptions class|
|TiffOptions(options)|Initializes a new instance of the TiffOptions class|
|TiffOptions(tags)|Initializes a new instance of the TiffOptions class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|xmp_data|Gets or sets the XMP metadata container.|
|source|Gets or sets the source to create image in.|
|palette|Gets or sets the color palette.|
|resolution_settings|Gets or sets the resolution settings.|
|vector_rasterization_options|Gets or sets the vector rasterization options.|
|buffer_size_hint|Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.|
|multi_page_options|The multipage options|
|full_frame|Gets or sets a value indicating whether [full frame].|
|file_standard|Gets or sets the TIFF file standard.|
|default_memory_allocation_limit|Gets or sets the default memory allocation limit.|
|premultiply_components|Gets or sets a value indicating whether components must be premultiplied.|
|is_valid|Gets a value indicating whether the [TiffOptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/) have been properly configured. Use Validate method as to find the failure reason.|
|y_cb_cr_subsampling|Gets or sets the subsampling factors for YCbCr photometric.|
|y_cb_cr_coefficients|Gets or sets the YCbCrCoefficients.|
|is_tiled|Gets a value indicating whether image is tiled.|
|artist|Gets or sets the artist.|
|byte_order|Gets or sets a value indicating the tiff byte order.|
|disable_icc_export|Gets or sets a value indicating whether ICC profile export is disabled (ICC profile is applied to the source pixels beforehand).|
|bits_per_sample|Gets or sets the bits per sample.|
|extra_samples|Gets the extra samples values.|
|compression|Gets or sets the compression.|
|compressed_quality|Gets or sets compressed image quality.<br/>            Used with the Jpeg compression.|
|copyright|Gets or sets the copyright.|
|color_map|Gets or sets the color map.|
|date_time|Gets or sets the date and time.|
|document_name|Gets or sets the name of the document.|
|alpha_storage|Gets or sets the alpha storage option. Options other than [UNSPECIFIED](/imaging/python-net/api-reference/aspose.imaging.fileformats.tiff.enums/tiffalphastorage/)<br/>            are used when there are more than 3 [samples_per_pixel](/imaging/python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/) defined.|
|is_extra_samples_present|Gets a value indicating whether the extra samples is present.|
|fill_order|Gets or sets the byte bits fill order.|
|half_tone_hints|Gets or sets the halftone hints.|
|image_description|Gets or sets the image description.|
|ink_names|Gets or sets the ink names.|
|scanner_manufacturer|Gets or sets the scanner manufacturer.|
|max_sample_value|Gets or sets the max sample value.|
|min_sample_value|Gets or sets the min sample value.|
|scanner_model|Gets or sets the scanner model.|
|orientation|Gets or sets the orientation.|
|page_name|Gets or sets the page name.|
|page_number|Gets or sets the page number tag.|
|photometric|Gets or sets the photometric.|
|planar_configuration|Gets or sets the planar configuration.|
|resolution_unit|Gets or sets the resolution unit.|
|rows_per_strip|Gets or sets the rows per strip.|
|tile_width|Gets ot sets tile width.|
|tile_length|Gets ot sets tile length.|
|sample_format|Gets or sets the sample format.|
|samples_per_pixel|Gets the samples per pixel. To change this property value use the [bits_per_sample](/imaging/python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/) property setter.|
|smax_sample_value|Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).|
|smin_sample_value|Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type).|
|software_type|Gets or sets the software type.|
|strip_byte_counts|Gets or sets the strip byte counts.|
|strip_offsets|Gets or sets the strip offsets.|
|tile_byte_counts|Gets or sets the tile byte counts.|
|tile_offsets|Gets or sets the tile offsets.|
|sub_file_type|Gets or sets a general indication of the kind of data contained in this subfile.|
|target_printer|Gets or sets the target printer.|
|threshholding|Gets or sets the threshholding.|
|total_pages|Gets the total pages.|
|xposition|Gets or sets the x position.|
|xresolution|Gets or sets the x resolution.|
|yposition|Gets or sets the y position.|
|yresolution|Gets or sets the y resolution.|
|fax_t4_options|Gets or sets the fax t4 options.|
|predictor|Gets or sets the predictor for LZW compression.|
|image_length|Gets or sets the image length.|
|image_width|Gets or sets the image width.|
|exif_ifd|Gets or sets the pointer to EXIF IFD.|
|tags|Gets or sets the tags.|
|valid_tag_count|Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved.|
|bits_per_pixel|Gets the bits per pixel.|
|xp_title|Gets or sets information about image, which used by Windows Explorer.|
|xp_comment|Gets or sets comment on image, which used by Windows Explorer.|
|xp_author|Gets or sets image author, which used by Windows Explorer.|
|xp_keywords|Gets or sets subject image, which used by Windows Explorer.|
|xp_subject|Gets or sets information about image, which used by Windows Explorer.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|clone()|Clones this instance.|
|create_with_format(expected_format)|Initializes a new instance of the [TiffOptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/) class. By default little endian convention is used.|
|create_with_options(options)|Initializes a new instance of the [TiffOptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/) class.|
|create_with_tags(tags)|Initializes a new instance of the [TiffOptions](/imaging/python-net/api-reference/aspose.imaging.imageoptions/tiffoptions/) class.|
|is_tag_present(tag)|Determines whether tag is present in the options or not.|
|get_valid_tags_count(tags)|Gets the valid tags count.|
|remove_tag(tag)|Removes the tag.|
|validate()|Validates if options have valid combination of tags|
|add_tags(tags_to_add)|Adds the tags.|
|add_tag(tag_to_add)|Adds the tags.|
|get_tag_by_type(tag_key)|Gets the instance of the tag by type.|
