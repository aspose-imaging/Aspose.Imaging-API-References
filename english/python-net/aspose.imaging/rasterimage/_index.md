---
title: RasterImage Class
type: docs
weight: 720
url: /python-net/aspose.imaging/rasterimage/
---

Represents a raster image supporting raster graphics operations.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.RasterImage

**Assembly:**  Aspose.Imaging Version: 23.6.0

The RasterImage type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|data_stream_container|  |
|is_cached|  |
|bits_per_pixel|Gets the image bits per pixel count.|
|bounds|Gets the image bounds.|
|container|Gets the [Image](/imaging/python-net/aspose.imaging/image/) container.|
|height|Gets the image height.|
|palette|Gets or sets the color palette. The color palette is not used when pixels are represented directly.|
|use_palette|Gets a value indicating whether the image palette is used.|
|size|Gets the image size.|
|width|Gets the image width.|
|interrupt_monitor|Gets or sets the interrupt monitor.|
|buffer_size_hint|Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.|
|auto_adjust_palette|Gets or sets a value indicating whether automatic adjust palette.|
|has_background_color|Gets or sets a value indicating whether image has background color.|
|file_format|Gets a value of file format|
|background_color|Gets or sets a value for the background color.|
|premultiply_components|Gets or sets a value indicating whether the image components must be premultiplied.|
|use_raw_data|Gets or sets a value indicating whether to use raw data loading when the raw data loading is available.|
|update_xmp_data|Gets or sets a value indicating whether to update the XMP metadata.|
|xmp_data|Gets or sets the XMP metadata.|
|raw_indexed_color_converter|Gets or sets the indexed color converter|
|raw_custom_color_converter|Gets or sets the custom color converter|
|raw_fallback_index|Gets or sets the fallback index to use when palette index is out of bounds|
|raw_data_settings|Gets the current raw data settings. Note when using these settings the data loads without conversion.|
|raw_data_format|Gets the raw data format.|
|raw_line_size|Gets the raw line size in bytes.|
|is_raw_data_available|Gets a value indicating whether raw data loading is available.|
|horizontal_resolution|Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).|
|vertical_resolution|Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).|
|has_transparent_color|Gets a value indicating whether image has transparent color.|
|has_alpha|Gets a value indicating whether this instance has alpha.|
|transparent_color|Gets the image transparent color.|
|image_opacity|Gets opacity of this image.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save(stream, options_base, bounds_rectangle)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save()|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(file_path)|Saves the image to the specified file location.|
|save(file_path, options)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save(file_path, options, bounds_rectangle)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save(stream, options_base)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(stream)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(file_path, over_write)|  |
|can_load(file_path)|Determines whether image can be loaded from the specified file path.|
|can_load(file_path, load_options)|Determines whether image can be loaded from the specified file path and optionally using the specified open options.|
|can_load(stream)|Determines whether image can be loaded from the specified stream.|
|can_load(stream, load_options)|Determines whether image can be loaded from the specified stream and optionally using the specified|
|create(image_options, width, height)|Creates a new image using the specified create options.|
|create(images)|Creates a new image using the specified images as pages|
|create(images, dispose_images)|Creates a new image the specified images as pages.|
|get_file_format(file_path)|Gets the file format.|
|get_file_format(stream)|Gets the file format.|
|get_fitting_rectangle(rectangle, width, height)|Gets rectangle which fits the current image.|
|get_fitting_rectangle(rectangle, pixels, width, height)|Gets rectangle which fits the current image.|
|load(file_path, load_options)|Loads a new image from the specified file.|
|load(file_path)|Loads a new image from the specified file.|
|load(stream, load_options)|Loads a new image from the specified stream.|
|load(stream)|Loads a new image from the specified stream.|
|resize(new_width, new_height, resize_type)|Resizes the image.|
|resize(new_width, new_height, settings)|Resizes the image with extended options.|
|resize(new_width, new_height)|Resizes the image.|
|resize_width_proportionally(new_width)|Resizes the width proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.|
|resize_width_proportionally(new_width, resize_type)|Resizes the width proportionally.|
|resize_width_proportionally(new_width, settings)|Resizes the width proportionally.|
|resize_height_proportionally(new_height)|Resizes the height proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.|
|resize_height_proportionally(new_height, resize_type)|Resizes the height proportionally.|
|resize_height_proportionally(new_height, settings)|Resizes the height proportionally.|
|dither(dithering_method, bits_count)|Performs dithering on the current image.|
|dither(dithering_method, bits_count, custom_palette)|Performs dithering on the current image.|
|get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)|Gets the default raw data array using partial pixel loader.|
|get_default_raw_data(rectangle, raw_data_settings)|Gets the default raw data array using partial pixel loader.|
|load_raw_data(rectangle, raw_data_settings, raw_data_loader)|Loads raw data.|
|load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)|Loads raw data.|
|crop(rectangle)|Crops the specified rectangle.|
|crop(left_shift, right_shift, top_shift, bottom_shift)|Crop image with shifts.|
|binarize_bradley(brightness_difference)|Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding|
|binarize_bradley(brightness_difference, window_size)|Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding|
|adjust_gamma(gamma_red, gamma_green, gamma_blue)|Gamma-correction of an image.|
|adjust_gamma(gamma)|Gamma-correction of an image.|
|rotate(angle, resize_proportionally, background_color)|Rotate image around the center.|
|rotate(angle)|Rotate image around the center.|
|normalize_angle()|Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [None](/imaging/python-net/aspose.imaging/rasterimage/) and|
|normalize_angle(resize_proportionally, background_color)|Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [None](/imaging/python-net/aspose.imaging/rasterimage/) and|
|replace_color(old_color, old_color_diff, new_color)|Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.|
|replace_color(old_color_argb, old_color_diff, new_color_argb)|Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.|
|replace_non_transparent_colors(new_color)|Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one.|
|replace_non_transparent_colors(new_color_argb)|Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one.|
|cache_data()|  |
|save_to_stream(stream)|Saves the image's data to the specified stream in the specified file format according to save options.|
|can_load_with_options(file_path, load_options)|Determines whether image can be loaded from the specified file path and optionally using the specified open options.|
|can_load_stream(stream)|Determines whether image can be loaded from the specified stream.|
|can_load_stream_with_options(stream, load_options)|Determines whether image can be loaded from the specified stream and optionally using the specified|
|get_file_format_of_stream(stream)|Gets the file format.|
|load_with_options(file_path, load_options)|Loads a new image from the specified file.|
|load_stream_with_options(stream, load_options)|Loads a new image from the specified stream.|
|load_stream(stream)|Loads a new image from the specified stream.|
|can_save(options)|Determines whether image can be saved to the specified file format represented by the passed save options.|
|resize_by_type(new_width, new_height, resize_type)|Resizes the image.|
|resize_by_settings(new_width, new_height, settings)|Resizes the image with extended options.|
|get_default_options(args)|Gets the default options.|
|get_original_options()|Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the|
|resize_width_proportionally_settings(new_width, settings)|Resizes the width proportionally.|
|resize_height_proportionally_settings(new_height, settings)|Resizes the height proportionally.|
|rotate_flip(rotate_flip_type)|Rotates, flips, or rotates and flips the image.|
|save_with_options(file_path, options)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save_with_options_rect(file_path, options, bounds_rectangle)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save_to_stream_with_options(stream, options_base)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)|Saves the image's data to the specified stream in the specified file format according to save options.|
|set_palette(palette, update_colors)|Sets the image palette.|
|get_proportional_width(width, height, new_height)|Gets a proportional width.|
|get_proportional_height(width, height, new_width)|Gets a proportional height.|
|get_modify_date(use_default)|Gets the date and time the resource image was last modified.|
|get_default_pixels(rectangle, partial_pixel_loader)|Gets the default pixels array using partial pixel loader.|
|get_default_argb_32_pixels(rectangle)|Gets the default 32-bit ARGB pixels array.|
|get_argb_32_pixel(x, y)|Gets an image 32-bit ARGB pixel.|
|get_pixel(x, y)|Gets an image pixel.|
|set_argb_32_pixel(x, y, argb_32_color)|Sets an image 32-bit ARGB pixel for the specified position.|
|set_pixel(x, y, color)|Sets an image pixel for the specified position.|
|read_scan_line(scan_line_index)|Reads the whole scan line by the specified scan line index.|
|read_argb_32_scan_line(scan_line_index)|Reads the whole scan line by the specified scan line index.|
|write_scan_line(scan_line_index, pixels)|Writes the whole scan line to the specified scan line index.|
|write_argb_32_scan_line(scan_line_index, argb_32_pixels)|Writes the whole scan line to the specified scan line index.|
|load_partial_argb_32_pixels(rectangle, partial_pixel_loader)|Loads 32-bit ARGB pixels partially by packs.|
|load_partial_pixels(desired_rectangle, pixel_loader)|Loads pixels partially by packs.|
|load_argb_32_pixels(rectangle)|Loads 32-bit ARGB pixels.|
|load_argb_64_pixels(rectangle)|Loads 64-bit ARGB pixels.|
|load_partial_argb_64_pixels(rectangle, partial_pixel_loader)|Loads 64-bit ARGB pixels partially by packs.|
|load_pixels(rectangle)|Loads pixels.|
|load_cmyk_pixels(rectangle)|Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the|
|load_cmyk_32_pixels(rectangle)|Loads pixels in CMYK format.|
|save_raw_data(data, data_offset, rectangle, raw_data_settings)|Saves the raw data.|
|save_argb_32_pixels(rectangle, pixels)|Saves the 32-bit ARGB pixels.|
|save_pixels(rectangle, pixels)|Saves the pixels.|
|to_bitmap()|Converts raster image to the bitmap.|
|save_cmyk_pixels(rectangle, pixels)|Saves the pixels.<br/>            This method is deprecated. Please use more effective the|
|save_cmyk_32_pixels(rectangle, pixels)|Saves the pixels.|
|set_resolution(dpi_x, dpi_y)|Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).|
|binarize_fixed(threshold)|Binarization of an image with predefined threshold|
|binarize_otsu()|Binarization of an image with Otsu thresholding|
|grayscale()|Transformation of an image to its grayscale representation|
|adjust_brightness(brightness)|Adjust of a brightness for image.|
|adjust_contrast(contrast)|Image contrasting|
|get_skew_angle()|Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning.|
|filter(rectangle, options)|Filters the specified rectangle.|
|replace_argb(old_color_argb, old_color_diff, new_color_argb)|Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.|
