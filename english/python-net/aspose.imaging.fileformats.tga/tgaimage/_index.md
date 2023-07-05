---
title: TgaImage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.tga/tgaimage/
---

The TGA image.

**Namespace:** [aspose.imaging.fileformats.tga](/imaging/python-net/aspose.imaging.fileformats.tga/)

**Full Class Name:** aspose.imaging.fileformats.tga.TgaImage

**Assembly:**  Aspose.Imaging Version: 23.6.0

The TgaImage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|TgaImage(path)|Initializes a new instance of the TgaImage class|
|TgaImage(raster_image)|Initializes a new instance of the TgaImage class|
|TgaImage(stream)|Initializes a new instance of the TgaImage class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|data_stream_container|  |
|is_cached|Gets a value indicating whether image data is cached currently.|
|bits_per_pixel|Gets bits per pixel.|
|bounds|Gets the object bounds.|
|container|  |
|height|Gets this image height.|
|palette|  |
|use_palette|  |
|size|Gets the object size.|
|width|Gets this image width.|
|interrupt_monitor|  |
|buffer_size_hint|  |
|auto_adjust_palette|  |
|has_background_color|Gets or sets a value indicating whether the image has background color.|
|file_format|Gets the file format.|
|background_color|Gets or sets the background color.|
|premultiply_components|  |
|use_raw_data|  |
|update_xmp_data|  |
|xmp_data|  |
|raw_indexed_color_converter|  |
|raw_custom_color_converter|  |
|raw_fallback_index|  |
|raw_data_settings|Gets the current raw data settings. Note when using these settings the data loads without conversion.|
|raw_data_format|  |
|raw_line_size|  |
|is_raw_data_available|Gets a value indicating whether raw data loading is supported.|
|horizontal_resolution|  |
|vertical_resolution|  |
|has_transparent_color|Gets or sets a value indicating whether the image has transparent color.|
|has_alpha|Gets a value indicating whether  this [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) has an alpha channel.|
|transparent_color|Gets or sets Key Color.|
|image_opacity|  |
|bytes_per_pixel|Gets bytes per pixel.|
|is_gray_scale|Gets a value indicating whether this [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) is gray-scale.|
|has_color_map|Gets a value indicating whether this image has color map.|
|gamma_value_numerator|Gets Gamma Value Numerator part.<br/>            An uncorrected image (an image with no gamma) should have the value 1.0 as the result.|
|gamma_value_denominator|Gets Gamma Value Denominator part.<br/>            An uncorrected image (an image with no gamma) should have the value 1.0 as the result.|
|pixel_aspect_ratio_numerator|Gets Pixel Aspect Ratio numerator part.|
|pixel_aspect_ratio_denominator|Gets Pixel Aspect Ratio denominator part.|
|x_origin|Gets or sets absolute horizontal coordinate for the lower left corner of the image<br/>            as it is positioned on a display device having an origin at the lower left of the<br/>            screen(e.g., the TARGA series).|
|y_origin|Gets or sets absolute vertical coordinate for the lower left corner of the image<br/>            as it is positioned on a display device having an origin at the lower left of the<br/>            screen(e.g., the TARGA series).|
|image_id|Gets or sets Image ID.|
|author_comments|Gets or sets Author Comments.<br/>            This is an ASCII field consisting of 324 bytes which are organized as four lines<br/>            of 80 characters, each followed by a null terminator.|
|author_name|Gets or sets Author Name.<br/>            This field is a total of 40 ASCII characters for the name. If the field is used,<br/>            it should contain the name of the person who created the image (author).|
|date_time_stamp|Gets or sets Date/Time Stamp.<br/>            This field defines the value for the date and time that the image was saved. <br/>            Even though operating systems typically time- and date-stamp files, this feature is<br/>            provided because the operating system may change the time and date stamp if the file is<br/>            copied. By using this area, you are guaranteed an unmodified region for date and time<br/>            recording.|
|job_name_or_id|Gets or sets Job Name/ID.|
|job_time|Gets or sets Job Time.|
|software_version|Gets or sets Software Version. Accepted version string length is 3-4 characters.|
|software_version_letter|Gets or sets Software Version letter part.|
|software_version_number|Gets or sets Software Version number part.|
|software_id|Gets or sets Software ID.<br/>            A total of 40 ASCII characters for the Software ID.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save(stream, options_base, bounds_rectangle)|The save data.|
|save()|The save data.|
|save(file_path)|The save data.|
|save(file_path, options)|The save data.|
|save(file_path, options, bounds_rectangle)|The save data.|
|save(stream, options_base)|The save data.|
|save(stream)|The save data.|
|save(file_path, over_write)|The save data.|
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
|resize(new_width, new_height, settings)|Resizes the image.|
|resize(new_width, new_height, resize_type)|Resizes the image.|
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
|crop(left_shift, right_shift, top_shift, bottom_shift)|Crop image with shifts.|
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
|clone()|Creates a new object that is a copy of the current instance.|
|clone(tga_image)|Creates a new object that is a copy of the current instance.|
|cache_data()|Caches the data and ensures no additional data loading will be performed from the underlying [data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/).|
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
|rotate_flip(rotate_flip_type)|The rotate flip.|
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
|create_from_image(raster_image)|Initializes a new instance of the [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) class.|
|create_from_stream(stream)|Initializes a new instance of the [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) class.|
