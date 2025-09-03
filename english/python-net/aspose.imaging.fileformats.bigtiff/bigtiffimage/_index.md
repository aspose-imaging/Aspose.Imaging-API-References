---
title: BigTiffImage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/
---

**Summary:** With the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class you can effortlessly manipulate<br/>            BigTiff image format files. Our API offering seamless handling and customization<br/>            options, ensuring optimal processing of large-scale image data with versatile features<br/>            tailored to your specific requirements.

**Module:** [aspose.imaging.fileformats.bigtiff](/imaging/python-net/aspose.imaging.fileformats.bigtiff/)

**Full Name:** aspose.imaging.fileformats.bigtiff.BigTiffImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IHasXmpData, IHasMetadata, IMultipageImage, IMultipageImageExt, IHasExifData, TiffImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffImage(frame)](#BigTiffImage_frame_1) | Create a new instance of the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class by initializing<br/>            it with a TiffFrame parameter. Ideal for developers seeking a convenient<br/>            way to work with BigTiffImage objects, ensuring flexibility and ease of integration<br/>            into their projects. |
| [BigTiffImage(frames)](#BigTiffImage_frames_2) | Begin utilizing the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class seamlessly by<br/>            initializing a new instance with a list of TiffFrames parameter.<br/>            Perfect for developers seeking a straightforward method to work with<br/>            BigTiffImage objects containing multiple frames, ensuring efficiency of their projects. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r/w | Manage the active frame seamlessly, facilitating dynamic navigation and <br/>            manipulation within the designated context. Empower your application to interact <br/>            efficiently with multimedia content, enhancing user engagement and productivity. |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Toggle the byte order for TIFF files seamlessly, ensuring precise control over <br/>            data interpretation. Empower your applications with the flexibility to adapt to <br/>            diverse file specifications, enhancing compatibility and efficiency in data processing. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Access or modify EXIF data associated with the active frame seamlessly, empowering <br/>            precise control over image metadata. Enhance your application's capabilities by <br/>            integrating this feature, ensuring accurate preservation and customization of <br/>            essential image information. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Retrieve the file format value associated with the image. This property serves as <br/>            a critical aspect of image metadata retrieval, allowing software applications to <br/>            identify and interpret the format of the image data efficiently. |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r | Retrieve an array of [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) instances, enabling comprehensive <br/>            access and manipulation of individual frames within the TIFF image. Harness the <br/>            power of this array to streamline image processing workflows, ensuring precise <br/>            control and optimization of visual content. |
| has_alpha | bool | r | Determine whether the image has an alpha channel, providing crucial information <br/>            for rendering and compositing operations. Integrate this feature to optimize <br/>            visual processing workflows, ensuring accurate representation and manipulation of <br/>            transparent elements. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| has_transparent_color | bool | r/w | Gets a value indicating whether image has transparent color. |
| height | int | r | Gets the object height. |
| horizontal_resolution | float | r/w | Retrieve the horizontal resolution of the specified [Image](/imaging/python-net/aspose.imaging/image/) in pixels <br/>            per inch, facilitating precise adjustment and rendering capabilities. Access <br/>            essential image metadata effortlessly, empowering streamlined image processing <br/>            workflows for enhanced user experiences. |
| image_opacity | float | r | Gets opacity of this image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| page_count | int | r | Retrieve the total count of pages within the specified document, facilitating <br/>            efficient navigation and management of multi-page content. Incorporate this <br/>            functionality to enhance user experience, enabling seamless access to <br/>            comprehensive document structures. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Access the pages of the document seamlessly, enabling dynamic navigation and <br/>            manipulation within the content structure. Empower your application with efficient <br/>            access to individual pages, facilitating streamlined document processing and <br/>            enhanced user interaction. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| premultiply_components | bool | r/w | Indicate if components necessitate premultiplication, ensuring efficient handling <br/>            of visual elements. Enhance rendering processes by toggling this property, <br/>            streamlining graphic workflows for optimized performance. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Gets or sets the custom color converter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Gets the raw data format. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Gets or sets the indexed color converter |
| raw_line_size | int | r | Gets the raw line size in bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Gets the object size. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets the image transparent color. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| vertical_resolution | float | r/w | Access the vertical resolution of the designated [Image](/imaging/python-net/aspose.imaging/image/) in pixels per <br/>            inch, enabling precise adjustments and rendering optimizations. Utilize essential <br/>            image data effortlessly to streamline image processing workflows, ensuring <br/>            superior quality and performance in your applications. |
| width | int | r | Gets the object width. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(image)](#add_image_1) | Add the frames from the specified image seamlessly into the current frame, <br/>            consolidating their content and enhancing compositional flexibility. Integrate <br/>            this method to streamline frame management and manipulation within your <br/>            application, facilitating efficient handling of multi-frame images. |
| [add_frame(frame)](#add_frame_frame_2) | Incorporate the specified frame seamlessly into the image, expanding its content <br/>            and versatility. Utilize this method to enhance image composition and management, <br/>            empowering efficient handling of multi-frame images within your application. |
| [add_frames(frames)](#add_frames_frames_3) | Integrate the array of frames seamlessly into the image, enriching its content and <br/>            versatility. Utilize this method to enhance image composition and management, <br/>            enabling efficient handling of multi-frame images within your application. |
| [add_page(page)](#add_page_page_4) | Effortlessly expand your BigTiff image by adding a new page with this intuitive method.<br/>            Perfect for developers seeking to dynamically enhance the content of their multi-page images. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | Implement _brightness_ adjustment for the image, allowing the <br/>            modification of overall luminance levels. Incorporate this method into your image <br/>            processing workflow to enhance visibility and improve the visual quality of <br/>            images within your application. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | Enhance the contrast of the [Image](/imaging/python-net/aspose.imaging/image/) instance, <br/>            amplifying the differences between its light and dark areas. Integrate this <br/>            functionality to improve the visual clarity and overall quality of the image <br/>            within your application. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | Apply gamma correction to the image, adjusting pixel intensities to achieve <br/>            desired color balance. Incorporate this method into your image processing <br/>            workflow to enhance visual quality and improve the accuracy of subsequent <br/>            analysis or display tasks within your application. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | Perform gamma correction on the image using individual coefficients for red, <br/>            green, and blue channels, allowing for fine-tuned adjustments of color balance <br/>            and contrast. Integrate this method into your image processing pipeline to <br/>            achieve precise control over color rendering and enhance visual fidelity within <br/>            your application. |
| align_resolutions() | Implement the AlignResolutions helper method to synchronize horizontal and <br/>            vertical resolutions, ensuring uniformity in image dimensions. This functionality <br/>            facilitates streamlined image processing workflows by harmonizing resolution <br/>            parameters, optimizing visual quality and consistency across various platforms and <br/>            devices. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | Calculates the percentage similarity between the extracted data and the original password. |
| auto_brightness_contrast() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | Implement binarization on the image employing Bradley's adaptive thresholding <br/>            algorithm with integral image thresholding. This approach dynamically computes <br/>            local thresholds based on the image's neighborhood, enhancing adaptability to <br/>            varying lighting conditions and ensuring robust segmentation for subsequent <br/>            processing tasks within your application. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | Apply binarization to the image using a predefined threshold, converting it into <br/>            a binary image with distinct foreground and background regions. Incorporate this <br/>            method into your image processing workflow to facilitate segmentation and feature <br/>            extraction tasks, enhancing the accuracy and efficiency of image analysis within <br/>            your application. |
| binarize_otsu() | Utilize Otsu thresholding to perform binarization on the image, automatically <br/>            determining the optimal threshold value based on the image's histogram. Integrate <br/>            this method into your image processing workflow to achieve effective segmentation <br/>            and feature extraction, enhancing the accuracy and reliability of image analysis <br/>            tasks within your application. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_13) | Blends this image instance with the _overlay_ image. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_14) | Blends this image instance with the _overlay_ image. |
| cache_data() | Caches the data private. |
| [can_load(file_path)](#can_load_file_path_15) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_16) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_17) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_18) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_19) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_20) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_21) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_save(options)](#can_save_options_22) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [create(files)](#create_files_23) | Creates the multipage image containing the specified files. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_24) | Creates the multipage image containing the specified files. |
| [create(image_options, width, height)](#create_image_options_width_height_25) | Creates a new image using the specified create options. |
| [create(images)](#create_images_26) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_27) | Creates a new image the specified images as pages. |
| [create(multipage_create_options)](#create_multipage_create_options_28) | Creates the specified multipage create options. |
| [create_from_files(files)](#create_from_files_files_29) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_30) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_images(images)](#create_from_images_images_31) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Creates a new image the specified images as pages. |
| [create_with_frame(frame)](#create_with_frame_frame_33) | Initializes a new instance of the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class. |
| [create_with_frames(frames)](#create_with_frames_frames_34) | Initializes a new instance of the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_35) | Perform cropping on the image by specifying shifts in the left, right, top, and <br/>            bottom directions. This method enables precise selection of the desired portion of <br/>            the image, facilitating efficient removal of unwanted areas and focusing on <br/>            essential content. Integrate this functionality into your image processing <br/>            pipeline to enhance clarity and composition as needed within your application. |
| [crop(rectangle)](#crop_rectangle_36) | Crop the image using a specified rectangular region, allowing precise selection of <br/>            desired content. Integrate this method into your image processing workflow to <br/>            efficiently remove unwanted areas and focus on essential details, enhancing the <br/>            overall clarity and composition of the image. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_37) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_38) | Execute dithering on the current image to enhance its visual quality and reduce <br/>            color banding artifacts. Integrate this method into your image processing workflow <br/>            to ensure smoother transitions between colors, resulting in improved overall image <br/>            appearance and clarity. |
| [embed_digital_signature(password)](#embed_digital_signature_password_39) | Embed digital sign based on provided password into each page of the image. |
| [filter(rectangle, options)](#filter_rectangle_options_40) | Filter the content within the specified rectangle, applying a designated image <br/>            processing filter to enhance or modify the selected region. Integrate this method <br/>            into your image manipulation workflow to achieve targeted enhancements or <br/>            transformations within your application. |
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
| [get_original_options()](#get_original_options__53) | Retrieve options derived from the original file settings, facilitating seamless <br/>            preservation of key parameters such as bit-depth and other essential attributes of <br/>            the original image. Utilize this method to maintain fidelity and consistency in <br/>            image processing tasks, ensuring optimal results without unnecessary alterations.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            <DOM Element: class at 0x24927cf0a60>.DataStreamSupporter.save()(string) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the <DOM Element: class at 0x24927e73280>.Image.save()(string,Aspose.Imaging.ImageOptionsBase) method as the second parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_54) | Gets an image pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_55) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_56) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_57) | Converts to aps. |
| [get_skew_angle()](#get_skew_angle__58) | Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| grayscale() | Convert the image to its grayscale representation, transforming it into a <br/>            single-channel image where each pixel represents intensity. Integrate this method <br/>            into your image processing pipeline to simplify analysis and enhance <br/>            compatibility with grayscale-based algorithms, facilitating various computer <br/>            vision and image analysis tasks within your application. |
| [insert_frame(index, frame_to_insert)](#insert_frame_index_frame_to_insert_59) | Insert the new frame at the specified index within the frame sequence, ensuring <br/>            precise control over frame arrangement. Employ this method to manage frame <br/>            sequences effectively, facilitating dynamic manipulation and organization of image <br/>            content within your application. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_60) | Performs a fast check to determine if the image is digitally signed, using the provided password and threshold. |
| [load(file_path)](#load_file_path_61) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_62) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_63) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_64) | Loads a new image from the specified stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_65) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_66) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_67) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_68) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the Aspose.Imaging.RasterImage.LoadCmyk32Pixels(Aspose.Imaging.Rectangle) method. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_69) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_70) | Loads 64-bit ARGB pixels partially by packs. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_71) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_72) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_73) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_74) | Loads raw data. |
| [load_stream(stream)](#load_stream_stream_75) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_76) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_77) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and Aspose.Imaging.RasterImage.Rotate(float) methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_78) | Utilize the NormalizeAngle method specifically designed for scanned text documents <br/>            to rectify skewed scans, ensuring accurate alignment. Seamlessly <br/>            integrate this functionality into your text processing workflows to enhance <br/>            document readability and quality, improving overall efficiency in text recognition <br/>            and analysis tasks.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and Aspose.Imaging.FileFormats.Tiff.TiffImage.Rotate(float,bool,Aspose.Imaging.Color) methods. |
| normalize_histogram() | Normalizes the image histogram — adjust pixel values to use all available range. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_79) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_80) | Reads the whole scan line by the specified scan line index. |
| [remove_frame(frame)](#remove_frame_frame_81) | Efficiently remove the specified frame from the image sequence, facilitating <br/>            streamlined frame management within your application. Integrate this functionality <br/>            to enhance precision and flexibility in frame manipulation, ensuring seamless <br/>            organization and presentation of image content. |
| [remove_frame(index)](#remove_frame_index_82) | Removes the frame by its index. |
| [remove_frame_by_index(index)](#remove_frame_by_index_index_83) | Removes the frame by its index. |
| remove_metadata() | Removes this image instance metadata by setting this [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) and [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) values to **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_frame(index, frame_to_replace)](#replace_frame_index_frame_to_replace_87) | Substitute the frame at the designated position with another frame seamlessly, <br/>            facilitating dynamic frame management within the image sequence. Integrate this <br/>            method to enhance flexibility and precision in frame manipulation, ensuring <br/>            optimal organization and presentation of image content within your application. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_88) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_89) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [resize(new_width, new_height)](#resize_new_width_new_height_90) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_91) | Conduct a proportional resize operation on the image, preserving its aspect ratio <br/>            while adjusting its dimensions. Employ this method to dynamically scale images <br/>            within your application, ensuring consistent visual representation of content <br/>            integrity.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_92) | Adjust the size of the image based on specified settings, allowing for precise <br/>            control over dimensions, aspect ratio, and scaling behavior. Integrate this <br/>            method into your image processing workflow to achieve customized resizing <br/>            operations tailored to the specific requirements of your application. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_93) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_94) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_95) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_96) | Conduct a proportional adjustment of the image's height, preserving its aspect <br/>            ratio for consistent visual integrity. Employ this method to dynamically resize <br/>            images within your application, ensuring optimal display across diverse platforms <br/>            and devices without compromising content quality. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_97) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_98) | Resizes the height proportionally. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_99) | Conduct a proportional resize operation on the image, preserving its aspect ratio <br/>            while adjusting its dimensions. Employ this method to dynamically scale images <br/>            within your application, ensuring consistent visual representation of content <br/>            integrity.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_100) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_101) | Adjust the width of the image while maintaining its aspect ratio, ensuring <br/>            proportional resizing for optimal visual presentation. Utilize this method to <br/>            dynamically scale images within your application, facilitating consistent and <br/>            aesthetically pleasing rendering across various display contexts. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_102) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_103) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_104) | Rotate image around the center. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_105) | Rotate the image around its center point by a specified angle, enabling precise <br/>            orientation adjustments. Incorporate this functionality into your image processing <br/>            pipeline to facilitate accurate transformations, ensuring optimal alignment and <br/>            presentation of visual content within your application. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_106) | Perform rotation, flipping, or a combination of both operations exclusively on the <br/>            active frame. This method allows precise manipulation of individual frames within <br/>            the image sequence, enhancing flexibility in image editing and composition within <br/>            your application. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_107) | Rotates the flip all. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_108) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_109) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_110) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_111) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_112) | Saves the object's data to the specified stream. |
| [save(stream, options_base)](#save_stream_options_base_113) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_114) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_115) | Saves the 32-bit ARGB pixels. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_116) | Saves the pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_117) | Saves the pixels.<br/>            This method is deprecated. Please use more effective the Aspose.Imaging.RasterImage.SaveCmyk32Pixels(Aspose.Imaging.Rectangle,int[]) method. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_118) | Saves the pixels internal main. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_119) | Saves the raw data. |
| [save_to_stream(stream)](#save_to_stream_stream_120) | Saves image to stream |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_121) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_122) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_123) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_124) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_125) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_126) | Sets the image palette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_127) | Sets an image pixel for the specified position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_128) | Establishes the resolution for the specified [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), enabling <br/>            precise control over image rendering and display properties. Integrate this <br/>            functionality to optimize visual output and ensure compatibility with diverse <br/>            output devices and platforms, enhancing the overall user experience. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_129) | Writes the whole scan line to the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_130) | Writes the whole scan line to the specified scan line index. |


### Constructor: BigTiffImage(frame) {#BigTiffImage_frame_1}


```
 BigTiffImage(frame) 
```

Create a new instance of the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class by initializing<br/>            it with a TiffFrame parameter. Ideal for developers seeking a convenient<br/>            way to work with BigTiffImage objects, ensuring flexibility and ease of integration<br/>            into their projects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The tiff frame to initialize image with. |

### Constructor: BigTiffImage(frames) {#BigTiffImage_frames_2}


```
 BigTiffImage(frames) 
```

Begin utilizing the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class seamlessly by<br/>            initializing a new instance with a list of TiffFrames parameter.<br/>            Perfect for developers seeking a straightforward method to work with<br/>            BigTiffImage objects containing multiple frames, ensuring efficiency of their projects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frames. |

### Method: add(image) {#add_image_1}


```
 add(image) 
```

Add the frames from the specified image seamlessly into the current frame, <br/>            consolidating their content and enhancing compositional flexibility. Integrate <br/>            this method to streamline frame management and manipulation within your <br/>            application, facilitating efficient handling of multi-frame images.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image | [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) | The source image. |

### Method: add_frame(frame) {#add_frame_frame_2}


```
 add_frame(frame) 
```

Incorporate the specified frame seamlessly into the image, expanding its content <br/>            and versatility. Utilize this method to enhance image composition and management, <br/>            empowering efficient handling of multi-frame images within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frame to add. |

### Method: add_frames(frames) {#add_frames_frames_3}


```
 add_frames(frames) 
```

Integrate the array of frames seamlessly into the image, enriching its content and <br/>            versatility. Utilize this method to enhance image composition and management, <br/>            enabling efficient handling of multi-frame images within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frames array to add |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

Effortlessly expand your BigTiff image by adding a new page with this intuitive method.<br/>            Perfect for developers seeking to dynamically enhance the content of their multi-page images.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | The page to add. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

Implement _brightness_ adjustment for the image, allowing the <br/>            modification of overall luminance levels. Incorporate this method into your image <br/>            processing workflow to enhance visibility and improve the visual quality of <br/>            images within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

Enhance the contrast of the [Image](/imaging/python-net/aspose.imaging/image/) instance, <br/>            amplifying the differences between its light and dark areas. Integrate this <br/>            functionality to improve the visual clarity and overall quality of the image <br/>            within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

Apply gamma correction to the image, adjusting pixel intensities to achieve <br/>            desired color balance. Incorporate this method into your image processing <br/>            workflow to enhance visual quality and improve the accuracy of subsequent <br/>            analysis or display tasks within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Perform gamma correction on the image using individual coefficients for red, <br/>            green, and blue channels, allowing for fine-tuned adjustments of color balance <br/>            and contrast. Integrate this method into your image processing pipeline to <br/>            achieve precise control over color rendering and enhance visual fidelity within <br/>            your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma_red | float | Gamma for red channel coefficient |
| gamma_green | float | Gamma for green channel coefficient |
| gamma_blue | float | Gamma for blue channel coefficient |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_9}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_10}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | float | The brightness difference between pixel and the average of an s x s window of pixels<br/>                centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_11}


```
 binarize_bradley(brightness_difference, window_size) 
```

Implement binarization on the image employing Bradley's adaptive thresholding <br/>            algorithm with integral image thresholding. This approach dynamically computes <br/>            local thresholds based on the image's neighborhood, enhancing adaptability to <br/>            varying lighting conditions and ensuring robust segmentation for subsequent <br/>            processing tasks within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | float | The brightness difference between pixel and the average of an s x s window of pixels<br/>            centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

Apply binarization to the image using a predefined threshold, converting it into <br/>            a binary image with distinct foreground and background regions. Incorporate this <br/>            method into your image processing workflow to facilitate segmentation and feature <br/>            extraction tasks, enhancing the accuracy and efficiency of image analysis within <br/>            your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | System.Byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of<br/>            255 will be assigned to it, 0 otherwise. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_13}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_14}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_15}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_16}


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


### Method: can_load(stream)  [static] {#can_load_stream_17}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_18}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_19}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_20}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_21}


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


### Method: can_save(options) {#can_save_options_22}


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


### Method: create(files)  [static] {#create_files_23}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_24}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_25}


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


### Method: create(images)  [static] {#create_images_26}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_27}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_28}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_29}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_30}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


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


### Method: create_with_frame(frame)  [static] {#create_with_frame_frame_33}


```
 create_with_frame(frame) 
```

Initializes a new instance of the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The tiff frame to initialize image with. |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) | A new BigTiffImage image that includes the frame. |


### Method: create_with_frames(frames)  [static] {#create_with_frames_frames_34}


```
 create_with_frames(frames) 
```

Initializes a new instance of the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frames. |

**Returns**

| Type | Description |
| :- | :- |
| [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_35}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Perform cropping on the image by specifying shifts in the left, right, top, and <br/>            bottom directions. This method enables precise selection of the desired portion of <br/>            the image, facilitating efficient removal of unwanted areas and focusing on <br/>            essential content. Integrate this functionality into your image processing <br/>            pipeline to enhance clarity and composition as needed within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left_shift | int | The left shift. |
| right_shift | int | The right shift. |
| top_shift | int | The top shift. |
| bottom_shift | int | The bottom shift. |

### Method: crop(rectangle) {#crop_rectangle_36}


```
 crop(rectangle) 
```

Crop the image using a specified rectangular region, allowing precise selection of <br/>            desired content. Integrate this method into your image processing workflow to <br/>            efficiently remove unwanted areas and focus on essential details, enhancing the <br/>            overall clarity and composition of the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_37}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_38}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Execute dithering on the current image to enhance its visual quality and reduce <br/>            color banding artifacts. Integrate this method into your image processing workflow <br/>            to ensure smoother transitions between colors, resulting in improved overall image <br/>            appearance and clarity.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | The dithering method. |
| bits_count | int | The final bits count for dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The custom palette for dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_39}


```
 embed_digital_signature(password) 
```

Embed digital sign based on provided password into each page of the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| password | string | The password used for generate digital sign data |

### Method: filter(rectangle, options) {#filter_rectangle_options_40}


```
 filter(rectangle, options) 
```

Filter the content within the specified rectangle, applying a designated image <br/>            processing filter to enhance or modify the selected region. Integrate this method <br/>            into your image manipulation workflow to achieve targeted enhancements or <br/>            transformations within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |
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
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get pixels for. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | The default pixels array. |


### Method: get_default_options(args) {#get_default_options_args_43}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_44}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | The partial pixel loader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_46}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_50}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_51}


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
| System.DateTime | The date and time the resource image was last modified. |


### Method: get_original_options() {#get_original_options__53}


```
 get_original_options() 
```

Retrieve options derived from the original file settings, facilitating seamless <br/>            preservation of key parameters such as bit-depth and other essential attributes of <br/>            the original image. Utilize this method to maintain fidelity and consistency in <br/>            image processing tasks, ensuring optimal results without unnecessary alterations.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            <DOM Element: class at 0x24927cf0a60>.DataStreamSupporter.save()(string) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the <DOM Element: class at 0x24927e73280>.Image.save()(string,Aspose.Imaging.ImageOptionsBase) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options based on the original file settings. |


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
| [Color](/imaging/python-net/aspose.imaging/color/) | The pixel color for the specified location. |


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
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The clipping rectangle. |
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


### Method: insert_frame(index, frame_to_insert) {#insert_frame_index_frame_to_insert_59}


```
 insert_frame(index, frame_to_insert) 
```

Insert the new frame at the specified index within the frame sequence, ensuring <br/>            precise control over frame arrangement. Employ this method to manage frame <br/>            sequences effectively, facilitating dynamic manipulation and organization of image <br/>            content within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of new frame in list of frames |
| frame_to_insert | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frame To Insert. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_60}


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


### Method: load(file_path)  [static] {#load_file_path_61}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_62}


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


### Method: load(stream)  [static] {#load_stream_63}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_64}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_65}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_66}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_67}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_68}


```
 load_cmyk_pixels(rectangle) 
```

Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the Aspose.Imaging.RasterImage.LoadCmyk32Pixels(Aspose.Imaging.Rectangle) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The loaded CMYK pixels array. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_69}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | The partial pixel loader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | The 64-bit ARGB pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_71}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_72}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_73}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_74}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_75}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_76}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_77}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_78}


```
 normalize_angle(resize_proportionally, background_color) 
```

Utilize the NormalizeAngle method specifically designed for scanned text documents <br/>            to rectify skewed scans, ensuring accurate alignment. Seamlessly <br/>            integrate this functionality into your text processing workflows to enhance <br/>            document readability and quality, improving overall efficiency in text recognition <br/>            and analysis tasks.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and Aspose.Imaging.FileFormats.Tiff.TiffImage.Rotate(float,bool,Aspose.Imaging.Color) methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color of the background. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_79}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_80}


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


### Method: remove_frame(frame) {#remove_frame_frame_81}


```
 remove_frame(frame) 
```

Efficiently remove the specified frame from the image sequence, facilitating <br/>            streamlined frame management within your application. Integrate this functionality <br/>            to enhance precision and flexibility in frame manipulation, ensuring seamless <br/>            organization and presentation of image content.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frame to remove. |

### Method: remove_frame(index) {#remove_frame_index_82}


```
 remove_frame(index) 
```

Removes the frame by its index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of frame to be removed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The removed frame. |


### Method: remove_frame_by_index(index) {#remove_frame_by_index_index_83}


```
 remove_frame_by_index(index) 
```

Removes the frame by its index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index of frame to be removed. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The removed frame. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


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

### Method: replace_frame(index, frame_to_replace) {#replace_frame_index_frame_to_replace_87}


```
 replace_frame(index, frame_to_replace) 
```

Substitute the frame at the designated position with another frame seamlessly, <br/>            facilitating dynamic frame management within the image sequence. Integrate this <br/>            method to enhance flexibility and precision in frame manipulation, ensuring <br/>            optimal organization and presentation of image content within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero based frame position. |
| frame_to_replace | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The frame to replace. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | The removed frame. |


### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_88}


```
 replace_non_transparent_colors(new_color) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_89}


```
 replace_non_transparent_colors(new_color_argb) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_argb | int | New color ARGB value to replace non transparent colors with. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_90}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_91}


```
 resize(new_width, new_height, resize_type) 
```

Conduct a proportional resize operation on the image, preserving its aspect ratio <br/>            while adjusting its dimensions. Employ this method to dynamically scale images <br/>            within your application, ensuring consistent visual representation of content <br/>            integrity.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_92}


```
 resize(new_width, new_height, settings) 
```

Adjust the size of the image based on specified settings, allowing for precise <br/>            control over dimensions, aspect ratio, and scaling behavior. Integrate this <br/>            method into your image processing workflow to achieve customized resizing <br/>            operations tailored to the specific requirements of your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_93}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_94}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_95}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_96}


```
 resize_height_proportionally(new_height, resize_type) 
```

Conduct a proportional adjustment of the image's height, preserving its aspect <br/>            ratio for consistent visual integrity. Employ this method to dynamically resize <br/>            images within your application, ensuring optimal display across diverse platforms <br/>            and devices without compromising content quality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_97}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_98}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_99}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Conduct a proportional resize operation on the image, preserving its aspect ratio <br/>            while adjusting its dimensions. Employ this method to dynamically scale images <br/>            within your application, ensuring consistent visual representation of content <br/>            integrity.<br/>            The proportional resize will resize each frame according to the ratio of _newWidth_/width and _newHeight_/height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_100}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_101}


```
 resize_width_proportionally(new_width, resize_type) 
```

Adjust the width of the image while maintaining its aspect ratio, ensuring <br/>            proportional resizing for optimal visual presentation. Utilize this method to <br/>            dynamically scale images within your application, facilitating consistent and <br/>            aesthetically pleasing rendering across various display contexts.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_102}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_103}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_104}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_105}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotate the image around its center point by a specified angle, enabling precise <br/>            orientation adjustments. Incorporate this functionality into your image processing <br/>            pipeline to facilitate accurate transformations, ensuring optimal alignment and <br/>            presentation of visual content within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Color of the background. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_106}


```
 rotate_flip(rotate_flip_type) 
```

Perform rotation, flipping, or a combination of both operations exclusively on the <br/>            active frame. This method allows precise manipulation of individual frames within <br/>            the image sequence, enhancing flexibility in image editing and composition within <br/>            your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip type. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_107}


```
 rotate_flip_all(rotate_flip) 
```

Rotates the flip all.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | The rotate flip. |

### Method: save(file_path) {#save_file_path_108}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_109}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_110}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_111}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_112}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save(stream, options_base) {#save_stream_options_base_113}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_114}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_115}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | int[] | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_116}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Saves the pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | int[] | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_117}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Saves the pixels.<br/>            This method is deprecated. Please use more effective the Aspose.Imaging.RasterImage.SaveCmyk32Pixels(Aspose.Imaging.Rectangle,int[]) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_118}


```
 save_pixels(rectangle, pixels) 
```

Saves the pixels internal main.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The pixels. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_119}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_120}


```
 save_to_stream(stream) 
```

Saves image to stream

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_121}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_122}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_123}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_124}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_125}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_126}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_127}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_128}


```
 set_resolution(dpi_x, dpi_y) 
```

Establishes the resolution for the specified [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), enabling <br/>            precise control over image rendering and display properties. Integrate this <br/>            functionality to optimize visual output and ensure compatibility with diverse <br/>            output devices and platforms, enhancing the overall user experience.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dpi_x | float | The horizontal resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | The vertical resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_129}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| argb_32_pixels | int[] | The 32-bit ARGB colors array to write. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_130}


```
 write_scan_line(scan_line_index, pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | The pixel colors array to write. |

