---
title: JpegImage Class
type: docs
weight: 20
url: /python-net/aspose.imaging.fileformats.jpeg/jpegimage/
---

A jpeg image.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.JpegImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.Imaging Version:** 23.6

The JpegImage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [JpegImage(path)](#JpegImage_path_0) | Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class. |
| [JpegImage(stream)](#JpegImage_stream_1) | Initializes a new instance of the JpegImage class |
| [JpegImage(raster_image)](#JpegImage_raster_image_2) | Initializes a new instance of the JpegImage class |
| [JpegImage(width, height)](#JpegImage_width_height_3) | Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class. |
| [JpegImage(jpeg_options, width, height)](#JpegImage_jpeg_options_width_height_4) | Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| height | int | r | Gets the image height. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets the object size. |
| width | int | r | Gets the image width. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Gets a value of file format |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a value for the background color. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata. |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter) | r/w | Gets or sets the indexed color converter |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter) | r/w | Gets or sets the custom color converter |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the raw data format. |
| raw_line_size | int | r | Gets the raw line size in bytes. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| horizontal_resolution | double | r/w | Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| vertical_resolution | double | r/w | Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| has_transparent_color | bool | r/w | Gets a value indicating whether image has transparent color. |
| has_alpha | bool | r | Gets a value indicating whether this instance has alpha. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets the image transparent color. |
| image_opacity | float | r | Gets opacity of this image. |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | r | Gets the JPEG options used to create or load this [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) instance. |
| comment | string | r/w | Gets or sets the jpeg file comment. |
| exif_data | [JpegExifData](/imaging/python-net/aspose.imaging.exif/jpegexifdata/) | r/w | Get or set exif data container |
| jfif | [JFIFData](/imaging/python-net/aspose.imaging.fileformats.jpeg/jfifdata) | r/w | Gets or sets the jfif. |
| rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | The RGB color profile for CMYK and YCCK jpeg images. Must be in pair with CMYKColorProfile for correct color conversion. |
| cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | The CMYK color profile for CMYK and YCCK jpeg images. Must be in pair with RGBColorProfile for correct color conversion. |
| destination_rgb_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | The RGB color profile for CMYK and YCCK jpeg images, used for image saving process. Must be in pair with CMYKColorProfile for correct color conversion. |
| destination_cmyk_color_profile | [StreamSource](/imaging/python-net/aspose.imaging.sources/streamsource/) | r/w | The CMYK color profile for CMYK and YCCK jpeg images, used for image saving process. Must be in pair with RGBColorProfile for correct color conversion. |
| ignore_embedded_color_profile | bool | r/w | Gets or sets a value indicating whether embedded color profile is ignored. If embedded color profile is ignored, dafault color profile is used. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_5) | Saves the image's data to the specified stream in the specified file format according to save options. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_6) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_7) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_8) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(stream, options_base)](#save_stream_options_base_9) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream)](#save_stream_10) | Saves the object's data to the specified stream. |
| [save(file_path, over_write)](#save_file_path_over_write_11) | Saves the object's data to the specified file location. |
| [can_load(file_path)](#can_load_file_path_12) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_13) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_14) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_15) | Determines whether image can be loaded from the specified stream and optionally using the specified <paramref name="loadOptions" />. |
| [create(image_options, width, height)](#create_image_options_width_height_16) | Creates a new image using the specified create options. |
| [create(images)](#create_images_17) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_18) | Creates a new image the specified images as pages. |
| [get_file_format(file_path)](#get_file_format_file_path_19) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_20) | Gets the file format. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_21) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_22) | Gets rectangle which fits the current image. |
| [load(file_path, load_options)](#load_file_path_load_options_23) | Loads a new image from the specified file. |
| [load(file_path)](#load_file_path_24) | Loads a new image from the specified file. |
| [load(stream, load_options)](#load_stream_load_options_25) | Loads a new image from the specified stream. |
| [load(stream)](#load_stream_26) | Loads a new image from the specified stream. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_27) | Resizes the image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_28) | Resizes the image. |
| [resize(new_width, new_height)](#resize_new_width_new_height_29) | Resizes the image. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_30) | Resizes the width proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_31) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_32) | Resizes the width proportionally. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_33) | Resizes the height proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_34) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_35) | Resizes the height proportionally. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_36) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_37) | Performs dithering on the current image. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_38) | Gets the default raw data array using partial pixel loader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_39) | Gets the default raw data array. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_40) | Loads raw data. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_41) | Loads raw data. |
| [crop(rectangle)](#crop_rectangle_42) | Cropping the image. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_43) | Crop image with shifts. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_44) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_45) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_46) | Gamma-correction of an image. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_47) | Gamma-correction of an image. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_48) | Rotate image around the center. |
| [rotate(angle)](#rotate_angle_49) | Rotate image around the center. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [None](/imaging/python-net/aspose.imaging/rasterimage/) and <see cref="M:Aspose.Imaging.RasterImage.Rotate(float)" /> methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_50) | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [None](/imaging/python-net/aspose.imaging/rasterimage/) and <see cref="M:Aspose.Imaging.RasterImage.Rotate(float,System.Boolean,Aspose.Imaging.Color)" /> methods. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_51) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |    |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_52) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_53) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| cache_data() | Caches the data and ensures no additional data loading will be performed from the underlying [data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [save_to_stream(stream)](#save_to_stream_stream_54) | Saves the object's data to the specified stream. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_55) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load_stream(stream)](#can_load_stream_stream_56) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_57) | Determines whether image can be loaded from the specified stream and optionally using the specified <paramref name="loadOptions" />. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_58) | Gets the file format. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_59) | Loads a new image from the specified file. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_60) | Loads a new image from the specified stream. |
| [load_stream(stream)](#load_stream_stream_61) | Loads a new image from the specified stream. |
| [can_save(options)](#can_save_options_62) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_63) | Resizes the image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_64) | Resizes the image. |
| [get_default_options(args)](#get_default_options_args_65) | Gets the default options. |
| [get_original_options()](#get_original_options__66) | Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            <see cref="M:Aspose.Imaging.DataStreamSupporter.Save(System.String)" /> method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the <see cref="M:Aspose.Imaging.Image.Save(System.String,Aspose.Imaging.ImageOptionsBase)" /> method as the second parameter. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_67) | Resizes the width proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_68) | Resizes the height proportionally. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_69) | Rotates, flips, or rotates and flips the image. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_70) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_71) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_72) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_73) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_74) | Sets the image palette. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_75) | Gets a proportional width. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_76) | Gets a proportional height. |
| [get_modify_date(use_default)](#get_modify_date_use_default_77) | Gets the date and time the resource image was last modified. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_78) | Gets the default pixels array using partial pixel loader. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_79) | Gets the default 32-bit ARGB pixels array. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_80) | Gets an image 32-bit ARGB pixel. |
| [get_pixel(x, y)](#get_pixel_x_y_81) | Gets an image pixel. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_82) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_83) | Sets an image pixel for the specified position. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_84) | Reads the whole scan line by the specified scan line index. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_85) | Reads the whole scan line by the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_86) | Writes the whole scan line to the specified scan line index. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_87) | Writes the whole scan line to the specified scan line index. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_88) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_89) | Loads pixels partially by packs. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_90) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_91) | Loads 64-bit ARGB pixels. |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_92) | Loads 64-bit ARGB pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_93) | Loads pixels. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_94) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the <see cref="M:Aspose.Imaging.RasterImage.LoadCmyk32Pixels(Aspose.Imaging.Rectangle)" /> method. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_95) | Loads pixels in CMYK format. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Saves the raw data. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_97) | Saves the 32-bit ARGB pixels. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_98) | Saves pixels (format specific method). |
| [to_bitmap()](#to_bitmap__99) | Converts raster image to the bitmap. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_100) | Saves the pixels.<br/>            This method is deprecated. Please use more effective the <see cref="M:Aspose.Imaging.RasterImage.SaveCmyk32Pixels(Aspose.Imaging.Rectangle,int[])" /> method. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_101) | Saves the pixels. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_102) | Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_103) | Binarization of an image with predefined threshold |
| binarize_otsu() | Binarization of an image with Otsu thresholding |
| grayscale() | Transformation of an image to its grayscale representation |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_104) | Adjust of a brightness for image. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_105) | Image contrasting |
| [get_skew_angle()](#get_skew_angle__106) | Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| [filter(rectangle, options)](#filter_rectangle_options_107) | Filters the specified rectangle. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_108) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [create_from_stream(stream)](#create_from_stream_stream_109) | Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class. |
| [create_from_image(raster_image)](#create_from_image_raster_image_110) | Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class. |
| auto_rotate() | Perform automatic rotate of image depending on orientation data provided by Exif. |

### JpegImage(path) {#JpegImage_path_0}


```
 JpegImage(path) 
```

Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to load image from and initialize pixel and palette data with. |

### JpegImage(stream) {#JpegImage_stream_1}


```
 JpegImage(stream) 
```

Initializes a new instance of the JpegImage class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

### JpegImage(raster_image) {#JpegImage_raster_image_2}


```
 JpegImage(raster_image) 
```

Initializes a new instance of the JpegImage class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) |  |

### JpegImage(width, height) {#JpegImage_width_height_3}


```
 JpegImage(width, height) 
```

Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width. |
| height | int | The image height. |

### JpegImage(jpeg_options, width, height) {#JpegImage_jpeg_options_width_height_4}


```
 JpegImage(jpeg_options, width, height) 
```

Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/imaging/python-net/aspose.imaging.imageoptions/jpegoptions/) | The jpeg options. |
| width | int | Image width. |
| height | int | Image height. |

### save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_5}


```
 save(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### save(file_path) {#save_file_path_6}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### save(file_path, options) {#save_file_path_options_7}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_8}


```
 save(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### save(stream, options_base) {#save_stream_options_base_9}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### save(stream) {#save_stream_10}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### save(file_path, over_write) {#save_file_path_over_write_11}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### can_load(file_path)  [static] {#can_load_file_path_12}


```
 can_load(file_path) 
```

Determines whether image can be loaded from the specified file path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_13}


```
 can_load(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### can_load(stream)  [static] {#can_load_stream_14}


```
 can_load(stream) 
```

Determines whether image can be loaded from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### can_load(stream, load_options)  [static] {#can_load_stream_load_options_15}


```
 can_load(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### create(image_options, width, height)  [static] {#create_image_options_width_height_16}


```
 create(image_options, width, height) 
```

Creates a new image using the specified create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The image options. |
| width | int | The width. |
| height | int | The height. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The newly created image. |


### create(images)  [static] {#create_images_17}


```
 create(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The Image as IMultipageImage |


### create(images, dispose_images)  [static] {#create_images_dispose_images_18}


```
 create(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The Image as IMultipageImage |


### get_file_format(file_path)  [static] {#get_file_format_file_path_19}


```
 get_file_format(file_path) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The determined file format. |


### get_file_format(stream)  [static] {#get_file_format_stream_20}


```
 get_file_format(stream) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The determined file format. |


### get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_21}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get fitting rectangle for. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The fitting rectangle or exception if no fitting rectangle can be found. |


### get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_22}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get fitting rectangle for. |
| pixels | int | The 32-bit ARGB pixels. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The fitting rectangle or exception if no fitting rectangle can be found. |


### load(file_path, load_options)  [static] {#load_file_path_load_options_23}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### load(stream, load_options)  [static] {#load_stream_load_options_25}


```
 load(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_27}


```
 resize(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_28}


```
 resize(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The resize settings. |

### resize(new_width, new_height) {#resize_new_width_new_height_29}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_30}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_31}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_32}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_33}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_34}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_35}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_36}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The custom palette for dithering. |

### dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_37}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_38}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Gets the default raw data array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get pixels for. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader) | The partial raw data loader. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | The raw data settings. |

### get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_39}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Gets the default raw data array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get raw data for. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | The raw data settings. |

**Returns**

| Type | Description |
| :- | :- |
| byte | The default raw data array. |


### load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_40}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load raw data from. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader) | The raw data loader. |

### load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_41}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load raw data from. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The dest image bounds. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader) | The raw data loader. |

### crop(rectangle) {#crop_rectangle_42}


```
 crop(rectangle) 
```

Cropping the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |

### crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_43}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Crop image with shifts.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left_shift | int | The left shift. |
| right_shift | int | The right shift. |
| top_shift | int | The top shift. |
| bottom_shift | int | The bottom shift. |

### binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_44}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_45}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_46}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gamma-correction of an image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma_red | float | Gamma for red channel coefficient |
| gamma_green | float | Gamma for green channel coefficient |
| gamma_blue | float | Gamma for blue channel coefficient |

### adjust_gamma(gamma) {#adjust_gamma_gamma_47}


```
 adjust_gamma(gamma) 
```

Gamma-correction of an image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_48}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### rotate(angle) {#rotate_angle_49}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_50}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [None](/imaging/python-net/aspose.imaging/rasterimage/) and <see cref="M:Aspose.Imaging.RasterImage.Rotate(float,System.Boolean,Aspose.Imaging.Color)" /> methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_51}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color) | Old color to be replaced. |
| old_color_diff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color) | New color to replace old color with. |

### replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_52}


```
 replace_non_transparent_colors(new_color) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color) | New color to replace non transparent colors with. |

### replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_53}


```
 replace_non_transparent_colors(new_color_argb) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_argb | int | New color ARGB value to replace non transparent colors with. |

### save_to_stream(stream) {#save_to_stream_stream_54}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_55}


```
 can_load_with_options(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### can_load_stream(stream)  [static] {#can_load_stream_stream_56}


```
 can_load_stream(stream) 
```

Determines whether image can be loaded from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_57}


```
 can_load_stream_with_options(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_58}


```
 get_file_format_of_stream(stream) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The determined file format. |


### load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_59}


```
 load_with_options(file_path, load_options) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_60}


```
 load_stream_with_options(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### load_stream(stream)  [static] {#load_stream_stream_61}


```
 load_stream(stream) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### can_save(options) {#can_save_options_62}


```
 can_save(options) 
```

Determines whether image can be saved to the specified file format represented by the passed save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options to use. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be saved to the specified file format represented by the passed save options; otherwise, <c>false</c>. |


### resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_63}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_64}


```
 resize_by_settings(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The resize settings. |

### get_default_options(args) {#get_default_options_args_65}


```
 get_default_options(args) 
```

Gets the default options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | object | The arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Default options |


### get_original_options() {#get_original_options__66}


```
 get_original_options() 
```

Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            <see cref="M:Aspose.Imaging.DataStreamSupporter.Save(System.String)" /> method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the <see cref="M:Aspose.Imaging.Image.Save(System.String,Aspose.Imaging.ImageOptionsBase)" /> method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options based on the original file settings. |


### resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_67}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_68}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_69}


```
 rotate_flip(rotate_flip_type) 
```

Rotates, flips, or rotates and flips the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip type. |

### save_with_options(file_path, options) {#save_with_options_file_path_options_70}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_71}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_72}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_73}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### set_palette(palette, update_colors) {#set_palette_palette_update_colors_74}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_75}


```
 get_proportional_width(width, height, new_height) 
```

Gets a proportional width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |
| new_height | int | The new height. |

**Returns**

| Type | Description |
| :- | :- |
| int | The proportional width. |


### get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_76}


```
 get_proportional_height(width, height, new_width) 
```

Gets a proportional height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |
| new_width | int | The new width. |

**Returns**

| Type | Description |
| :- | :- |
| int | The proportional height. |


### get_modify_date(use_default) {#get_modify_date_use_default_77}


```
 get_modify_date(use_default) 
```

Gets the date and time the resource image was last modified.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| use_default | bool | if set to <c>true</c> uses the information from FileInfo as default value. |

**Returns**

| Type | Description |
| :- | :- |
| datetime | The date and time the resource image was last modified. |


### get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_78}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_79}


```
 get_default_argb_32_pixels(rectangle) 
```

Gets the default 32-bit ARGB pixels array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get pixels for. |

**Returns**

| Type | Description |
| :- | :- |
| int | The default pixels array. |


### get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_80}


```
 get_argb_32_pixel(x, y) 
```

Gets an image 32-bit ARGB pixel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |

**Returns**

| Type | Description |
| :- | :- |
| int | The 32-bit ARGB pixel for the specified location. |


### get_pixel(x, y) {#get_pixel_x_y_81}


```
 get_pixel(x, y) 
```

Gets an image pixel.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color) | The pixel color for the specified location. |


### set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_82}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Sets an image 32-bit ARGB pixel for the specified position.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| argb_32_color | int | The 32-bit ARGB pixel for the specified position. |

### set_pixel(x, y, color) {#set_pixel_x_y_color_83}


```
 set_pixel(x, y, color) 
```

Sets an image pixel for the specified position.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| color | [Color](/imaging/python-net/aspose.imaging/color) | The pixel color for the specified position. |

### read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_84}


```
 read_scan_line(scan_line_index) 
```

Reads the whole scan line by the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The scan line pixel color values array. |


### read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_85}


```
 read_argb_32_scan_line(scan_line_index) 
```

Reads the whole scan line by the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |

**Returns**

| Type | Description |
| :- | :- |
| int | The scan line 32-bit ARGB color values array. |


### write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_86}


```
 write_scan_line(scan_line_index, pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The pixel colors array to write. |

### write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_87}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| argb_32_pixels | int | The 32-bit ARGB colors array to write. |

### load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_88}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_89}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader) | The pixel loader. |

### load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_90}


```
 load_argb_32_pixels(rectangle) 
```

Loads 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int | The loaded 32-bit ARGB pixels array. |


### load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_91}


```
 load_argb_64_pixels(rectangle) 
```

Loads 64-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| long | The loaded 64-bit ARGB pixels array. |


### load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_92}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader) | The 64-bit ARGB pixel loader. |

### load_pixels(rectangle) {#load_pixels_rectangle_93}


```
 load_pixels(rectangle) 
```

Loads pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color) | The loaded pixels array. |


### load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_94}


```
 load_cmyk_pixels(rectangle) 
```

Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the <see cref="M:Aspose.Imaging.RasterImage.LoadCmyk32Pixels(Aspose.Imaging.Rectangle)" /> method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The loaded CMYK pixels array. |


### load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_95}


```
 load_cmyk_32_pixels(rectangle) 
```

Loads pixels in CMYK format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int | The loaded CMYK pixels presentes as 32-bit inateger values. |


### save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Saves the raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | byte | The raw data. |
| data_offset | int | The starting raw data offset. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The raw data rectangle. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | The raw data settings the data is in. |

### save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_97}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The 32-bit ARGB pixels array. |

### save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_98}


```
 save_pixels(rectangle, pixels) 
```

Saves pixels (format specific method).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The 32-bit ARGB pixels array. |

### to_bitmap() {#to_bitmap__99}


```
 to_bitmap() 
```

Converts raster image to the bitmap.

**Returns**

| Type | Description |
| :- | :- |
| System.Drawing.Bitmap | The bitmap |


### save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_100}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Saves the pixels.<br/>            This method is deprecated. Please use more effective the <see cref="M:Aspose.Imaging.RasterImage.SaveCmyk32Pixels(Aspose.Imaging.Rectangle,int[])" /> method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The CMYK pixels array. |

### save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_101}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Saves the pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The CMYK pixels presented as the 32-bit integer values. |

### set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_102}


```
 set_resolution(dpi_x, dpi_y) 
```

Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dpi_x | double | The horizontal resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | double | The vertical resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### binarize_fixed(threshold) {#binarize_fixed_threshold_103}


```
 binarize_fixed(threshold) 
```

Binarization of an image with predefined threshold

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

### adjust_brightness(brightness) {#adjust_brightness_brightness_104}


```
 adjust_brightness(brightness) 
```

Adjust of a brightness for image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |

### adjust_contrast(contrast) {#adjust_contrast_contrast_105}


```
 adjust_contrast(contrast) 
```

Image contrasting

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |

### get_skew_angle() {#get_skew_angle__106}


```
 get_skew_angle() 
```

Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning.

**Returns**

| Type | Description |
| :- | :- |
| float | The skew angle, in degrees. |


### filter(rectangle, options) {#filter_rectangle_options_107}


```
 filter(rectangle, options) 
```

Filters the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | The options. |

### replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_108}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color_argb | int | Old color ARGB value to be replaced. |
| old_color_diff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color_argb | int | New color ARGB value to replace old color with. |

### create_from_stream(stream)  [static] {#create_from_stream_stream_109}


```
 create_from_stream(stream) 
```

Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |

**Returns**

| Type | Description |
| :- | :- |
| [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage) |  |


### create_from_image(raster_image)  [static] {#create_from_image_raster_image_110}


```
 create_from_image(raster_image) 
```

Initializes a new instance of the [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |

**Returns**

| Type | Description |
| :- | :- |
| [JpegImage](/imaging/python-net/aspose.imaging.fileformats.jpeg/jpegimage) |  |


