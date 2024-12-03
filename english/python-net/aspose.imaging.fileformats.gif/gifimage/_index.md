---
title: GifImage Class
type: docs
weight: 70
url: /python-net/aspose.imaging.fileformats.gif/gifimage/
---

**Summary:** The API for Graphical Interchange Format (GIF) image file provides<br/>            developers with versatile tools for processing compressed raster images and<br/>            animated GIFs. Offering features like XMP metadata handling, color palette<br/>            settings, background and transparent color control, opacity settings, resize,<br/>            crop, filter application, gamma corrections, contrast adjustment, grayscale<br/>            transformation, and conversion to other formats. This API empowers seamless<br/>            manipulation and enhancement of GIF images for a wide range of applications.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IHasXmpData, IHasMetadata, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifImage(first_frame)](#GifImage_first_frame_1) | Crafting GIF images becomes effortless with the [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) <br/>            constructor. With just the firstFrame parameter, it enters in a world of dynamic <br/>            visual communication. |
| [GifImage(first_frame, global_palette)](#GifImage_first_frame_global_palette_2) | Initiate a new [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) object with specified parameters for the <br/>            first frame and global palette. Start managing GIF images swiftly, ensuring <br/>            accurate representation with customizable settings for optimal results. |
| [GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer)](#GifImage_first_frame_global_palette_is_palette_sorted_palette_color_resolution_palette_background_color_index_aspect_ratio_has_trailer_3) | Get started effortlessly with the [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) constructor. With this <br/>            simple method, you can dive into creating animated GIFs with ease. Just supply the <br/>            firstFrame, globalPalette, paletteColorResolution, aspectRatio, and other <br/>            parameters, and you're ready to bring your visuals to life. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [active_frame](#active_frame1) | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | r/w | Manage and manipulate frames with this property, enabling smooth navigation and <br/>            modification of the active frame within the GIF image. |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Manage the background color of the GIF image with this property. You can set or <br/>            retrieve the background color to ensure consistency and enhance visual appeal. |
| background_color_index | byte | r/w | Control the background color index of the GIF image using this property. Set or <br/>            retrieve the index to maintain consistency or achieve desired visual effects. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| blocks | [IGifBlock[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock) | r | Gain access to the GIF blocks seamlessly with this property, facilitating easy <br/>            retrieval and manipulation of the image's underlying data structures. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Retrieve the file format effortlessly with this property. It's your go-to source <br/>            for identifying the format of your files. Seamlessly integrated into your workflow, <br/>            it provides vital information without any hassle. |
| has_alpha | bool | r | Gets a value indicating whether this instance has alpha. |
| has_background_color | bool | r/w | This property determines whether the GIF image contains a background color. If <br/>            true, it indicates that the image includes a background color. |
| has_trailer | bool | r/w | Manage the presence of a trailer in your GIF files with this property. Whether you <br/>            need to check if a trailer exists or set its presence, this property simplifies the <br/>            process. Keep your GIF files structured and compliant with this intuitive feature. |
| has_transparent_color | bool | r/w | Determine whether the active frame of the GIF image includes a transparent color. <br/>            This property provides a convenient way to check for transparency within the image. |
| height | int | r | Gets the image height. |
| horizontal_resolution | double | r/w | Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Retrieve the opacity of the active frame within the image, offering insight into <br/>            its transparency level. This property is particularly useful for understanding the <br/>            degree of transparency or opaqueness of the active frame in the image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_interlaced | bool | r | Determines if the image is interlaced, impacting its display during loading. This <br/>            property offers insight into the image's rendering behavior, essential for <br/>            optimizing loading strategies and enhancing overall viewing experience. |
| is_palette_sorted | bool | r/w | Control the sorting of the palette in your GIF images using this property. Whether <br/>            you need to check if the palette is sorted or set the sorting behavior, this <br/>            property provides a straightforward way to manage the palette organization in your <br/>            GIF files. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| loops_count | int | r/w | Retrieve the loop count effortlessly with this property. If your GIF image includes <br/>            loop information, this property gives you quick access to the loop count, enabling <br/>            you to seamlessly manage looping behavior in your GIF files. |
| page_count | int | r | Retrieve the total number of pages contained within the image with this <br/>            straightforward property. Ideal for quickly assessing the extent of the image content. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image) | r | Gain access to the pages within the image through this convenient property, <br/>            allowing seamless navigation and manipulation of individual pages as needed. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| palette_color_resolution_bits | byte | r/w | Manage the palette color resolution of your GIF images with this property. Adjust <br/>            the number of bits used to represent colors in the palette, providing fine control <br/>            over color depth and image quality. |
| pixel_aspect_ratio | byte | r/w | Manage the pixel aspect ratio of the GIF image with this property. Set or retrieve <br/>            the aspect ratio to ensure accurate rendering and maintain visual fidelity. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter) | r/w | Gets or sets the custom color converter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the raw data format. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter) | r/w | Gets or sets the indexed color converter |
| raw_line_size | int | r | Gets the raw line size in bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets the object size. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Retrieve the transparent color of the active frame in the GIF image. This property <br/>            allows you to access the specific color that has been designated as transparent <br/>            within the currently active frame. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| vertical_resolution | double | r/w | Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Gets the image width. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Manage XMP metadata with this property. Whether you're retrieving existing metadata <br/>            or updating it with new information, this property streamlines the process. Keep <br/>            your metadata organized and accessible, ensuring that your files contain the <br/>            relevant information they need. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Adding a new GIF block allows you to include additional data within the image. <br/>            This method enables you to append custom blocks to the GIF image, which can <br/>            contain various types of information. |
| [add_page(page)](#add_page_page_2) | Incorporate a new page seamlessly into the existing image, enhancing its content <br/>            and expanding its scope. This method augment image collections with additional <br/>            content, fostering creativity and flexibility in image management and composition. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Adjusts the brightness of the image according to the specified<br/>            _brightness_ parameter. This method modifies the brightness of <br/>            the entire image uniformly, enhancing or reducing the overall luminance to achieve <br/>            the desired effect. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Adjusts the contrast of the image, enhancing or reducing the difference in <br/>            brightness between pixels. This method modifies the image's overall tonal range, <br/>            making darker areas darker and brighter areas brighter to improve visual clarity <br/>            and detail. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Enhance image quality by applying gamma correction. This method adjusts the color <br/>            gamma of the image to achieve optimal visual clarity. It modifies the gamma value <br/>            of each pixel, resulting in improved color rendition and overall image appearance. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Gamma-correction of an image applies a nonlinear adjustment to the pixel values, <br/>            enhancing or reducing brightness based on the specified coefficients for the red, <br/>            green, and blue channels. This method helps to fine-tune the color balance and <br/>            luminance of the image, improving its overall appearance and visual quality. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_7) | Binarization of an image using Bradley's adaptive thresholding algorithm with <br/>            integral image thresholding is a method for converting a grayscale image into a <br/>            binary image. This algorithm calculates a local threshold for each pixel based on <br/>            the average intensity of the surrounding pixels within a specified window. By <br/>            adaptively adjusting the threshold based on local pixel intensities, Bradley's <br/>            method is effective at handling variations in lighting and contrast across the image. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_8) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_9) | Binarization of an image with a predefined threshold converts a grayscale or color <br/>            image into a binary image, where each pixel is classified as either black or white <br/>            based on whether its intensity value exceeds a specified threshold. |
| binarize_otsu() | Binarization of an image with Otsu thresholding is a method used to automatically <br/>            determine the optimal threshold value for converting a grayscale image into a <br/>            binary image. The Otsu thresholding algorithm calculates the threshold that <br/>            minimizes the intra-class variance of the pixel intensities in the two resulting <br/>            classes (foreground and background). This technique is particularly useful when <br/>            the optimal threshold value is unknown and needs to be determined adaptively based <br/>            on the image's histogram. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_10) | Blends this image instance with the _overlay_ image. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_11) | Blends this image instance with the _overlay_ image. |
| cache_data() | Caches the data private. |
| [can_load(file_path)](#can_load_file_path_12) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_13) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_14) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_15) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_16) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_17) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_18) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_save(options)](#can_save_options_19) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| clear_blocks() | Clearing all the GIF blocks removes any existing data stored within the image. <br/>            This operation effectively resets the image to an empty state, removing any <br/>            previously added blocks. Use this method when you need to start fresh with a clean <br/>            slate for creating or modifying a GIF image. |
| [create(files)](#create_files_20) | Creates the multipage image containing the specified files. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_21) | Creates the multipage image containing the specified files. |
| [create(image_options, width, height)](#create_image_options_width_height_22) | Creates a new image using the specified create options. |
| [create(images)](#create_images_23) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Creates a new image the specified images as pages. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Creates the specified multipage create options. |
| [create_from_files(files)](#create_from_files_files_26) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_images(images)](#create_from_images_images_28) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | Creates a new image the specified images as pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | Crop image with shifts. |
| [crop(rectangle)](#crop_rectangle_31) | Crop the image using a specified rectangle area. This operation removes the outer <br/>            portion of the image, leaving only the selected region defined by the rectangle. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | Apply dithering to the current image. This process enhances image quality by <br/>            reducing color banding and improving color transitions, resulting in a smoother <br/>            appearance. |
| [filter(rectangle, options)](#filter_rectangle_options_34) | Apply a specific filter to the designated area of the image, enhancing its visual <br/>            quality or altering its appearance as desired. This method selectively processes <br/>            pixels within the defined rectangle, allowing for targeted adjustments to be made <br/>            while preserving the integrity of the surrounding image data. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_35) | Gets an image 32-bit ARGB pixel. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_36) | Gets the default 32-bit ARGB pixels array. |
| [get_default_options(args)](#get_default_options_args_37) | Gets the default options. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_38) | Gets the default pixels array using partial pixel loader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_39) | Gets the default raw data array using partial pixel loader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_40) | Gets the default raw data array. |
| [get_file_format(file_path)](#get_file_format_file_path_41) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_42) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_43) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_44) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_45) | Gets rectangle which fits the current image. |
| [get_modify_date(use_default)](#get_modify_date_use_default_46) | Gets the date and time the resource image was last modified. |
| [get_original_options()](#get_original_options__47) | Retrieve the original file settings-based options, crucial for maintaining fidelity <br/>            and consistency in image processing and manipulation. This method allows seamless <br/>            integration of file-specific parameters into subsequent operations, ensuring <br/>            accurate rendition and adherence to the image's inherent characteristics.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_48) | Gets an image pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_49) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_50) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_51) | Converts to aps. |
| [get_skew_angle()](#get_skew_angle__52) | Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| grayscale() | The transformation of an image to its grayscale representation converts the color <br/>            image into a grayscale version by removing color information while preserving <br/>            luminance. This process simplifies the image to shades of gray, making it suitable <br/>            for various applications such as printing, document processing, and grayscale <br/>            analysis. |
| [insert_block(index, block)](#insert_block_index_block_53) | Inserting a new GIF block allows you to add custom data at a specific position <br/>            within the image. This method enables you to place custom blocks at a desired <br/>            location in the GIF image, providing flexibility in organizing and structuring the <br/>            image data. |
| [load(file_path)](#load_file_path_54) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_55) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_56) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_57) | Loads a new image from the specified stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_58) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_59) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_60) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_61) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_62) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_63) | Loads 64-bit ARGB pixels partially by packs. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Loads raw data. |
| [load_stream(stream)](#load_stream_stream_68) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_69) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_70) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_71) | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods. |
| order_blocks() | Ordering the GIF blocks according to the GIF specification ensures proper GIF <br/>            layout and compliance with the standard. This process involves arranging the <br/>            blocks in the correct sequence as defined by the specification. Additionally, it <br/>            may involve removing certain [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) instances that <br/>            are not necessary for the final layout. By adhering to the GIF specification, the <br/>            resulting image will be correctly structured and compatible with GIF viewing <br/>            applications. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_72) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_73) | Reads the whole scan line by the specified scan line index. |
| [remove_block(block)](#remove_block_block_74) | Removing a GIF block removes specific data from the image, offering the ability to <br/>            clean up or modify the image structure. This method enables you to remove unwanted <br/>            or unnecessary blocks, optimizing the GIF image for efficient storage. Use this <br/>            functionality to eliminate outdated information from the image while preserving <br/>            its integrity and quality. |
| remove_metadata() | Removes this image instance metadata by setting this [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) value to **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_75) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_76) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_77) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_78) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_79) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [resize(new_width, new_height)](#resize_new_width_new_height_80) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_81) | Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_82) | Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_83) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_84) | Resizes the image. |
| [resize_full_frame(new_width, new_height, resize_type)](#resize_full_frame_new_width_new_height_resize_type_85) | Resizing of the image while taking into account the full frames for each page in a <br/>            GIF, thus preventing potential artifacts from appearing. This method is essential <br/>            to maintain the integrity and quality of the image, especially when dealing with <br/>            animated GIFs or sequences of frames. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_86) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_87) | Resizes the width proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_88) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_89) | Resizes the height proportionally. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_90) | Proportional resizing maintains the aspect ratio of the image while adjusting its <br/>            size, ensuring that the image does not appear stretched or distorted. This method <br/>            resizes the image proportionally, scaling both the width and height by the same factor.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_91) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_92) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_93) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_94) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_95) | Rotate image around the center. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_96) | This method rotates the image around its center point. By specifying the rotation <br/>            angle, you can rotate the image clockwise or counterclockwise to achieve the <br/>            desired orientation. This rotation helps adjust the image's presentation or <br/>            alignment without distorting its content. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_97) | Perform rotation, flipping, or both on the active frame exclusively. This operation <br/>            applies transformations solely to the currently active frame of the image, <br/>            preserving the integrity of other frames in the sequence. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_98) | Rotates the flip all. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_99) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_100) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_101) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_102) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_103) | Saves the object's data to the specified stream. |
| [save(stream, options_base)](#save_stream_options_base_104) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_105) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_106) | Saves the 32-bit ARGB pixels. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_107) | Saves the pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_108) | Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_109) | Saves the pixels internal main. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_110) | Saves the raw data. |
| [save_to_stream(stream)](#save_to_stream_stream_111) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_112) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_113) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_114) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_115) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_116) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_frame_time(time)](#set_frame_time_time_117) | Adjusts the duration of each frame in milliseconds, ensuring consistent timing <br/>            throughout the image sequence. This method uniformly sets the display time for <br/>            every frame, allowing for precise control over animation speed.<br/>            Changing this value will reset delay for all frames. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_118) | Sets the image palette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_119) | Sets an image pixel for the specified position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_120) | Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_121) | Writes the whole scan line to the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_122) | Writes the whole scan line to the specified scan line index. |


### Constructor: GifImage(first_frame) {#GifImage_first_frame_1}


```
 GifImage(first_frame) 
```

Crafting GIF images becomes effortless with the [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) <br/>            constructor. With just the firstFrame parameter, it enters in a world of dynamic <br/>            visual communication.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | The first frame to initialize gif image with. |


**See also:**

**[Example # 1](#example_93)**: This example shows how to create a GIF image and save it to a file.

**[Example # 2](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Constructor: GifImage(first_frame, global_palette) {#GifImage_first_frame_global_palette_2}


```
 GifImage(first_frame, global_palette) 
```

Initiate a new [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) object with specified parameters for the <br/>            first frame and global palette. Start managing GIF images swiftly, ensuring <br/>            accurate representation with customizable settings for optimal results.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | The first frame to initialize gif image with. |
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The global palette to use. Note if both _firstFrame_ and _globalPalette_ are null then default global palette is used. |


**See also:**

**[Example # 1](#example_94)**: This example shows how to create a GIF image with a custom palette and save i...


### Constructor: GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer) {#GifImage_first_frame_global_palette_is_palette_sorted_palette_color_resolution_palette_background_color_index_aspect_ratio_has_trailer_3}


```
 GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer) 
```

Get started effortlessly with the [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) constructor. With this <br/>            simple method, you can dive into creating animated GIFs with ease. Just supply the <br/>            firstFrame, globalPalette, paletteColorResolution, aspectRatio, and other <br/>            parameters, and you're ready to bring your visuals to life.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | The first frame to initialize gif image with. |
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The global palette to use. Note if both _firstFrame_ and _globalPalette_ are null then default global palette is used. |
| is_palette_sorted | bool | if set to <c>true</c> the palette is sorted. Note the parameter is used when _globalPalette_ is not null. |
| palette_color_resolution | byte | The palette color resolution. Note the parameter is used when _globalPalette_ is not null. |
| palette_background_color_index | byte | The palette background color index. |
| aspect_ratio | byte | The aspect ratio. |
| has_trailer | bool | if set to <c>true</c> the gif image has trailer otherwise no trailer written at the end of the stream. |

### Property: active_frame {#active_frame1}

Manage and manipulate frames with this property, enabling smooth navigation and <br/>            modification of the active frame within the GIF image.

**See also:**

**[Example # 1](#example_96)**: The following example shows how to remove all blocks from a GIF image.


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Adding a new GIF block allows you to include additional data within the image. <br/>            This method enables you to append custom blocks to the GIF image, which can <br/>            contain various types of information.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock) | The GIF block to add. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Incorporate a new page seamlessly into the existing image, enhancing its content <br/>            and expanding its scope. This method augment image collections with additional <br/>            content, fostering creativity and flexibility in image management and composition.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The page to add. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Adjusts the brightness of the image according to the specified<br/>            _brightness_ parameter. This method modifies the brightness of <br/>            the entire image uniformly, enhancing or reducing the overall luminance to achieve <br/>            the desired effect.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |


**See also:**

**[Example # 1](#example_102)**: The following example performs brightness correction of a GIF image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Adjusts the contrast of the image, enhancing or reducing the difference in <br/>            brightness between pixels. This method modifies the image's overall tonal range, <br/>            making darker areas darker and brighter areas brighter to improve visual clarity <br/>            and detail.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |


**See also:**

**[Example # 1](#example_103)**: The following example performs contrast correction of a GIF image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Enhance image quality by applying gamma correction. This method adjusts the color <br/>            gamma of the image to achieve optimal visual clarity. It modifies the gamma value <br/>            of each pixel, resulting in improved color rendition and overall image appearance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |


**See also:**

**[Example # 1](#example_100)**: The following example performs gamma-correction of a GIF image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gamma-correction of an image applies a nonlinear adjustment to the pixel values, <br/>            enhancing or reducing brightness based on the specified coefficients for the red, <br/>            green, and blue channels. This method helps to fine-tune the color balance and <br/>            luminance of the image, improving its overall appearance and visual quality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma_red | float | Gamma for red channel coefficient |
| gamma_green | float | Gamma for green channel coefficient |
| gamma_blue | float | Gamma for blue channel coefficient |


**See also:**

**[Example # 1](#example_101)**: The following example performs gamma-correction of a GIF image applying diffe...


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_7}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm with <br/>            integral image thresholding is a method for converting a grayscale image into a <br/>            binary image. This algorithm calculates a local threshold for each pixel based on <br/>            the average intensity of the surrounding pixels within a specified window. By <br/>            adaptively adjusting the threshold based on local pixel intensities, Bradley's <br/>            method is effective at handling variations in lighting and contrast across the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_8}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels<br/>                centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_9}


```
 binarize_fixed(threshold) 
```

Binarization of an image with a predefined threshold converts a grayscale or color <br/>            image into a binary image, where each pixel is classified as either black or white <br/>            based on whether its intensity value exceeds a specified threshold.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |


**See also:**

**[Example # 1](#example_97)**: The following example binarizes a GIF image with the predefined threshold. Bi...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_10}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_11}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_12}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_13}


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


### Method: can_load(stream)  [static] {#can_load_stream_14}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_15}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_16}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_17}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_18}


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


### Method: can_save(options) {#can_save_options_19}


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


### Method: create(files)  [static] {#create_files_20}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_21}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_22}


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


### Method: create(images)  [static] {#create_images_23}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


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

### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

Crop the image using a specified rectangle area. This operation removes the outer <br/>            portion of the image, leaving only the selected region defined by the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Apply dithering to the current image. This process enhances image quality by <br/>            reducing color banding and improving color transitions, resulting in a smoother <br/>            appearance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The custom palette for dithering. |

### Method: filter(rectangle, options) {#filter_rectangle_options_34}


```
 filter(rectangle, options) 
```

Apply a specific filter to the designated area of the image, enhancing its visual <br/>            quality or altering its appearance as desired. This method selectively processes <br/>            pixels within the defined rectangle, allowing for targeted adjustments to be made <br/>            while preserving the integrity of the surrounding image data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | The options. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_35}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_36}


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


### Method: get_default_options(args) {#get_default_options_args_37}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_38}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_39}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_40}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_41}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_42}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_43}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_44}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_45}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_46}


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


### Method: get_original_options() {#get_original_options__47}


```
 get_original_options() 
```

Retrieve the original file settings-based options, crucial for maintaining fidelity <br/>            and consistency in image processing and manipulation. This method allows seamless <br/>            integration of file-specific parameters into subsequent operations, ensuring <br/>            accurate rendition and adherence to the image's inherent characteristics.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options based on the original file settings. |


### Method: get_pixel(x, y) {#get_pixel_x_y_48}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_49}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_50}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_51}


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


### Method: get_skew_angle() {#get_skew_angle__52}


```
 get_skew_angle() 
```

Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning.

**Returns**

| Type | Description |
| :- | :- |
| float | The skew angle, in degrees. |


### Method: insert_block(index, block) {#insert_block_index_block_53}


```
 insert_block(index, block) 
```

Inserting a new GIF block allows you to add custom data at a specific position <br/>            within the image. This method enables you to place custom blocks at a desired <br/>            location in the GIF image, providing flexibility in organizing and structuring the <br/>            image data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based element, at which block will be inserted. |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock) | The GIF block to add. |

### Method: load(file_path)  [static] {#load_file_path_54}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_55}


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


### Method: load(stream)  [static] {#load_stream_56}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_57}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_58}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_59}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_60}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_61}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_62}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader) | The 64-bit ARGB pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_68}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_69}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_70}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_71}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_72}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_73}


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


### Method: remove_block(block) {#remove_block_block_74}


```
 remove_block(block) 
```

Removing a GIF block removes specific data from the image, offering the ability to <br/>            clean up or modify the image structure. This method enables you to remove unwanted <br/>            or unnecessary blocks, optimizing the GIF image for efficient storage. Use this <br/>            functionality to eliminate outdated information from the image while preserving <br/>            its integrity and quality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock) | The block to remove. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_75}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_76}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color) |  |
| old_color_diff | byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_77}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_78}


```
 replace_non_transparent_colors(new_color) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_79}


```
 replace_non_transparent_colors(new_color_argb) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_argb | int | New color ARGB value to replace non transparent colors with. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_80}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_81}


```
 resize(new_width, new_height, resize_type) 
```

Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_82}


```
 resize(new_width, new_height, settings) 
```

Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_83}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_84}


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

### Method: resize_full_frame(new_width, new_height, resize_type) {#resize_full_frame_new_width_new_height_resize_type_85}


```
 resize_full_frame(new_width, new_height, resize_type) 
```

Resizing of the image while taking into account the full frames for each page in a <br/>            GIF, thus preventing potential artifacts from appearing. This method is essential <br/>            to maintain the integrity and quality of the image, especially when dealing with <br/>            animated GIFs or sequences of frames.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_86}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_87}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_88}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_89}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_90}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Proportional resizing maintains the aspect ratio of the image while adjusting its <br/>            size, ensuring that the image does not appear stretched or distorted. This method <br/>            resizes the image proportionally, scaling both the width and height by the same factor.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_91}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_92}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_93}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_94}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_95}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_96}


```
 rotate(angle, resize_proportionally, background_color) 
```

This method rotates the image around its center point. By specifying the rotation <br/>            angle, you can rotate the image clockwise or counterclockwise to achieve the <br/>            desired orientation. This rotation helps adjust the image's presentation or <br/>            alignment without distorting its content.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed<br/>            according to rotated rectangle (corner points) projections in other<br/>            case that leaves dimensions untouched and only<br/>            __internal__ image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_97}


```
 rotate_flip(rotate_flip_type) 
```

Perform rotation, flipping, or both on the active frame exclusively. This operation <br/>            applies transformations solely to the currently active frame of the image, <br/>            preserving the integrity of other frames in the sequence.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip type. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_98}


```
 rotate_flip_all(rotate_flip) 
```

Rotates the flip all.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip. |

### Method: save(file_path) {#save_file_path_99}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_100}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_101}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_102}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_103}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save(stream, options_base) {#save_stream_options_base_104}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_105}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_106}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_107}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Saves the pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_108}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_109}


```
 save_pixels(rectangle, pixels) 
```

Saves the pixels internal main.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The pixels. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_110}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_111}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_112}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_113}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_114}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_115}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_116}


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

### Method: set_frame_time(time) {#set_frame_time_time_117}


```
 set_frame_time(time) 
```

Adjusts the duration of each frame in milliseconds, ensuring consistent timing <br/>            throughout the image sequence. This method uniformly sets the display time for <br/>            every frame, allowing for precise control over animation speed.<br/>            Changing this value will reset delay for all frames.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| time | ushort | The time of frame duration in milliseconds. |

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
### This example shows how to create a GIF image and save it to a file. {#example_93}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color


# Create a GIF Frame block of 100x100 px.
with GifFrameBlock(100, 100) as firstBlock:
	# Fill the entire block in red.
	gr = Graphics(firstBlock)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, firstBlock.bounds)

	with GifImage(firstBlock) as gifImage:
		gifImage.save("output.gif")


```

### This example shows how to create a GIF image with a custom palette and save it to a file. {#example_94}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color, ColorPaletteHelper


# Create a GIF Frame block of 100x100 px.
with GifFrameBlock(100, 100) as firstBlock:
	# Fill the entire block in red.
	gr = Graphics(firstBlock)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, firstBlock.bounds)

	# Use 4-bit palette to reduce the image size. The quality can get worse.
	palette = ColorPaletteHelper.create_4_bit()

	with GifImage(firstBlock, palette) as gifImage:
		gifImage.save("output.gif")


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Create a GIF image 100 x 100 px.
# The first block is fully black by default.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# The first circle is red
		brush1 = SolidBrush(Color.red)

		# The second circle is black
		brush2 = SolidBrush(Color.black)

		# Gradually increase the angle of the red arc shape.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Gradually increase the angle of the black arc and wipe out the red arc.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush2, block.bounds, 0, angle)
			gr.fill_pie(brush1, block.bounds, angle, 360 - angle)
			gifImage.add_block(block)

		gifImage.save("animated_radar.gif")


```

### The following example shows how to remove all blocks from a GIF image. {#example_96}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 

# Create a GIF image 100 x 100 px.
# The first block is fully black by default.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		if gifImage.active_frame is not None:
			print(f"Active frame size: {gifImage.active_frame.size}")
		else:
			print("Active frame is not set")

		print("Clear all the blocks")
		gifImage.clear_blocks()

		if gifImage.active_frame is not None:
			print(f"Active frame size: {gifImage.active_frame.size}")
		else:
			print("Active frame is not set")

# The output looks like this:
# Active frame size: { Width = 100, Height = 100}
# Clear all the blocks
# Active frame is not set

```

### The following example binarizes a GIF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_97}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	djvu_image = aspycore.as_of(image, GifImage)
	# Binarize the image with a threshold value of 127.
	# If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
	djvu_image.binarize_fixed(127)
	djvu_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example performs gamma-correction of a GIF image. {#example_100}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp\\"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Set gamma coefficient for red, green and blue channels.
	gif_image.adjust_gamma(2.5)
	gif_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a GIF image applying different coefficients for color components. {#example_101}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Set individual gamma coefficients for red, green and blue channels.
	gif_image.adjust_gamma(1.5, 2.5, 3.5)
	gif_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a GIF image. {#example_102}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Set the brightness value. The accepted values of brightness are in the range [-255, 255].
	gif_image.adjust_brightness(50)
	gif_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a GIF image. {#example_103}
``` python


import aspose.pycore as aspycore

from aspose.imaging import Image

from aspose.imaging.fileformats.gif import GifImage

from aspose.imaging.imageoptions import PngOptions

from os.path import join



dir_ = "c:\\temp"

with Image.load(join(dir_, "sample.gif")) as image:

	gif_image = aspycore.as_of(image, GifImage)

	# Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].

	gif_image.adjust_contrast(50.0)

	gif_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())



# ExEnd

```

### Export of part of animation from GIF image based on time interval. {#example_162}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import GifOptions, MultiPageOptions, MultiPageMode, TimeInterval

with Image.load("Animation.gif") as image:
	obj_init = MultiPageOptions()
	obj_init.mode = MultiPageMode.TIME_INTERVAL
	obj_init.time_interval = TimeInterval(0, 400)
	options = GifOptions()
	options.full_frame = True
	options.multi_page_options = obj_init
	image.save("PartOfAnimation.gif", options)


```

