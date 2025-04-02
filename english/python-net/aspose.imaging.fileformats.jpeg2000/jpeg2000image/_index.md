---
title: Jpeg2000Image Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---

**Summary:** Efficiently manipulate JPEG2000 (JP2) image files with our API, supporting<br/>            a range of bits per pixel depths and seamless processing of XMP metadata<br/>            containing essential image information. With capabilities for lossless compression,<br/>            ensure optimal image quality while maintaining file integrity, empowering you to<br/>            tailor JP2 images to your exact specifications with ease.

**Module:** [aspose.imaging.fileformats.jpeg2000](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/)

**Full Name:** aspose.imaging.fileformats.jpeg2000.Jpeg2000Image

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IHasXmpData, IHasMetadata, RasterCachedImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Jpeg2000Image(image)](#Jpeg2000Image_image_1) | Instantiate a new [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class with a raster image. This <br/>            constructor facilitates the creation of a JPEG2000 image from an existing raster <br/>            image, offering seamless integration and conversion between different image formats. |
| [Jpeg2000Image(path)](#Jpeg2000Image_path_2) | Start working with the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class by initializing a new <br/>            instance with the path to the image you want to load. This constructor enables easy <br/>            access to JPEG2000 images, simplifying the process of loading and handling image <br/>            files. By providing the file path, you can quickly begin processing and <br/>            manipulating JPEG2000 images in your application. |
| [Jpeg2000Image(path, bits_per_pixel)](#Jpeg2000Image_path_bits_per_pixel_3) | Get started easily with the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class by creating a new <br/>            instance with both the file path and the desired bits per pixel parameter. This <br/>            constructor allows for fine-tuning the image loading process, ensuring <br/>            compatibility with various image formats and quality settings. With this <br/>            flexibility, you can efficiently manage and manipulate JPEG2000 images according to <br/>            your specific requirements. |
| [Jpeg2000Image(raster_image, bits_per_pixel)](#Jpeg2000Image_raster_image_bits_per_pixel_4) | Initialize a fresh [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) instance with a raster image and <br/>            bits per pixel parameters. This constructor enables precise control over the <br/>            quality and size of the resulting JPEG2000 image, making it ideal for scenarios <br/>            where customization is crucial. |
| [Jpeg2000Image(stream)](#Jpeg2000Image_stream_5) | Easily initialize a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class by <br/>            providing a stream object. This constructor simplifies the process of loading <br/>            JPEG2000 images directly from streams, offering flexibility and convenience for <br/>            handling image data from various sources. |
| [Jpeg2000Image(stream, bits_per_pixel)](#Jpeg2000Image_stream_bits_per_pixel_6) | Initialize a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class with a stream to <br/>            load the image, along with bits per pixel parameters. This constructor offers <br/>            flexibility by allowing you to specify both the image data source and the desired <br/>            bits per pixel, providing finer control over the image loading process. |
| [Jpeg2000Image(width, height)](#Jpeg2000Image_width_height_7) | Create a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class, specifying the <br/>            width and height parameters. This constructor allows you to initialize a JPEG2000 <br/>            image with specific dimensions, which is useful for scenarios where you need to <br/>            create an image of a certain size programmatically. |
| [Jpeg2000Image(width, height, bits_count)](#Jpeg2000Image_width_height_bits_count_8) | Create a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class with parameters for <br/>            width, height, and bits count. This constructor allows for the creation of JPEG2000 <br/>            images with specific dimensions and bit depths, providing flexibility for various <br/>            imaging needs. |
| [Jpeg2000Image(width, height, options)](#Jpeg2000Image_width_height_options_9) | Instantiate a new [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) object, providing the width, height, <br/>            and image options parameters. This constructor allows for the creation of JPEG2000 <br/>            images with specific dimensions and additional options, offering flexibility in <br/>            image generation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | This property returns the depth of the image, measured in bits per pixel (bpp). It <br/>            indicates the amount of color information stored in each pixel of the image. <br/>            Understanding the image depth is crucial for determining the color fidelity and <br/>            quality of the image. With this information, users can gauge the level of detail <br/>            and richness of colors present in the image. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| codec | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec) | r | This property retrieves the JPEG2000 codec associated with the image. The JPEG2000 <br/>            codec is responsible for encoding and decoding the image data in the JPEG2000 <br/>            format, providing efficient compression while maintaining high image quality. <br/>            Accessing this codec can be useful for performing advanced image processing <br/>            operations or optimizing image compression settings tailored to specific requirements. |
| comments | string | r/w | This property allows for retrieving or updating the comments associated with the <br/>            image. Comments provide additional information about the image content, such as <br/>            annotations, descriptions, or metadata. Modifying these comments can be useful for <br/>            organizing and categorizing images, as well as conveying important details to <br/>            viewers or users. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Retrieve the format of the image file. This property provides information about the <br/>            file format of the image. Utilize this property to determine the format of the <br/>            image file programmatically, facilitating appropriate handling and processing based <br/>            on the file's format. |
| has_alpha | bool | r | Gets a value indicating whether this instance has alpha. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| has_transparent_color | bool | r/w | Gets a value indicating whether image has transparent color. |
| height | int | r | This property retrieves the height of the image in pixels. It serves as essential <br/>            information for understanding the image's vertical dimensions, aiding in various <br/>            image manipulation tasks like resizing, cropping, and rendering. Accessing this <br/>            property allows users to ascertain the image's vertical size, enabling precise <br/>            layout and display in applications. |
| horizontal_resolution | double | r/w | This property allows you to retrieve or modify the horizontal resolution of the<br/>            [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), measured in pixels per inch (PPI). Adjusting this <br/>            resolution can impact the size and quality of the image when printed or displayed. <br/>            By setting the horizontal resolution, users can optimize the image for specific <br/>            output devices or applications, ensuring the best possible visual results. |
| image_opacity | float | r | Gets opacity of this image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter) | r/w | Gets or sets the custom color converter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | This property retrieves the raw data format of the image. It provides information <br/>            about how the pixel data is stored in memory. Use this property to understand the <br/>            underlying data format of the image, which can be crucial for various image <br/>            processing operations like color conversion, compression, or decompression. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter) | r/w | Gets or sets the indexed color converter |
| raw_line_size | int | r | This property retrieves the size of a single line of raw image data in bytes. It <br/>            indicates the amount of memory occupied by a single row of pixels in the image's <br/>            raw data format. Understanding the raw line size is essential for tasks such as <br/>            memory allocation, data manipulation, and image processing algorithms that operate <br/>            on individual image lines. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets the object size. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets the image transparent color. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| vertical_resolution | double | r/w | This property provides access to the vertical resolution of the<br/>            [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), measured in pixels per inch (PPI). Modifying this <br/>            resolution can affect the quality and size of the image when printed or displayed. <br/>            By adjusting the vertical resolution, users can optimize the image for different <br/>            output devices or applications, ensuring optimal visual rendering. |
| width | int | r | This property returns the width of the image in pixels. It provides a fundamental <br/>            piece of information about the image's dimensions, crucial for various image <br/>            processing tasks, including resizing, cropping, and rendering. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Retrieve or modify the XMP metadata associated with the image. This property grants <br/>            access to the Extensible Metadata Platform (XMP) information embedded within the <br/>            image file, allowing for manipulation or extraction of metadata attributes such as <br/>            author details, copyright information, and descriptive tags. Utilizing this <br/>            property empowers you to manage and leverage metadata embedded within the image, <br/>            enhancing interoperability and metadata-driven workflows in your image processing tasks. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Adjust of a brightness for image. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Image contrasting |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Gamma-correction of an image. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Gamma-correction of an image. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_5) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_6) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_7) | Binarization of an image with predefined threshold |
| binarize_otsu() | Binarization of an image with Otsu thresholding |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_8) | Blends this image instance with the _overlay_ image. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_9) | Blends this image instance with the _overlay_ image. |
| cache_data() | Caches the data and ensures no additional data loading will be performed from the underlying [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_10) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_11) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_12) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_13) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_14) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_15) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_16) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_save(options)](#can_save_options_17) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [create(files)](#create_files_18) | Creates the multipage image containing the specified files. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_19) | Creates the multipage image containing the specified files. |
| [create(image_options, width, height)](#create_image_options_width_height_20) | Creates a new image using the specified create options. |
| [create(images)](#create_images_21) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_22) | Creates a new image the specified images as pages. |
| [create(multipage_create_options)](#create_multipage_create_options_23) | Creates the specified multipage create options. |
| [create_from_file_with_bpp(path, bits_per_pixel)](#create_from_file_with_bpp_path_bits_per_pixel_24) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_from_files(files)](#create_from_files_files_25) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_26) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_image(image)](#create_from_image_image_27) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_from_image_with_bpp(raster_image, bits_per_pixel)](#create_from_image_with_bpp_raster_image_bits_per_pixel_28) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_from_images(images)](#create_from_images_images_29) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_30) | Creates a new image the specified images as pages. |
| [create_from_stream(stream)](#create_from_stream_stream_31) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_from_stream_with_bpp(stream, bits_per_pixel)](#create_from_stream_with_bpp_stream_bits_per_pixel_32) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_with_width_height(width, height)](#create_with_width_height_width_height_33) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_with_width_height_bitscount(width, height, bits_count)](#create_with_width_height_bitscount_width_height_bits_count_34) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [create_with_width_height_options(width, height, options)](#create_with_width_height_options_width_height_options_35) | Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_36) | Crop image with shifts. |
| [crop(rectangle)](#crop_rectangle_37) | Cropping the image. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_38) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_39) | Performs dithering on the current image. |
| [filter(rectangle, options)](#filter_rectangle_options_40) | Filters the specified rectangle. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_41) | Gets an image 32-bit ARGB pixel. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_42) | Gets the default 32-bit ARGB pixels array. |
| [get_default_options(args)](#get_default_options_args_43) | Gets the default options. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_44) | Gets the default pixels array using partial pixel loader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45) | Gets the default raw data array using partial pixel loader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_46) | Gets the default raw data array. |
| [get_file_format(file_path)](#get_file_format_file_path_47) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_48) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_49) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_50) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_51) | Gets rectangle which fits the current image. |
| [get_modify_date(use_default)](#get_modify_date_use_default_52) | Gets the date and time the resource image was last modified. |
| [get_original_options()](#get_original_options__53) | Retrieve the image options based on the original file settings. This method is <br/>            beneficial for maintaining the bit-depth and other parameters of the original <br/>            image, ensuring consistency and preserving the integrity of the image data. <br/>            Accessing these options facilitates seamless handling and processing of the image <br/>            while retaining its original characteristics.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_54) | Gets an image pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_55) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_56) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_57) | Converts to aps. |
| [get_skew_angle()](#get_skew_angle__58) | Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| grayscale() | Transformation of an image to its grayscale representation |
| [load(file_path)](#load_file_path_59) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_60) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_61) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_62) | Loads a new image from the specified stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_63) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_64) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_65) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_66) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68) | Loads 64-bit ARGB pixels partially by packs. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_69) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_70) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72) | Loads raw data. |
| [load_stream(stream)](#load_stream_stream_73) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_74) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_75) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_76) | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) methods. |
| normalize_histogram() | Normalizes the image histogram — adjust pixel values to use all available range. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_77) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_78) | Reads the whole scan line by the specified scan line index. |
| remove_metadata() | Removes this image instance metadata by setting this [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) value to **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Resizes the image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Resizes the image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_93) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_94) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_95) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_96) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_97) | Rotate image around the center. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_98) | Rotate image around the center. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_99) | Rotates, flips, or rotates and flips the image. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_100) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_101) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_102) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_103) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_104) | Saves the object's data to the specified stream |
| [save(stream, options_base)](#save_stream_options_base_105) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_106) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_107) | Saves the 32-bit ARGB pixels. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_108) | Saves the pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_109) | Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_110) | Saves pixels (format specific method). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_111) | Saves the raw data. |
| [save_to_stream(stream)](#save_to_stream_stream_112) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_113) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_115) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_116) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_117) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_118) | Sets the image palette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_119) | Sets an image pixel for the specified position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_120) | Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_121) | Writes the whole scan line to the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_122) | Writes the whole scan line to the specified scan line index. |


### Constructor: Jpeg2000Image(image) {#Jpeg2000Image_image_1}


```
 Jpeg2000Image(image) 
```

Instantiate a new [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class with a raster image. This <br/>            constructor facilitates the creation of a JPEG2000 image from an existing raster <br/>            image, offering seamless integration and conversion between different image formats.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image. |

### Constructor: Jpeg2000Image(path) {#Jpeg2000Image_path_2}


```
 Jpeg2000Image(path) 
```

Start working with the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class by initializing a new <br/>            instance with the path to the image you want to load. This constructor enables easy <br/>            access to JPEG2000 images, simplifying the process of loading and handling image <br/>            files. By providing the file path, you can quickly begin processing and <br/>            manipulating JPEG2000 images in your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to load image from and initialize pixel and palette data with. |


**See also:**

**[Example # 1](#example_141)**: This example shows how to load a JPEG2000 image from a file and save it to PNG.


### Constructor: Jpeg2000Image(path, bits_per_pixel) {#Jpeg2000Image_path_bits_per_pixel_3}


```
 Jpeg2000Image(path, bits_per_pixel) 
```

Get started easily with the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class by creating a new <br/>            instance with both the file path and the desired bits per pixel parameter. This <br/>            constructor allows for fine-tuning the image loading process, ensuring <br/>            compatibility with various image formats and quality settings. With this <br/>            flexibility, you can efficiently manage and manipulate JPEG2000 images according to <br/>            your specific requirements.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to load image from and initialize pixel and palette data with |
| bits_per_pixel | int | The bits per pixel. |

### Constructor: Jpeg2000Image(raster_image, bits_per_pixel) {#Jpeg2000Image_raster_image_bits_per_pixel_4}


```
 Jpeg2000Image(raster_image, bits_per_pixel) 
```

Initialize a fresh [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) instance with a raster image and <br/>            bits per pixel parameters. This constructor enables precise control over the <br/>            quality and size of the resulting JPEG2000 image, making it ideal for scenarios <br/>            where customization is crucial.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |
| bits_per_pixel | int | The bits per pixel. |

### Constructor: Jpeg2000Image(stream) {#Jpeg2000Image_stream_5}


```
 Jpeg2000Image(stream) 
```

Easily initialize a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class by <br/>            providing a stream object. This constructor simplifies the process of loading <br/>            JPEG2000 images directly from streams, offering flexibility and convenience for <br/>            handling image data from various sources.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |


**See also:**

**[Example # 1](#example_142)**: This example shows how to load a JPEG2000 image from a file stream and save i...


### Constructor: Jpeg2000Image(stream, bits_per_pixel) {#Jpeg2000Image_stream_bits_per_pixel_6}


```
 Jpeg2000Image(stream, bits_per_pixel) 
```

Initialize a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class with a stream to <br/>            load the image, along with bits per pixel parameters. This constructor offers <br/>            flexibility by allowing you to specify both the image data source and the desired <br/>            bits per pixel, providing finer control over the image loading process.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |
| bits_per_pixel | int | The bits per pixel. |

### Constructor: Jpeg2000Image(width, height) {#Jpeg2000Image_width_height_7}


```
 Jpeg2000Image(width, height) 
```

Create a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class, specifying the <br/>            width and height parameters. This constructor allows you to initialize a JPEG2000 <br/>            image with specific dimensions, which is useful for scenarios where you need to <br/>            create an image of a certain size programmatically.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height |


**See also:**

**[Example # 1](#example_143)**: This example shows how to create a JPEG2000 image and save it to a file.


### Constructor: Jpeg2000Image(width, height, bits_count) {#Jpeg2000Image_width_height_bits_count_8}


```
 Jpeg2000Image(width, height, bits_count) 
```

Create a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class with parameters for <br/>            width, height, and bits count. This constructor allows for the creation of JPEG2000 <br/>            images with specific dimensions and bit depths, providing flexibility for various <br/>            imaging needs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height |
| bits_count | int | The bits count. |

### Constructor: Jpeg2000Image(width, height, options) {#Jpeg2000Image_width_height_options_9}


```
 Jpeg2000Image(width, height, options) 
```

Instantiate a new [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) object, providing the width, height, <br/>            and image options parameters. This constructor allows for the creation of JPEG2000 <br/>            images with specific dimensions and additional options, offering flexibility in <br/>            image generation.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height |
| options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | The options. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Adjust of a brightness for image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Image contrasting

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Gamma-correction of an image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_5}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_6}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_7}


```
 binarize_fixed(threshold) 
```

Binarization of an image with predefined threshold

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_8}


```
 blend(origin, overlay, overlay_alpha) 
```

Blends this image instance with the _overlay_ image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | The background image blending origin. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The overlay image. |
| overlay_alpha | byte | The overlay alpha. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_9}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Blends this image instance with the _overlay_ image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point) | The background image blending origin. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The overlay image. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The overlay area. |
| overlay_alpha | byte | The overlay alpha. |

### Method: can_load(file_path)  [static] {#can_load_file_path_10}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_11}


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


### Method: can_load(stream)  [static] {#can_load_stream_12}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_13}


```
 can_load(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_14}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_15}


```
 can_load_stream_with_options(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_16}


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


### Method: can_save(options) {#can_save_options_17}


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


### Method: create(files)  [static] {#create_files_18}


```
 create(files) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_19}


```
 create(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> [throw exception on load error]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_20}


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


### Method: create(images)  [static] {#create_images_21}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_22}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_23}


```
 create(multipage_create_options) 
```

Creates the specified multipage create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | The multipage create options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create_from_file_with_bpp(path, bits_per_pixel)  [static] {#create_from_file_with_bpp_path_bits_per_pixel_24}


```
 create_from_file_with_bpp(path, bits_per_pixel) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to load image from and initialize pixel and palette data with |
| bits_per_pixel | int | The bits per pixel. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_25}


```
 create_from_files(files) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_26}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> throw exception on load error. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create_from_image(image)  [static] {#create_from_image_image_27}


```
 create_from_image(image) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_from_image_with_bpp(raster_image, bits_per_pixel)  [static] {#create_from_image_with_bpp_raster_image_bits_per_pixel_28}


```
 create_from_image_with_bpp(raster_image, bits_per_pixel) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The image to initialize pixel and palette data with. |
| bits_per_pixel | int | The bits per pixel. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_29}


```
 create_from_images(images) 
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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_30}


```
 create_from_images(images, dispose_images) 
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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_31}


```
 create_from_stream(stream) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_from_stream_with_bpp(stream, bits_per_pixel)  [static] {#create_from_stream_with_bpp_stream_bits_per_pixel_32}


```
 create_from_stream_with_bpp(stream, bits_per_pixel) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |
| bits_per_pixel | int | The bits per pixel. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_with_width_height(width, height)  [static] {#create_with_width_height_width_height_33}


```
 create_with_width_height(width, height) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_with_width_height_bitscount(width, height, bits_count)  [static] {#create_with_width_height_bitscount_width_height_bits_count_34}


```
 create_with_width_height_bitscount(width, height, bits_count) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height |
| bits_count | int | The bits count. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: create_with_width_height_options(width, height, options)  [static] {#create_with_width_height_options_width_height_options_35}


```
 create_with_width_height_options(width, height, options) 
```

Initializes a new instance of the [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height |
| options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | The options. |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_36}


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

### Method: crop(rectangle) {#crop_rectangle_37}


```
 crop(rectangle) 
```

Cropping the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_38}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_39}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_40}


```
 filter(rectangle, options) 
```

Filters the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | The options. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_41}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_42}


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


### Method: get_default_options(args) {#get_default_options_args_43}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_44}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_46}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_47}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_48}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_49}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_50}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_51}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_52}


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


### Method: get_original_options() {#get_original_options__53}


```
 get_original_options() 
```

Retrieve the image options based on the original file settings. This method is <br/>            beneficial for maintaining the bit-depth and other parameters of the original <br/>            image, ensuring consistency and preserving the integrity of the image data. <br/>            Accessing these options facilitates seamless handling and processing of the image <br/>            while retaining its original characteristics.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options based on the original file settings. |


### Method: get_pixel(x, y) {#get_pixel_x_y_54}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_55}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_56}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_57}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Converts to aps.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The image options. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The clipping rectangle. |
| page_number | int[] | The page number. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The serialized stream |


### Method: get_skew_angle() {#get_skew_angle__58}


```
 get_skew_angle() 
```

Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning.

**Returns**

| Type | Description |
| :- | :- |
| float | The skew angle, in degrees. |


### Method: load(file_path)  [static] {#load_file_path_59}


```
 load(file_path) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_60}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(stream)  [static] {#load_stream_61}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_62}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_63}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_64}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_65}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_66}


```
 load_cmyk_pixels(rectangle) 
```

Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The loaded CMYK pixels array. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader) | The 64-bit ARGB pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_69}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_70}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_73}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_74}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_75}


```
 load_with_options(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_76}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_77}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_78}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color_argb | int | Old color ARGB value to be replaced. |
| old_color_diff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color_argb | int | New color ARGB value to replace old color with. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color) | New color to replace non transparent colors with. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>            Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_argb | int | New color ARGB value to replace non transparent colors with. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_93}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_94}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_95}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_96}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_97}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_98}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_99}


```
 rotate_flip(rotate_flip_type) 
```

Rotates, flips, or rotates and flips the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip type. |

### Method: save(file_path) {#save_file_path_100}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_101}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_102}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_103}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_104}


```
 save(stream) 
```

Saves the object's data to the specified stream

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to |

### Method: save(stream, options_base) {#save_stream_options_base_105}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_106}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_107}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_108}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Saves the pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_109}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_110}


```
 save_pixels(rectangle, pixels) 
```

Saves pixels (format specific method).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The 32-bit ARGB pixels array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_111}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_112}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_113}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_115}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_116}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_117}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_118}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_119}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_120}


```
 set_resolution(dpi_x, dpi_y) 
```

Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dpi_x | double | The horizontal resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | double | The vertical resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_121}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| argb_32_pixels | int | The 32-bit ARGB colors array to write. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_122}


```
 write_scan_line(scan_line_index, pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The pixel colors array to write. |

## **Examples**
### This example shows how to load a JPEG2000 image from a file and save it to PNG. {#example_141}
``` python
import aspose.pycore as aspycore
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Load a JPEG2000 image.
with Jpeg2000Image(join(dir_, "sample.jp2")) as jpeg2000_image:
	# Save to PNG
	jpeg2000_image.save(join(dir_, "sample.output.png"), PngOptions())


```

### This example shows how to load a JPEG2000 image from a file stream and save it to PNG. {#example_142}
``` python
import aspose.pycore as aspycore
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Load a JPEG2000 image from stream.
with open(join(dir_, "sample.jp2"), "rb") as stream:
	with Jpeg2000Image(stream) as jpeg2000_image:
		# Save to PNG
		jpeg2000_image.save(join(dir_, "sample.output.png"), PngOptions())


```

### This example shows how to create a JPEG2000 image and save it to a file. {#example_143}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import Jpeg2000Options
from os.path import join

dir_: str = "c:\\temp"
# Create a JPEG2000 image of 100x100 px.
with Jpeg2000Image(100, 100) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# Fill the entire image in red.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# Save to a file
	jpeg2000_image.save(join(dir_, "sample.output.jp2"), Jpeg2000Options())


```

