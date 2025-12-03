---
title: GifImage Class
type: docs
weight: 70
url: /python-net/aspose.imaging.fileformats.gif/gifimage/
---

**Summary:** The API for Graphical Interchange Format (GIF) image file provides<br/>            developers with versatile tools for processing compressed raster images and<br/>            animated GIFs. Offering features like XMP metadata handling, color palette<br/>            settings, background and transparent color control, opacity settings, resize,<br/>            crop, filter application, gamma corrections, contrast adjustment, grayscale<br/>            transformation, and conversion to other formats. This API empowers seamless<br/>            manipulation and enhancement of GIF images for a wide range of applications.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

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
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Manage the background color of the GIF image with this property. You can set or <br/>            retrieve the background color to ensure consistency and enhance visual appeal. |
| background_color_index | System.Byte | r/w | Control the background color index of the GIF image using this property. Set or <br/>            retrieve the index to maintain consistency or achieve desired visual effects. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| blocks | [IGifBlock[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | r | Gain access to the GIF blocks seamlessly with this property, facilitating easy <br/>            retrieval and manipulation of the image's underlying data structures. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets Exif instance. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Retrieve the file format effortlessly with this property. It's your go-to source <br/>            for identifying the format of your files. Seamlessly integrated into your workflow, <br/>            it provides vital information without any hassle. |
| has_alpha | bool | r | Gets a value indicating whether this instance has alpha. |
| has_background_color | bool | r/w | This property determines whether the GIF image contains a background color. If <br/>            true, it indicates that the image includes a background color. |
| has_trailer | bool | r/w | Manage the presence of a trailer in your GIF files with this property. Whether you <br/>            need to check if a trailer exists or set its presence, this property simplifies the <br/>            process. Keep your GIF files structured and compliant with this intuitive feature. |
| has_transparent_color | bool | r/w | Determine whether the active frame of the GIF image includes a transparent color. <br/>            This property provides a convenient way to check for transparency within the image. |
| height | int | r | Gets the image height. |
| horizontal_resolution | float | r/w | Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Retrieve the opacity of the active frame within the image, offering insight into <br/>            its transparency level. This property is particularly useful for understanding the <br/>            degree of transparency or opaqueness of the active frame in the image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_interlaced | bool | r | Determines if the image is interlaced, impacting its display during loading. This <br/>            property offers insight into the image's rendering behavior, essential for <br/>            optimizing loading strategies and enhancing overall viewing experience. |
| is_palette_sorted | bool | r/w | Control the sorting of the palette in your GIF images using this property. Whether <br/>            you need to check if the palette is sorted or set the sorting behavior, this <br/>            property provides a straightforward way to manage the palette organization in your <br/>            GIF files. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| loops_count | int | r/w | Retrieve the loop count effortlessly with this property. If your GIF image includes <br/>            loop information, this property gives you quick access to the loop count, enabling <br/>            you to seamlessly manage looping behavior in your GIF files. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Gets or sets XMP data from frame. |
| page_count | int | r | Retrieve the total number of pages contained within the image with this <br/>            straightforward property. Ideal for quickly assessing the extent of the image content. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Gain access to the pages within the image through this convenient property, <br/>            allowing seamless navigation and manipulation of individual pages as needed. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| palette_color_resolution_bits | System.Byte | r/w | Manage the palette color resolution of your GIF images with this property. Adjust <br/>            the number of bits used to represent colors in the palette, providing fine control <br/>            over color depth and image quality. |
| pixel_aspect_ratio | System.Byte | r/w | Manage the pixel aspect ratio of the GIF image with this property. Set or retrieve <br/>            the aspect ratio to ensure accurate rendering and maintain visual fidelity. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Gets or sets the custom color converter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Gets the raw data format. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Gets or sets the indexed color converter |
| raw_line_size | int | r | Gets the raw line size in bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Gets the object size. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Retrieve the transparent color of the active frame in the GIF image. This property <br/>            allows you to access the specific color that has been designated as transparent <br/>            within the currently active frame. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| vertical_resolution | float | r/w | Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Gets the image width. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Adding a new GIF block allows you to include additional data within the image. <br/>            This method enables you to append custom blocks to the GIF image, which can <br/>            contain various types of information. |
| [add_page(page)](#add_page_page_2) | Incorporate a new page seamlessly into the existing image, enhancing its content <br/>            and expanding its scope. This method augment image collections with additional <br/>            content, fostering creativity and flexibility in image management and composition. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Adjusts the brightness of the image according to the specified<br/>            _brightness_ parameter. This method modifies the brightness of <br/>            the entire image uniformly, enhancing or reducing the overall luminance to achieve <br/>            the desired effect. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Adjusts the contrast of the image, enhancing or reducing the difference in <br/>            brightness between pixels. This method modifies the image's overall tonal range, <br/>            making darker areas darker and brighter areas brighter to improve visual clarity <br/>            and detail. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Enhance image quality by applying gamma correction. This method adjusts the color <br/>            gamma of the image to achieve optimal visual clarity. It modifies the gamma value <br/>            of each pixel, resulting in improved color rendition and overall image appearance. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Gamma-correction of an image applies a nonlinear adjustment to the pixel values, <br/>            enhancing or reducing brightness based on the specified coefficients for the red, <br/>            green, and blue channels. This method helps to fine-tune the color balance and <br/>            luminance of the image, improving its overall appearance and visual quality. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Calculates the percentage similarity between the extracted data and the original password. |
| auto_brightness_contrast() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| auto_rotate() | Automatically rotates the image based on orientation data extracted from Exif <br/>            metadata. This method ensures that images are displayed in the correct orientation, <br/>            enhancing user experience and eliminating the need for manual adjustments. By <br/>            analyzing Exif information, the image is rotated accordingly, providing a seamless <br/>            viewing experience across different platforms and devices. This automated rotation <br/>            process simplifies image handling and improves overall usability, especially when <br/>            dealing with large batches of images with varying orientations. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarization of an image using Bradley's adaptive thresholding algorithm with <br/>            integral image thresholding is a method for converting a grayscale image into a <br/>            binary image. This algorithm calculates a local threshold for each pixel based on <br/>            the average intensity of the surrounding pixels within a specified window. By <br/>            adaptively adjusting the threshold based on local pixel intensities, Bradley's <br/>            method is effective at handling variations in lighting and contrast across the image. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Binarization of an image with a predefined threshold converts a grayscale or color <br/>            image into a binary image, where each pixel is classified as either black or white <br/>            based on whether its intensity value exceeds a specified threshold. |
| binarize_otsu() | Binarization of an image with Otsu thresholding is a method used to automatically <br/>            determine the optimal threshold value for converting a grayscale image into a <br/>            binary image. The Otsu thresholding algorithm calculates the threshold that <br/>            minimizes the intra-class variance of the pixel intensities in the two resulting <br/>            classes (foreground and background). This technique is particularly useful when <br/>            the optimal threshold value is unknown and needs to be determined adaptively based <br/>            on the image's histogram. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Blends this image instance with the _overlay_ image. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Blends this image instance with the _overlay_ image. |
| cache_data() | Caches the data private. |
| [can_load(file_path)](#can_load_file_path_13) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_15) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_save(options)](#can_save_options_20) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| clear_blocks() | Clearing all the GIF blocks removes any existing data stored within the image. <br/>            This operation effectively resets the image to an empty state, removing any <br/>            previously added blocks. Use this method when you need to start fresh with a clean <br/>            slate for creating or modifying a GIF image. |
| [create(files)](#create_files_21) | Creates the multipage image containing the specified files. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Creates the multipage image containing the specified files. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Creates a new image using the specified create options. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Creates a [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) instance from the provided pixel array.<br/>            <br/>            Validates that the specified width and height match the dimensions of the pixel data.<br/>            This method can only be used when the library is in Licensed mode. |
| [create(images)](#create_images_25) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Creates a new image the specified images as pages. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Creates the specified multipage create options. |
| [create_from_files(files)](#create_from_files_files_28) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_images(images)](#create_from_images_images_30) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | Creates a new image the specified images as pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Crop image with shifts. |
| [crop(rectangle)](#crop_rectangle_33) | Crop the image using a specified rectangle area. This operation removes the outer <br/>            portion of the image, leaving only the selected region defined by the rectangle. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Apply dithering to the current image. This process enhances image quality by <br/>            reducing color banding and improving color transitions, resulting in a smoother <br/>            appearance. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Embed digital sign based on provided password into each page of the image. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Apply a specific filter to the designated area of the image, enhancing its visual <br/>            quality or altering its appearance as desired. This method selectively processes <br/>            pixels within the defined rectangle, allowing for targeted adjustments to be made <br/>            while preserving the integrity of the surrounding image data. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Gets an image 32-bit ARGB pixel. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Gets the default 32-bit ARGB pixels array. |
| [get_default_options(args)](#get_default_options_args_40) | Gets the default options. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Gets the default pixels array using partial pixel loader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Gets the default raw data array using partial pixel loader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Gets the default raw data array. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_45) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Gets rectangle which fits the current image. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Gets the date and time the resource image was last modified. |
| [get_original_options()](#get_original_options__50) | Retrieve the original file settings-based options, crucial for maintaining fidelity <br/>            and consistency in image processing and manipulation. This method allows seamless <br/>            integration of file-specific parameters into subsequent operations, ensuring <br/>            accurate rendition and adherence to the image's inherent characteristics.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Gets an image pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Converts to aps. |
| [get_skew_angle()](#get_skew_angle__55) | Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| grayscale() | The transformation of an image to its grayscale representation converts the color <br/>            image into a grayscale version by removing color information while preserving <br/>            luminance. This process simplifies the image to shades of gray, making it suitable <br/>            for various applications such as printing, document processing, and grayscale <br/>            analysis. |
| [insert_block(index, block)](#insert_block_index_block_56) | Inserting a new GIF block allows you to add custom data at a specific position <br/>            within the image. This method enables you to place custom blocks at a desired <br/>            location in the GIF image, providing flexibility in organizing and structuring the <br/>            image data. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | Performs a fast check to determine if the image is digitally signed, using the provided password and threshold. |
| [load(file_path)](#load_file_path_58) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_59) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_60) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_61) | Loads a new image from the specified stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | Loads 64-bit ARGB pixels partially by packs. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | Loads raw data. |
| [load_stream(stream)](#load_stream_stream_72) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods. |
| normalize_histogram() | Normalizes the image histogram — adjust pixel values to use all available range. |
| order_blocks() | Ordering the GIF blocks according to the GIF specification ensures proper GIF <br/>            layout and compliance with the standard. This process involves arranging the <br/>            blocks in the correct sequence as defined by the specification. Additionally, it <br/>            may involve removing certain [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) instances that <br/>            are not necessary for the final layout. By adhering to the GIF specification, the <br/>            resulting image will be correctly structured and compatible with GIF viewing <br/>            applications. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Reads the whole scan line by the specified scan line index. |
| [remove_block(block)](#remove_block_block_78) | Removing a GIF block removes specific data from the image, offering the ability to <br/>            clean up or modify the image structure. This method enables you to remove unwanted <br/>            or unnecessary blocks, optimizing the GIF image for efficient storage. Use this <br/>            functionality to eliminate outdated information from the image while preserving <br/>            its integrity and quality. |
| remove_metadata() | Removes this image instance metadata by setting this [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) value to **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Resizes the image. |
| [resize_full_frame(new_width, new_height, resize_type)](#resize_full_frame_new_width_new_height_resize_type_89) | Resizing of the image while taking into account the full frames for each page in a <br/>            GIF, thus preventing potential artifacts from appearing. This method is essential <br/>            to maintain the integrity and quality of the image, especially when dealing with <br/>            animated GIFs or sequences of frames. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | Resizes the width proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | Resizes the height proportionally. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_94) | Proportional resizing maintains the aspect ratio of the image while adjusting its <br/>            size, ensuring that the image does not appear stretched or distorted. This method <br/>            resizes the image proportionally, scaling both the width and height by the same factor.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_95) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_96) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_97) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_98) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_99) | Rotate image around the center. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_100) | This method rotates the image around its center point. By specifying the rotation <br/>            angle, you can rotate the image clockwise or counterclockwise to achieve the <br/>            desired orientation. This rotation helps adjust the image's presentation or <br/>            alignment without distorting its content. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_101) | Perform rotation, flipping, or both on the active frame exclusively. This operation <br/>            applies transformations solely to the currently active frame of the image, <br/>            preserving the integrity of other frames in the sequence. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_102) | Rotates the flip all. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_103) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_104) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_105) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_106) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_107) | Saves the object's data to the specified stream. |
| [save(stream, options_base)](#save_stream_options_base_108) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_109) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Saves the 32-bit ARGB pixels. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Saves the pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Saves the pixels internal main. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Saves the raw data. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_frame_time(time)](#set_frame_time_time_121) | Adjusts the duration of each frame in milliseconds, ensuring consistent timing <br/>            throughout the image sequence. This method uniformly sets the display time for <br/>            every frame, allowing for precise control over animation speed.<br/>            Changing this value will reset delay for all frames. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_122) | Sets the image palette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_123) | Sets an image pixel for the specified position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_124) | Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_125) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) instance. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126) | Writes the whole scan line to the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_127) | Writes the whole scan line to the specified scan line index. |


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
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The global palette to use. Note if both _firstFrame_ and _globalPalette_ are null then default global palette is used. |


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
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The global palette to use. Note if both _firstFrame_ and _globalPalette_ are null then default global palette is used. |
| is_palette_sorted | bool | if set to <c>true</c> the palette is sorted. Note the parameter is used when _globalPalette_ is not null. |
| palette_color_resolution | System.Byte | The palette color resolution. Note the parameter is used when _globalPalette_ is not null. |
| palette_background_color_index | System.Byte | The palette background color index. |
| aspect_ratio | System.Byte | The aspect ratio. |
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
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | The GIF block to add. |


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
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The page to add. |


**See also:**

**[Example # 1](#example_214)**: Create multipage GIF image using single page raster images.


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

**[Example # 1](#example_104)**: The following example performs brightness correction of a GIF image.


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

**[Example # 1](#example_105)**: The following example performs contrast correction of a GIF image.


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

**[Example # 1](#example_102)**: The following example performs gamma-correction of a GIF image.


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

**[Example # 1](#example_103)**: The following example performs gamma-correction of a GIF image applying diffe...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


```
 analyze_percentage_digital_signature(password) 
```

Calculates the percentage similarity between the extracted data and the original password.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| password | string | The password used to extract the embedded data. |

**Returns**

| Type | Description |
| :- | :- |
| int | The percentage similarity value. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm with <br/>            integral image thresholding is a method for converting a grayscale image into a <br/>            binary image. This algorithm calculates a local threshold for each pixel based on <br/>            the average intensity of the surrounding pixels within a specified window. By <br/>            adaptively adjusting the threshold based on local pixel intensities, Bradley's <br/>            method is effective at handling variations in lighting and contrast across the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | float | The brightness difference between pixel and the average of an s x s window of pixels centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | float | The brightness difference between pixel and the average of an s x s window of pixels<br/>                centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Binarization of an image with a predefined threshold converts a grayscale or color <br/>            image into a binary image, where each pixel is classified as either black or white <br/>            based on whether its intensity value exceeds a specified threshold.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | System.Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of 255 will be assigned to it, 0 otherwise. |


**See also:**

**[Example # 1](#example_99)**: The following example binarizes a GIF image with the predefined threshold. Bi...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


```
 blend(origin, overlay, overlay_alpha) 
```

Blends this image instance with the _overlay_ image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | The background image blending origin. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The overlay image. |
| overlay_alpha | System.Byte | The overlay alpha. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Blends this image instance with the _overlay_ image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | The background image blending origin. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The overlay image. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The overlay area. |
| overlay_alpha | System.Byte | The overlay alpha. |

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


```
 can_load(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


```
 can_load(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


```
 can_load_stream_with_options(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


```
 can_load_with_options(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### Method: can_save(options) {#can_save_options_20}


```
 can_save(options) 
```

Determines whether image can be saved to the specified file format represented by the passed save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options to use. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be saved to the specified file format represented by the passed save options; otherwise, <c>false</c>. |


### Method: create(files)  [static] {#create_files_21}


```
 create(files) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


```
 create(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> [throw exception on load error]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


```
 create(image_options, width, height) 
```

Creates a new image using the specified create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |
| width | int | The width. |
| height | int | The height. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The newly created image. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


```
 create(image_options, width, height, pixels) 
```

Creates a [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) instance from the provided pixel array.<br/>            <br/>            Validates that the specified width and height match the dimensions of the pixel data.<br/>            This method can only be used when the library is in Licensed mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options used to create the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | The width of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | The height of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| pixels | int[] | The array of pixel values used to populate the image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | A [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) populated with the provided pixel data. |


### Method: create(images)  [static] {#create_images_25}


```
 create(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


```
 create(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


```
 create_from_files(files) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> throw exception on load error. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


```
 create_from_images(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


```
 create_from_images(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


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

### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Crop the image using a specified rectangle area. This operation removes the outer <br/>            portion of the image, leaving only the selected region defined by the rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |


**See also:**

**[Example # 1](#example_98)**: The following example crops a GIF image. The cropping area is be specified vi...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Apply dithering to the current image. This process enhances image quality by <br/>            reducing color banding and improving color transitions, resulting in a smoother <br/>            appearance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | The dithering method. |
| bits_count | int | The final bits count for dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The custom palette for dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Embed digital sign based on provided password into each page of the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| password | string | The password used for generate digital sign data |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Apply a specific filter to the designated area of the image, enhancing its visual <br/>            quality or altering its appearance as desired. This method selectively processes <br/>            pixels within the defined rectangle, allowing for targeted adjustments to be made <br/>            while preserving the integrity of the surrounding image data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | The options. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


```
 get_default_argb_32_pixels(rectangle) 
```

Gets the default 32-bit ARGB pixels array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get pixels for. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The default pixels array. |


### Method: get_default_options(args) {#get_default_options_args_40}


```
 get_default_options(args) 
```

Gets the default options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | System.Object | The arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Default options |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | The partial pixel loader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Gets the default raw data array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get pixels for. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | The partial raw data loader. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | The raw data settings. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Gets the default raw data array.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get raw data for. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | The raw data settings. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | The default raw data array. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get fitting rectangle for. |
| pixels | int[] | The 32-bit ARGB pixels. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get fitting rectangle for. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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
| System.DateTime | The date and time the resource image was last modified. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Retrieve the original file settings-based options, crucial for maintaining fidelity <br/>            and consistency in image processing and manipulation. This method allows seamless <br/>            integration of file-specific parameters into subsequent operations, ensuring <br/>            accurate rendition and adherence to the image's inherent characteristics.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options based on the original file settings. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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
| [Color](/imaging/python-net/aspose.imaging/color/) | The pixel color for the specified location. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Converts to aps.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The clipping rectangle. |
| page_number | int[] | The page number. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The serialized stream |


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning.

**Returns**

| Type | Description |
| :- | :- |
| float | The skew angle, in degrees. |


### Method: insert_block(index, block) {#insert_block_index_block_56}


```
 insert_block(index, block) 
```

Inserting a new GIF block allows you to add custom data at a specific position <br/>            within the image. This method enables you to place custom blocks at a desired <br/>            location in the GIF image, providing flexibility in organizing and structuring the <br/>            image data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based element, at which block will be inserted. |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | The GIF block to add. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


```
 is_digital_signed(password, percentage_threshold) 
```

Performs a fast check to determine if the image is digitally signed, using the provided password and threshold.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| password | string | The password to check the signing. |
| percentage_threshold | int | The threshold (in percentage)[0-100] that determines if the image is considered signed.<br/>            If not specified, a default threshold (<c>75</c>) will be applied. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True if the image is signed, otherwise false. |


### Method: load(file_path)  [static] {#load_file_path_58}


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
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load(stream)  [static] {#load_stream_60}


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
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


```
 load(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


```
 load_argb_32_pixels(rectangle) 
```

Loads 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The loaded 32-bit ARGB pixels array. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


```
 load_argb_64_pixels(rectangle) 
```

Loads 64-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The loaded 64-bit ARGB pixels array. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


```
 load_cmyk_32_pixels(rectangle) 
```

Loads pixels in CMYK format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The loaded CMYK pixels presentes as 32-bit inateger values. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


```
 load_cmyk_pixels(rectangle) 
```

Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The loaded CMYK pixels array. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | The partial pixel loader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | The 64-bit ARGB pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


```
 load_pixels(rectangle) 
```

Loads pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The loaded pixels array. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load raw data from. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The dest image bounds. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | The raw data loader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Loads raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load raw data from. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | The raw data settings to use for loaded data. Note if data is not in the format specified then data conversion will be performed. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | The raw data loader. |

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


```
 load_stream_with_options(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


```
 load_with_options(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color of the background. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


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
| int[] | The scan line 32-bit ARGB color values array. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


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
| [Color[]](/imaging/python-net/aspose.imaging/color/) | The scan line pixel color values array. |


### Method: remove_block(block) {#remove_block_block_78}


```
 remove_block(block) 
```

Removing a GIF block removes specific data from the image, offering the ability to <br/>            clean up or modify the image structure. This method enables you to remove unwanted <br/>            or unnecessary blocks, optimizing the GIF image for efficient storage. Use this <br/>            functionality to eliminate outdated information from the image while preserving <br/>            its integrity and quality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | The block to remove. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color_argb | int | Old color ARGB value to be replaced. |
| old_color_diff | System.Byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color_argb | int | New color ARGB value to replace old color with. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| old_color_argb | int | Old color ARGB value to be replaced. |
| old_color_diff | System.Byte | Allowed difference in old color to be able to widen replaced color tone. |
| new_color_argb | int | New color ARGB value to replace old color with. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

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

Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

Resizes this [Image](/imaging/python-net/aspose.imaging/image/) instance.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The settings. |

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
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

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
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_full_frame(new_width, new_height, resize_type) {#resize_full_frame_new_width_new_height_resize_type_89}


```
 resize_full_frame(new_width, new_height, resize_type) 
```

Resizing of the image while taking into account the full frames for each page in a <br/>            GIF, thus preventing potential artifacts from appearing. This method is essential <br/>            to maintain the integrity and quality of the image, especially when dealing with <br/>            animated GIFs or sequences of frames.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_90}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_91}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_92}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_93}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_94}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Proportional resizing maintains the aspect ratio of the image while adjusting its <br/>            size, ensuring that the image does not appear stretched or distorted. This method <br/>            resizes the image proportionally, scaling both the width and height by the same factor.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_95}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_96}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_97}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_98}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_99}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_100}


```
 rotate(angle, resize_proportionally, background_color) 
```

This method rotates the image around its center point. By specifying the rotation <br/>            angle, you can rotate the image clockwise or counterclockwise to achieve the <br/>            desired orientation. This rotation helps adjust the image's presentation or <br/>            alignment without distorting its content.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed<br/>            according to rotated rectangle (corner points) projections in other<br/>            case that leaves dimensions untouched and only<br/>            __internal__ image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color of the background. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_101}


```
 rotate_flip(rotate_flip_type) 
```

Perform rotation, flipping, or both on the active frame exclusively. This operation <br/>            applies transformations solely to the currently active frame of the image, <br/>            preserving the integrity of other frames in the sequence.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip type. |


**See also:**

**[Example # 1](#example_97)**: This example loads a GIF image, rotates it by 90 degrees clockwise and option...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_102}


```
 rotate_flip_all(rotate_flip) 
```

Rotates the flip all.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip. |

### Method: save(file_path) {#save_file_path_103}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_104}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_105}


```
 save(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: save(file_path, over_write) {#save_file_path_over_write_106}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_107}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save(stream, options_base) {#save_stream_options_base_108}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_109}


```
 save(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | int[] | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Saves the pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | int[] | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Saves the pixels internal main.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The pixels. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Saves the raw data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| data | System.Byte | The raw data. |
| data_offset | int | The starting raw data offset. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The raw data rectangle. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | The raw data settings the data is in. |

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_frame_time(time) {#set_frame_time_time_121}


```
 set_frame_time(time) 
```

Adjusts the duration of each frame in milliseconds, ensuring consistent timing <br/>            throughout the image sequence. This method uniformly sets the display time for <br/>            every frame, allowing for precise control over animation speed.<br/>            Changing this value will reset delay for all frames.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| time | int | The time of frame duration in milliseconds. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_122}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_123}


```
 set_pixel(x, y, color) 
```

Sets an image pixel for the specified position.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The pixel x location. |
| y | int | The pixel y location. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | The pixel color for the specified position. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_124}


```
 set_resolution(dpi_x, dpi_y) 
```

Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dpi_x | float | The horizontal resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | The vertical resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_125}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| argb_32_pixels | int[] | The 32-bit ARGB colors array to write. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_127}


```
 write_scan_line(scan_line_index, pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The pixel colors array to write. |

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

### This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_97}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Rotate, flip and save to the output file.
	with aspycore.as_of(Image.load(join(dir_, "sample.gif")), GifImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example crops a GIF image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_98}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.gif import GifImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Crop the image. The cropping area is the rectangular central area of the image.
	area = Rectangle(gif_image.width // 4, gif_image.height // 4, gif_image.width // 2,
					 gif_image.height // 2)
	gif_image.crop(area)
	# Save the cropped image to PNG
	gif_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a GIF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_99}
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

### The following example performs gamma-correction of a GIF image. {#example_102}
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

### The following example performs gamma-correction of a GIF image applying different coefficients for color components. {#example_103}
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

### The following example performs brightness correction of a GIF image. {#example_104}
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

### The following example performs contrast correction of a GIF image. {#example_105}
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

### Create multipage GIF image using single page raster images. {#example_214}
``` python
from aspose.imaging import Image, RasterImage
from aspose.pycore import as_of
from os import listdir
from os.path import isfile, join

def load_frames(directory):
	for f in listdir(directory):
		full_path = join(directory, f)
		if isfile(full_path):
			yield as_of(Image.load(file_path), RasterImage)


# Load frames
frames = list(load_frames("Animation frames"))
# Create GIF image using the first frame
with GifImage(GifFrameBlock(frames[0])) as image:
	# Add frames to the GIF image using the AddPage method
	for index in range(1, len(frames)):
		image.add_page(frames[index])

	# Save GIF image
	image.save("Multipage.gif")
	
for it in frames:
	with it as _:
		# dispose the images
		pass


```

### Export of part of animation from GIF image based on time interval. {#example_220}
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

