---
title: DicomImage Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.dicom/dicomimage/
---

It is class of the implementation working with image from DICOM file

**Namespace:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Class Name:** aspose.imaging.fileformats.dicom.DicomImage

**Assembly:**  Aspose.Imaging Version: 23.5.0

The DicomImage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|DicomImage(dicom_options, width, height)|Initializes a new instance of the DicomImage class|
|DicomImage(stream, load_options)|Initializes a new instance of the DicomImage class|
|DicomImage(stream)|Initializes a new instance of the DicomImage class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|data_stream_container|  |
|is_cached|Gets a value indicating whether image data is cached currently.|
|bits_per_pixel|Gets the image bits per pixel count.|
|bounds|Gets the object bounds.|
|container|  |
|height|Gets the image height.|
|palette|  |
|use_palette|  |
|size|Gets the object size.|
|width|Gets the image width.|
|interrupt_monitor|  |
|buffer_size_hint|  |
|auto_adjust_palette|  |
|has_background_color|  |
|file_format|Gets a value of file format|
|background_color|Gets or sets a value for the background color.|
|premultiply_components|  |
|use_raw_data|  |
|update_xmp_data|  |
|xmp_data|Gets or sets the Xmp data.|
|raw_indexed_color_converter|  |
|raw_custom_color_converter|  |
|raw_fallback_index|  |
|raw_data_settings|Gets the current raw data settings. Note when using these settings the data loads without conversion.|
|raw_data_format|  |
|raw_line_size|  |
|is_raw_data_available|Gets a value indicating whether raw data loading is supported.|
|horizontal_resolution|  |
|vertical_resolution|  |
|has_transparent_color|Gets a value indicating whether image has transparent color.|
|has_alpha|Gets the Has alpha channel.|
|transparent_color|  |
|image_opacity|Gets opacity of this image.|
|page_count|Gets the page count.|
|pages|Gets the pages.|
|file_info|Gets a value, which contains info header the DICOM file|
|dicom_pages|Gets the pages.|
|active_page|Gets or sets the active page.|
|active_page_index|Gets the index active page.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save(stream, options_base, bounds_rectangle)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save()|Saves the object's data to the specified file (indexer + filename) location in the specified file format according to save options..|
|save(file_path)|Saves the object's data to the specified file (indexer + filename) location in the specified file format according to save options..|
|save(file_path, options)|Saves the object's data to the specified file (indexer + filename) location in the specified file format according to save options..|
|save(file_path, options, bounds_rectangle)|  |
|save(stream, options_base)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(stream)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(file_path, over_write)|  |
|can_load(file_path)|  |
|can_load(file_path, load_options)|  |
|can_load(stream)|  |
|can_load(stream, load_options)|  |
|create(image_options, width, height)|Creates new instance of the [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) class.|
|create(images)|Creates new instance of the [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) class.|
|create(images, dispose_images)|Creates new instance of the [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) class.|
|get_file_format(file_path)|  |
|get_file_format(stream)|  |
|get_fitting_rectangle(rectangle, width, height)|  |
|get_fitting_rectangle(rectangle, pixels, width, height)|  |
|load(file_path, load_options)|Loads raw data.|
|load(file_path)|Loads raw data.|
|load(stream, load_options)|Loads raw data.|
|load(stream)|Loads raw data.|
|resize(new_width, new_height, resize_type)|Performs proportional resize on the image.<br/>            The proportional resize will resize each frame according to the ratio of|
|resize(new_width, new_height, settings)|Resizes the image.|
|resize(new_width, new_height)|Performs proportional resize on the image.<br/>            The proportional resize will resize each frame according to the ratio of|
|resize_width_proportionally(new_width, resize_type)|Resizes the width proportionally.|
|resize_width_proportionally(new_width)|Resizes the width proportionally.|
|resize_width_proportionally(new_width, settings)|Resizes the width proportionally.|
|resize_height_proportionally(new_height, resize_type)|Resizes the width proportionally.|
|resize_height_proportionally(new_height)|Resizes the width proportionally.|
|resize_height_proportionally(new_height, settings)|Resizes the width proportionally.|
|dither(dithering_method, bits_count, custom_palette)|Performs dithering on the current image.|
|dither(dithering_method, bits_count)|Performs dithering on the current image.|
|get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)|  |
|get_default_raw_data(rectangle, raw_data_settings)|  |
|load_raw_data(rectangle, raw_data_settings, raw_data_loader)|Loads raw data.|
|load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)|Loads raw data.|
|crop(rectangle)|Cropping the image.|
|crop(left_shift, right_shift, top_shift, bottom_shift)|Crop image with shifts.|
|binarize_bradley(brightness_difference, window_size)|Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding|
|binarize_bradley(brightness_difference)|Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding|
|adjust_gamma(gamma)|Gamma-correction of an image.|
|adjust_gamma(gamma_red, gamma_green, gamma_blue)|Gamma-correction of an image.|
|rotate(angle, resize_proportionally, background_color)|  |
|rotate(angle)|  |
|normalize_angle(resize_proportionally, background_color)|Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses GetSkewAngle and|
|normalize_angle()|Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses GetSkewAngle and|
|replace_color(old_color_argb, old_color_diff, new_color_argb)|Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.|
|replace_color(old_color, old_color_diff, new_color)|Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.|
|replace_non_transparent_colors(new_color_argb)|Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.|
|replace_non_transparent_colors(new_color)|Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.|
|add_page(page)|Adds page to the image.|
|add_page()|Adds page to the image.|
|cache_data()|Caches the data private.|
|save_to_stream(stream)|  |
|can_load_with_options(file_path, load_options)|  |
|can_load_stream(stream)|  |
|can_load_stream_with_options(stream, load_options)|  |
|get_file_format_of_stream(stream)|  |
|load_with_options(file_path, load_options)|  |
|load_stream_with_options(stream, load_options)|  |
|load_stream(stream)|  |
|can_save(options)|  |
|resize_by_type(new_width, new_height, resize_type)|Resizes the image.|
|resize_by_settings(new_width, new_height, settings)|Resizes the image.|
|get_default_options(args)|  |
|get_original_options()|  |
|resize_width_proportionally_settings(new_width, settings)|  |
|resize_height_proportionally_settings(new_height, settings)|  |
|rotate_flip(rotate_flip_type)|Rotates, flips, or rotates and flips the Active frame only.|
|save_with_options(file_path, options)|  |
|save_with_options_rect(file_path, options, bounds_rectangle)|  |
|save_to_stream_with_options(stream, options_base)|  |
|save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)|  |
|set_palette(palette, update_colors)|  |
|get_proportional_width(width, height, new_height)|  |
|get_proportional_height(width, height, new_width)|  |
|get_modify_date(use_default)|  |
|get_default_pixels(rectangle, partial_pixel_loader)|  |
|get_default_argb_32_pixels(rectangle)|  |
|get_argb_32_pixel(x, y)|  |
|get_pixel(x, y)|  |
|set_argb_32_pixel(x, y, argb_32_color)|  |
|set_pixel(x, y, color)|  |
|read_scan_line(scan_line_index)|  |
|read_argb_32_scan_line(scan_line_index)|  |
|write_scan_line(scan_line_index, pixels)|  |
|write_argb_32_scan_line(scan_line_index, argb_32_pixels)|  |
|load_partial_argb_32_pixels(rectangle, partial_pixel_loader)|Loads 32-bit ARGB pixels partially (by blocks).|
|load_partial_pixels(desired_rectangle, pixel_loader)|  |
|load_argb_32_pixels(rectangle)|  |
|load_argb_64_pixels(rectangle)|  |
|load_partial_argb_64_pixels(rectangle, partial_pixel_loader)|  |
|load_pixels(rectangle)|  |
|load_cmyk_pixels(rectangle)|  |
|load_cmyk_32_pixels(rectangle)|  |
|save_raw_data(data, data_offset, rectangle, raw_data_settings)|  |
|save_argb_32_pixels(rectangle, pixels)|  |
|save_pixels(rectangle, pixels)|Saves pixels (format specific method).|
|to_bitmap()|  |
|save_cmyk_pixels(rectangle, pixels)|  |
|save_cmyk_32_pixels(rectangle, pixels)|  |
|set_resolution(dpi_x, dpi_y)|Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).|
|binarize_fixed(threshold)|Binarization of an image with predefined threshold|
|binarize_otsu()|Binarization of an image with Otsu thresholding|
|grayscale()|Transformation of an image to its grayscale representation|
|adjust_brightness(brightness)|Adjust of a|
|adjust_contrast(contrast)|[Image](/imaging/python-net/aspose.imaging/image/) contrasting|
|get_skew_angle()|  |
|filter(rectangle, options)|Filters the specified rectangle.|
|replace_argb(old_color_argb, old_color_diff, new_color_argb)|  |
|rotate_flip_all(rotate_flip)|Rotates the flip all.|
|save_all(file_path, options)|Saves the object's data to the specified file (indexer + filename) location in the specified file format according to save options..|
|resize_proportional(new_width, new_height, resize_type)|Performs proportional resize on the image.<br/>            The proportional resize will resize each frame according to the ratio of|
|insert_page(page_index)|Inserts a new page into the page list at the specified index.|
|remove_page(page_index)|Removes the page at the specified index of the page list.|
