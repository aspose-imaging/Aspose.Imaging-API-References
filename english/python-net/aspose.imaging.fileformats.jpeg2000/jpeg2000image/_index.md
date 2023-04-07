---
title: Jpeg2000Image Class
type: docs
weight: 10
url: /python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---

Jpeg2000 library main class

**Namespace:** [aspose.imaging.fileformats.jpeg2000](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/)

**Full Class Name:** aspose.imaging.fileformats.jpeg2000.Jpeg2000Image

**Assembly:**  Aspose.Imaging Version: 23.3.0

The Jpeg2000Image type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|Jpeg2000Image(path)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(path, bits_per_pixel)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(stream)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(stream, bits_per_pixel)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(width, height)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(width, height, options)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(width, height, bits_count)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(image)|Initializes a new instance of the Jpeg2000Image class|
|Jpeg2000Image(raster_image, bits_per_pixel)|Initializes a new instance of the Jpeg2000Image class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|data_stream_container|  |
|is_cached|Gets a value indicating whether image data is cached currently.|
|bits_per_pixel|Gets image depth (bits per pixel)|
|bounds|Gets the object bounds.|
|container|  |
|height|Gets the image height|
|palette|  |
|use_palette|  |
|size|Gets the object size.|
|width|Gets the image width|
|interrupt_monitor|  |
|buffer_size_hint|  |
|auto_adjust_palette|  |
|has_background_color|  |
|file_format|Gets a value of file format|
|background_color|  |
|premultiply_components|  |
|use_raw_data|  |
|update_xmp_data|  |
|xmp_data|Gets or sets the XMP metadata.|
|raw_indexed_color_converter|  |
|raw_custom_color_converter|  |
|raw_fallback_index|  |
|raw_data_settings|Gets the current raw data settings. Note when using these settings the data loads without conversion.|
|raw_data_format|Gets the raw data format.|
|raw_line_size|Gets the raw line size in bytes.|
|is_raw_data_available|Gets a value indicating whether raw data loading is supported.|
|horizontal_resolution|Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/api-reference/aspose.imaging/rasterimage/).|
|vertical_resolution|Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/api-reference/aspose.imaging/rasterimage/).|
|has_transparent_color|  |
|has_alpha|  |
|transparent_color|  |
|image_opacity|  |
|comments|Gets or sets the comments.|
|codec|Gets the codec.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save(stream, options_base, bounds_rectangle)|  |
|save()|Saves the image into Jpeg2000 file format (j2k)|
|save(file_path)|  |
|save(file_path, options)|  |
|save(file_path, options, bounds_rectangle)|  |
|save(stream, options_base)|  |
|save(stream)|Saves the image into Jpeg2000 file format (j2k)|
|save(file_path, over_write)|  |
|can_load(file_path)|  |
|can_load(file_path, load_options)|  |
|can_load(stream)|  |
|can_load(stream, load_options)|  |
|create(image_options, width, height)|Creates the new data loader for saving.|
|create(images)|Creates the new data loader for saving.|
|create(images, dispose_images)|Creates the new data loader for saving.|
|get_file_format(file_path)|  |
|get_file_format(stream)|  |
|get_fitting_rectangle(rectangle, width, height)|  |
|get_fitting_rectangle(rectangle, pixels, width, height)|  |
|load(file_path, load_options)|Loads raw data.|
|load(file_path)|Loads raw data.|
|load(stream, load_options)|Loads raw data.|
|load(stream)|Loads raw data.|
|resize(new_width, new_height, resize_type)|Resizes the image.|
|resize(new_width, new_height, settings)|Resizes the image.|
|resize(new_width, new_height)|Resizes the image.|
|resize_width_proportionally(new_width)|  |
|resize_width_proportionally(new_width, resize_type)|  |
|resize_width_proportionally(new_width, settings)|  |
|resize_height_proportionally(new_height)|  |
|resize_height_proportionally(new_height, resize_type)|  |
|resize_height_proportionally(new_height, settings)|  |
|dither(dithering_method, bits_count, custom_palette)|Performs dithering on the current image.|
|dither(dithering_method, bits_count)|Performs dithering on the current image.|
|get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)|  |
|get_default_raw_data(rectangle, raw_data_settings)|  |
|load_raw_data(rectangle, raw_data_settings, raw_data_loader)|Loads raw data.|
|load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)|Loads raw data.|
|crop(rectangle)|Cropping the image.|
|crop(left_shift, right_shift, top_shift, bottom_shift)|Cropping the image.|
|binarize_bradley(brightness_difference, window_size)|Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding|
|binarize_bradley(brightness_difference)|Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding|
|adjust_gamma(gamma_red, gamma_green, gamma_blue)|Gamma-correction of an image.|
|adjust_gamma(gamma)|Gamma-correction of an image.|
|rotate(angle, resize_proportionally, background_color)|Rotate image around the center.|
|rotate(angle)|Rotate image around the center.|
|normalize_angle()|  |
|normalize_angle(resize_proportionally, background_color)|  |
|replace_color(old_color, old_color_diff, new_color)|  |
|replace_color(old_color_argb, old_color_diff, new_color_argb)|  |
|replace_non_transparent_colors(new_color)|  |
|replace_non_transparent_colors(new_color_argb)|  |
|cache_data()|Caches the data and ensures no additional data loading will be performed from the underlying [data_stream_container](/imaging/python-net/api-reference/aspose.imaging/datastreamsupporter/).|
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
|get_original_options()|Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the|
|resize_width_proportionally_settings(new_width, settings)|  |
|resize_height_proportionally_settings(new_height, settings)|  |
|rotate_flip(rotate_flip_type)|Rotates, flips, or rotates and flips the image.|
|save_with_options(file_path, options)|  |
|save_with_options_rect(file_path, options, bounds_rectangle)|  |
|save_to_stream_with_options(stream, options_base)|  |
|save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)|  |
|set_palette(palette, update_colors)|  |
|get_proportional_width(width, height, new_height)|  |
|get_proportional_height(width, height, new_width)|  |
|is_multipage()|  |
|as_multipage()|  |
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
|load_pixels(rectangle)|  |
|load_cmyk_pixels(rectangle)|  |
|load_cmyk_32_pixels(rectangle)|  |
|save_raw_data(data, data_offset, rectangle, raw_data_settings)|  |
|save_argb_32_pixels(rectangle, pixels)|  |
|save_pixels(rectangle, pixels)|  |
|to_bitmap()|  |
|save_cmyk_pixels(rectangle, pixels)|  |
|save_cmyk_32_pixels(rectangle, pixels)|  |
|set_resolution(dpi_x, dpi_y)|  |
|binarize_fixed(threshold)|Binarization of an image with predefined threshold|
|binarize_otsu()|Binarization of an image with Otsu thresholding|
|grayscale()|Transformation of an image to its grayscale representation|
|adjust_brightness(brightness)|Adjust of a brightness for image.|
|adjust_contrast(contrast)|Image contrasting|
|get_skew_angle()|  |
|filter(rectangle, options)|  |
|replace_argb(old_color_argb, old_color_diff, new_color_argb)|  |
|create_from_file_with_bpp(path, bits_per_pixel)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_from_stream(stream)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_from_stream_with_bpp(stream, bits_per_pixel)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_with_width_height(width, height)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_with_width_height_options(width, height, options)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_with_width_height_bitscount(width, height, bits_count)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_from_image(image)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
|create_from_image_with_bpp(raster_image, bits_per_pixel)|Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/api-reference/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.|
