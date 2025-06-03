---
title: DjvuImage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.djvu/djvuimage/
---

**Summary:** DjVu document class supports graphics file format and facilitates seamless<br/>            management of scanned documents and books, integrating text, drawings, images,<br/>            and photos into a single format. Supporting multi-page operations, you can<br/>            efficiently access unique document identifiers, count pages, set active pages,<br/>            and retrieve specific document pages. With features for resizing, rotating,<br/>            dithering, cropping, grayscale transformation, gamma corrections, adjustments,<br/>            and filters application, this class empowers precise manipulation and enhancement<br/>            of DjVu images to meet diverse application needs with ease and precision.

**Module:** [aspose.imaging.fileformats.djvu](/imaging/python-net/aspose.imaging.fileformats.djvu/)

**Full Name:** aspose.imaging.fileformats.djvu.DjvuImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IHasXmpData, IHasMetadata, IMultipageImage, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [DjvuImage(stream)](#DjvuImage_stream_1) | Start working with DjVu images by initializing a new instance of the<br/>            [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) class using a Stream parameter. Perfect for<br/>            developers who want seamless integration of DjVu image processing into<br/>            their projects. |
| [DjvuImage(stream, load_options)](#DjvuImage_stream_load_options_2) | Start working with DjVu images seamlessly with this constructor, which<br/>            initializes a new [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) class instance using a Stream and<br/>            LoadOptions parameters. Perfect for developers who want precise control over<br/>            DjVu image loading options while maintaining simplicity and efficiency. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage) | r/w | Navigate through your DjVu document by accessing or setting the currently active<br/>            page using this property. Seamlessly switch between pages to focus on specific<br/>            content and enhance your document viewing experience. |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| djvu_pages | [DjvuPage[]](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage) | r | Quickly retrieve all the pages contained within your DjVu document using this<br/>            property. Simplify your document processing workflow by easily accessing and<br/>            managing individual pages within your DjVu files. Improve efficiency and<br/>            streamline your tasks with convenient page retrieval. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Obtain the file format information associated with your DjVu image file. Quickly<br/>            determine the format of your file for seamless integration into your workflow. |
| first_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage) | r | Access the first page of your DjVu document with this property. Quickly retrieve<br/>            the initial page to begin viewing or processing your document efficiently. |
| has_alpha | bool | r | Quickly determine whether your DjVu image file contains an alpha channel.<br/>            Simplify your workflow by checking for the presence of transparency information<br/>            in your images. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| has_transparent_color | bool | r/w | Gets a value indicating whether image has transparent color. |
| height | int | r | Gets the image height. |
| horizontal_resolution | double | r/w | Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| identifier | int | r | Gets the unique identifier for the document |
| image_opacity | float | r | Gets opacity of this image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| last_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage) | r | Retrieve the last page of your DjVu document using this property. Quickly access<br/>            the final page for viewing or processing purposes with ease. |
| next_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage) | r | Navigate through your DjVu document by accessing the next page with this<br/>            convenient property. Quickly move forward in your document viewing or<br/>            processing tasks. |
| page_count | int | r | Retrieve the total number of pages in your DjVu image collection with this property.<br/>            Ideal for quickly assessing the extent of your document or book stored in DjVu format.<br/>            Improve your workflow efficiency with accurate page count information. |
| [pages](#pages1) | [Image[]](/imaging/python-net/aspose.imaging/image) | r | Access the individual pages of your DjVu image collection with this property.<br/>            Simplify navigation and manipulation of your document or book stored in DjVu format<br/>            by accessing each page directly. Improve your workflow efficiency with easy<br/>            page retrieval. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
| previous_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage) | r | Quickly move backward in your DjVu document viewing or processing tasks by<br/>            accessing the previous page with this convenient property. Efficiently navigate<br/>            through your document with ease. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter) | r/w | Gets or sets the custom color converter |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat) | r | Gets the raw data format. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings) | r | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| raw_fallback_index | int | r/w | Gets or sets the fallback index to use when palette index is out of bounds |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter) | r/w | Gets or sets the indexed color converter |
| raw_line_size | int | r | Gets the raw line size in bytes. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets the object size. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets the image transparent color. |
| update_xmp_data | bool | r/w | Gets or sets a value indicating whether to update the XMP metadata. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| use_raw_data | bool | r/w | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| vertical_resolution | double | r/w | Gets or sets the vertical resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Gets the image width. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets XMP data from frame. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Adjust the _brightness_ of an image using a specified parameter, <br/>            providing control over luminance levels for optimal visual clarity. This method enhances <br/>            or diminishes the overall brightness of the image, allowing for fine adjustments to <br/>            achieve desired lighting effects. By modulating brightness, users can optimize image <br/>            visibility and enhance detail reproduction for improved viewing experience. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Enhance [Image](/imaging/python-net/aspose.imaging/image/) contrast to improve visual clarity and <br/>            highlight details with this method, which adjusts the difference in brightness between <br/>            light and dark areas. By fine-tuning contrast levels, users can achieve more vivid and <br/>            impactful images, enhancing overall image quality and maximizing detail visibility. <br/>            This adjustment helps to bring out subtle nuances in color and texture, resulting in <br/>            more dynamic and visually appealing images. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Gamma correction, specifically for the red, green, and blue channels, involves adjusting <br/>            the brightness of each color component separately. By applying different gamma <br/>            coefficients to the RGB channels, you can fine-tune the overall brightness and contrast <br/>            of an image. This technique ensures accurate color representation and improves the <br/>            visual quality of the image across different display devices. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Gamma correction is applied to an image with customizable parameters for the red, green, <br/>            and blue channels, allowing precise adjustment of color balance and brightness. This <br/>            method enhances image quality by fine-tuning color representation, ensuring optimal <br/>            rendering across different display devices. Adjusting gamma values for individual <br/>            channels improves color balance and visual appeal. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_5) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_6) | Binarization using Bradley's adaptive thresholding algorithm with integral image<br/>            thresholding is a method that calculates a local threshold for each pixel based on a <br/>            local neighborhood. It adapts to variations in illumination across the image, making it <br/>            suitable for images with uneven lighting conditions. By computing the threshold using <br/>            integral images, it efficiently handles large neighborhoods, making it applicable to <br/>            real-time applications. This technique is commonly used in document processing, OCR <br/>            (Optical Character Recognition), and image segmentation tasks where accurate <br/>            binarization is essential for subsequent analysis. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_7) | Binarization with a predefined threshold simplifies complex images into binary<br/>            representations, where pixels are categorized as either black or white based on their <br/>            intensity compared to a specified threshold value. This technique is commonly used in <br/>            image processing to enhance clarity, simplify analysis, and prepare images for further <br/>            processing steps such as optical character recognition (OCR). By applying a fixed <br/>            threshold, you can quickly transform grayscale images into binary form, making them <br/>            easier to interpret and extract meaningful information from. |
| binarize_otsu() | Binarization using Otsu thresholding is a technique that automatically calculates an<br/>            optimal threshold value based on the image's histogram. It separates the image into <br/>            foreground and background by minimizing the intra-class variance. Otsu's method is <br/>            widely used for segmenting images into binary form, particularly when the distribution <br/>            of pixel intensities is bimodal or multimodal. This approach is beneficial for tasks <br/>            such as object detection, image segmentation, and feature extraction, where accurate <br/>            delineation between foreground and background is crucial. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_8) | Blends this image instance with the _overlay_ image. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_9) | Blends this image instance with the _overlay_ image. |
| cache_data() | Cache the data privately to optimize performance and reduce the need for repeated data <br/>            retrieval from external sources. This approach also helps conserve resources, <br/>            particularly in scenarios where data access is frequent or resources are limited. |
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
| [create_from_files(files)](#create_from_files_files_24) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_25) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_images(images)](#create_from_images_images_26) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_27) | Creates a new image the specified images as pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_28) | Crop with shifts allows you to precisely adjust the position and dimensions of the<br/>            cropped area within an image. This feature is invaluable for refining compositions,<br/>            aligning elements, and emphasizing focal points in your visuals. By incorporating shifts<br/>            into the cropping process, you can achieve pixel-perfect precision and fine-tune the<br/>            framing of your images with ease. |
| [crop(rectangle)](#crop_rectangle_29) | "Crop" trims your image to focus on specific details or remove unwanted elements,<br/>            enhancing its composition and visual impact. Whether you're adjusting photos for social<br/>            media, creating website banners, or designing print materials, this tool helps you<br/>            refine your images with precision and clarity. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_30) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_31) | The "Dither" function applies a dithering effect to your image, enhancing its visual<br/>            quality by reducing banding and improving color transitions. Whether you're working<br/>            on digital art, photography, or graphic design projects, this feature adds a<br/>            professional touch to your images, making them appear smoother and more refined. |
| [filter(rectangle, options)](#filter_rectangle_options_32) | Apply filters to a specified rectangular area within the image to enhance or modify its <br/>            appearance. By targeting specific regions, this method allows for precise adjustments, <br/>            such as blurring, sharpening, or applying artistic effects, to achieve desired visual <br/>            outcomes. Fine-tuning filters on selected areas empowers users to customize image <br/>            aesthetics, improve clarity, and create artistic effects tailored to their preferences. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_33) | Gets an image 32-bit ARGB pixel. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_34) | Gets the default 32-bit ARGB pixels array. |
| [get_default_options(args)](#get_default_options_args_35) | Gets the default options. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_36) | Gets the default pixels array using partial pixel loader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_37) | Gets the default raw data array using partial pixel loader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_38) | Gets the default raw data array. |
| [get_file_format(file_path)](#get_file_format_file_path_39) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_40) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_41) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_42) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_43) | Gets rectangle which fits the current image. |
| [get_modify_date(use_default)](#get_modify_date_use_default_44) | Gets the date and time the resource image was last modified. |
| [get_original_options()](#get_original_options__45) | Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_46) | Gets an image pixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_47) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_48) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_49) | Converts to aps. |
| [get_skew_angle()](#get_skew_angle__50) | Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| grayscale() | Grayscale transformation converts an image to a black-and-white representation, where <br/>            each pixel's intensity is represented by a single value ranging from black to white. <br/>            This process removes color information, resulting in a monochromatic image. Grayscale <br/>            images are commonly used in applications where color is unnecessary or where simplicity <br/>            is preferred, such as document scanning, printing, and certain types of image analysis. |
| [load(file_path)](#load_file_path_51) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_52) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_53) | Load your DjVu document with this method. Streamline your process by quickly<br/>            accessing and importing your DjVu files into your application. |
| [load(stream, load_options)](#load_stream_load_options_54) | Import your DjVu document by utilizing this method with stream and loadOptions<br/>            parameters. Streamline your process by quickly accessing and importing DjVu files<br/>            into your application, providing flexibility and customization options to meet<br/>            your needs. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_55) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_56) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_57) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_58) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [load_document(stream)](#load_document_stream_59) | Load your DjVu document with this method. Streamline your process by quickly<br/>            accessing and importing your DjVu files into your application. |
| [load_document(stream, load_options)](#load_document_stream_load_options_60) | Import your DjVu document by utilizing this method with stream and loadOptions<br/>            parameters. Streamline your process by quickly accessing and importing DjVu files<br/>            into your application, providing flexibility and customization options to meet<br/>            your needs. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_61) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_62) | Loads 64-bit ARGB pixels partially by packs. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_63) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_64) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_65) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_66) | Loads raw data. |
| [load_stream(stream)](#load_stream_stream_67) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_68) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_69) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_70) | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods. |
| normalize_histogram() | Normalizes the image histogram — adjust pixel values to use all available range. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_71) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_72) | Reads the whole scan line by the specified scan line index. |
| remove_metadata() | Removes this image instance metadata by setting this [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) value to **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_73) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_74) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_75) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_76) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_77) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [resize(new_width, new_height)](#resize_new_width_new_height_78) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_79) | Resize the image using the `Resize` method, providing a simple and effective way<br/>            to adjust the dimensions of your images according to your requirements. This<br/>            versatile functionality empowers you to easily scale images to your desired size,<br/>            enhancing their usability across various platforms and applications. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_80) | Resize the image to the specified width and height while applying additional settings <br/>            as needed. This method enables users to adjust the dimensions of the image while <br/>            maintaining desired attributes such as aspect ratio, image quality, and compression <br/>            settings. By providing flexibility in resizing options, users can tailor the image to <br/>            fit specific requirements and optimize its appearance for various applications and <br/>            platforms. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_81) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_82) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_83) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_84) | The `ResizeHeightProportionally` method allows you to adjust the height of your<br/>            image while preserving its aspect ratio. This ensures that your image maintains<br/>            its proportions, preventing distortion and preserving its visual integrity.<br/>            Whether you're optimizing images for web pages, mobile apps, or print media, this<br/>            method ensures that your images look their best across different platforms and devices. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_85) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_86) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_87) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_88) | The `ResizeWidthProportionally` method offers a convenient solution to adjust the<br/>            width of your image while maintaining its aspect ratio. By proportionally resizing<br/>            the width, you can ensure that your images remain visually appealing and<br/>            consistent across different devices and screen sizes, enhancing their versatility<br/>            and usability in various contexts. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_89) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_90) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_91) | Rotate image around the center. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_92) | Rotate the image around its center with the Rotate method of the<br/>            RasterCachedMultipageImage class. This convenient feature allows you to easily<br/>            adjust the orientation of images while maintaining their center position,<br/>            enhancing your image manipulation capabilities. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_93) | The `RotateFlip` method offers versatile manipulation options for your image, allowing<br/>            you to rotate, flip, or perform both operations on the active frame independently.<br/>            Whether you're editing photos, creating graphics, or enhancing digital art, this<br/>            method provides precise control over the orientation and composition of your images,<br/>            ensuring they meet your creative vision with ease and efficiency. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_94) | Rotates the flip all. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_95) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_96) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_97) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_98) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_99) | Saves the data. |
| [save(stream, options_base)](#save_stream_options_base_100) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_101) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_102) | Saves the 32-bit ARGB pixels. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_103) | Saves the pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_104) | Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_105) | Saves pixels (format specific method). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_106) | Saves the raw data. |
| [save_to_stream(stream)](#save_to_stream_stream_107) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_108) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_109) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_110) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_111) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_112) | Sets an image 32-bit ARGB pixel for the specified position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_113) | Sets the image palette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_114) | Sets an image pixel for the specified position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_115) | Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_116) | Writes the whole scan line to the specified scan line index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_117) | Writes the whole scan line to the specified scan line index. |


### Constructor: DjvuImage(stream) {#DjvuImage_stream_1}


```
 DjvuImage(stream) 
```

Start working with DjVu images by initializing a new instance of the<br/>            [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) class using a Stream parameter. Perfect for<br/>            developers who want seamless integration of DjVu image processing into<br/>            their projects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |


**See also:**

**[Example # 1](#example_137)**: This example shows how to load a DJVU image from a file stream.


### Constructor: DjvuImage(stream, load_options) {#DjvuImage_stream_load_options_2}


```
 DjvuImage(stream, load_options) 
```

Start working with DjVu images seamlessly with this constructor, which<br/>            initializes a new [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) class instance using a Stream and<br/>            LoadOptions parameters. Perfect for developers who want precise control over<br/>            DjVu image loading options while maintaining simplicity and efficiency.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

### Property: pages {#pages1}

Access the individual pages of your DjVu image collection with this property.<br/>            Simplify navigation and manipulation of your document or book stored in DjVu format<br/>            by accessing each page directly. Improve your workflow efficiency with easy<br/>            page retrieval.

**See also:**

**[Example # 1](#example_137)**: This example shows how to load a DJVU image from a file stream.


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Adjust the _brightness_ of an image using a specified parameter, <br/>            providing control over luminance levels for optimal visual clarity. This method enhances <br/>            or diminishes the overall brightness of the image, allowing for fine adjustments to <br/>            achieve desired lighting effects. By modulating brightness, users can optimize image <br/>            visibility and enhance detail reproduction for improved viewing experience.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |


**See also:**

**[Example # 1](#example_147)**: The following example performs brightness correction of a DJVU image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Enhance [Image](/imaging/python-net/aspose.imaging/image/) contrast to improve visual clarity and <br/>            highlight details with this method, which adjusts the difference in brightness between <br/>            light and dark areas. By fine-tuning contrast levels, users can achieve more vivid and <br/>            impactful images, enhancing overall image quality and maximizing detail visibility. <br/>            This adjustment helps to bring out subtle nuances in color and texture, resulting in <br/>            more dynamic and visually appealing images.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |


**See also:**

**[Example # 1](#example_148)**: The following example performs contrast correction of a DJVU image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Gamma correction, specifically for the red, green, and blue channels, involves adjusting <br/>            the brightness of each color component separately. By applying different gamma <br/>            coefficients to the RGB channels, you can fine-tune the overall brightness and contrast <br/>            of an image. This technique ensures accurate color representation and improves the <br/>            visual quality of the image across different display devices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |


**See also:**

**[Example # 1](#example_145)**: The following example performs gamma-correction of a DJVU image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gamma correction is applied to an image with customizable parameters for the red, green, <br/>            and blue channels, allowing precise adjustment of color balance and brightness. This <br/>            method enhances image quality by fine-tuning color representation, ensuring optimal <br/>            rendering across different display devices. Adjusting gamma values for individual <br/>            channels improves color balance and visual appeal.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma_red | float | Gamma for red channel coefficient |
| gamma_green | float | Gamma for green channel coefficient |
| gamma_blue | float | Gamma for blue channel coefficient |


**See also:**

**[Example # 1](#example_146)**: The following example performs gamma-correction of a DJVU image applying diff...


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_5}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels<br/>                centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_6}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarization using Bradley's adaptive thresholding algorithm with integral image<br/>            thresholding is a method that calculates a local threshold for each pixel based on a <br/>            local neighborhood. It adapts to variations in illumination across the image, making it <br/>            suitable for images with uneven lighting conditions. By computing the threshold using <br/>            integral images, it efficiently handles large neighborhoods, making it applicable to <br/>            real-time applications. This technique is commonly used in document processing, OCR <br/>            (Optical Character Recognition), and image segmentation tasks where accurate <br/>            binarization is essential for subsequent analysis.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels<br/>            centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |


**See also:**

**[Example # 1](#example_143)**: The following example binarizes a DJVU image with Bradley's adaptive threshol...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_7}


```
 binarize_fixed(threshold) 
```

Binarization with a predefined threshold simplifies complex images into binary<br/>            representations, where pixels are categorized as either black or white based on their <br/>            intensity compared to a specified threshold value. This technique is commonly used in <br/>            image processing to enhance clarity, simplify analysis, and prepare images for further <br/>            processing steps such as optical character recognition (OCR). By applying a fixed <br/>            threshold, you can quickly transform grayscale images into binary form, making them <br/>            easier to interpret and extract meaningful information from.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of<br/>            255 will be assigned to it, 0 otherwise. |


**See also:**

**[Example # 1](#example_141)**: The following example binarizes a DJVU image with the predefined threshold. B...


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


### Method: create_from_files(files)  [static] {#create_from_files_files_24}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_25}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_26}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_27}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_28}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Crop with shifts allows you to precisely adjust the position and dimensions of the<br/>            cropped area within an image. This feature is invaluable for refining compositions,<br/>            aligning elements, and emphasizing focal points in your visuals. By incorporating shifts<br/>            into the cropping process, you can achieve pixel-perfect precision and fine-tune the<br/>            framing of your images with ease.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left_shift | int | The left shift. |
| right_shift | int | The right shift. |
| top_shift | int | The top shift. |
| bottom_shift | int | The bottom shift. |

### Method: crop(rectangle) {#crop_rectangle_29}


```
 crop(rectangle) 
```

"Crop" trims your image to focus on specific details or remove unwanted elements,<br/>            enhancing its composition and visual impact. Whether you're adjusting photos for social<br/>            media, creating website banners, or designing print materials, this tool helps you<br/>            refine your images with precision and clarity.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |


**See also:**

**[Example # 1](#example_140)**: The following example crops a DJVU image. The cropping area is be specified v...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_30}


```
 dither(dithering_method, bits_count) 
```

Performs dithering on the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_31}


```
 dither(dithering_method, bits_count, custom_palette) 
```

The "Dither" function applies a dithering effect to your image, enhancing its visual<br/>            quality by reducing banding and improving color transitions. Whether you're working<br/>            on digital art, photography, or graphic design projects, this feature adds a<br/>            professional touch to your images, making them appear smoother and more refined.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod) | The dithering method. |
| bits_count | int | The final bits count for dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The custom palette for dithering. |

### Method: filter(rectangle, options) {#filter_rectangle_options_32}


```
 filter(rectangle, options) 
```

Apply filters to a specified rectangular area within the image to enhance or modify its <br/>            appearance. By targeting specific regions, this method allows for precise adjustments, <br/>            such as blurring, sharpening, or applying artistic effects, to achieve desired visual <br/>            outcomes. Fine-tuning filters on selected areas empowers users to customize image <br/>            aesthetics, improve clarity, and create artistic effects tailored to their preferences.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | The options. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_33}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_34}


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


### Method: get_default_options(args) {#get_default_options_args_35}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_36}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Gets the default pixels array using partial pixel loader.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get pixels for. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_37}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_38}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_39}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_40}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_41}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_42}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_43}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_44}


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


### Method: get_original_options() {#get_original_options__45}


```
 get_original_options() 
```

Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options based on the original file settings. |


### Method: get_pixel(x, y) {#get_pixel_x_y_46}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_47}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_48}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_49}


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


### Method: get_skew_angle() {#get_skew_angle__50}


```
 get_skew_angle() 
```

Gets the skew angle.<br/>            This method is applicable to scanned text documents, to determine the skew angle when scanning.

**Returns**

| Type | Description |
| :- | :- |
| float | The skew angle, in degrees. |


### Method: load(file_path)  [static] {#load_file_path_51}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_52}


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


### Method: load(stream)  [static] {#load_stream_53}


```
 load(stream) 
```

Load your DjVu document with this method. Streamline your process by quickly<br/>            accessing and importing your DjVu files into your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | Loaded djvu document |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_54}


```
 load(stream, load_options) 
```

Import your DjVu document by utilizing this method with stream and loadOptions<br/>            parameters. Streamline your process by quickly accessing and importing DjVu files<br/>            into your application, providing flexibility and customization options to meet<br/>            your needs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | Loaded djvu document |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_55}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_56}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_57}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_58}


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


### Method: load_document(stream)  [static] {#load_document_stream_59}


```
 load_document(stream) 
```

Load your DjVu document with this method. Streamline your process by quickly<br/>            accessing and importing your DjVu files into your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage) | Loaded djvu document |


### Method: load_document(stream, load_options)  [static] {#load_document_stream_load_options_60}


```
 load_document(stream, load_options) 
```

Import your DjVu document by utilizing this method with stream and loadOptions<br/>            parameters. Streamline your process by quickly accessing and importing DjVu files<br/>            into your application, providing flexibility and customization options to meet<br/>            your needs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage) | Loaded djvu document |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_61}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_62}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader) | The 64-bit ARGB pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_63}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_64}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_65}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_66}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_67}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_68}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_69}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_70}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_71}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_72}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_73}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_74}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_75}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_76}


```
 replace_non_transparent_colors(new_color) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_77}


```
 replace_non_transparent_colors(new_color_argb) 
```

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_color_argb | int | New color ARGB value to replace non transparent colors with. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_78}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_79}


```
 resize(new_width, new_height, resize_type) 
```

Resize the image using the `Resize` method, providing a simple and effective way<br/>            to adjust the dimensions of your images according to your requirements. This<br/>            versatile functionality empowers you to easily scale images to your desired size,<br/>            enhancing their usability across various platforms and applications.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_80}


```
 resize(new_width, new_height, settings) 
```

Resize the image to the specified width and height while applying additional settings <br/>            as needed. This method enables users to adjust the dimensions of the image while <br/>            maintaining desired attributes such as aspect ratio, image quality, and compression <br/>            settings. By providing flexibility in resizing options, users can tailor the image to <br/>            fit specific requirements and optimize its appearance for various applications and <br/>            platforms.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_81}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_82}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_83}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_84}


```
 resize_height_proportionally(new_height, resize_type) 
```

The `ResizeHeightProportionally` method allows you to adjust the height of your<br/>            image while preserving its aspect ratio. This ensures that your image maintains<br/>            its proportions, preventing distortion and preserving its visual integrity.<br/>            Whether you're optimizing images for web pages, mobile apps, or print media, this<br/>            method ensures that your images look their best across different platforms and devices.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_85}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_86}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_87}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_88}


```
 resize_width_proportionally(new_width, resize_type) 
```

The `ResizeWidthProportionally` method offers a convenient solution to adjust the<br/>            width of your image while maintaining its aspect ratio. By proportionally resizing<br/>            the width, you can ensure that your images remain visually appealing and<br/>            consistent across different devices and screen sizes, enhancing their versatility<br/>            and usability in various contexts.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_89}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_90}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_91}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_92}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotate the image around its center with the Rotate method of the<br/>            RasterCachedMultipageImage class. This convenient feature allows you to easily<br/>            adjust the orientation of images while maintaining their center position,<br/>            enhancing your image manipulation capabilities.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed<br/>            according to rotated rectangle (corner points) projections in other<br/>            case that leaves dimensions untouched and only<br/>            __internal__ image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_93}


```
 rotate_flip(rotate_flip_type) 
```

The `RotateFlip` method offers versatile manipulation options for your image, allowing<br/>            you to rotate, flip, or perform both operations on the active frame independently.<br/>            Whether you're editing photos, creating graphics, or enhancing digital art, this<br/>            method provides precise control over the orientation and composition of your images,<br/>            ensuring they meet your creative vision with ease and efficiency.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip type. |


**See also:**

**[Example # 1](#example_138)**: This example loads a DJVU image, rotates it by 90 degrees clockwise and optio...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_94}


```
 rotate_flip_all(rotate_flip) 
```

Rotates the flip all.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip. |

### Method: save(file_path) {#save_file_path_95}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_96}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_97}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_98}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_99}


```
 save(stream) 
```

Saves the data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

### Method: save(stream, options_base) {#save_stream_options_base_100}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_101}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_102}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Saves the 32-bit ARGB pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The 32-bit ARGB pixels array. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_103}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Saves the pixels.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | int | The CMYK pixels presented as the 32-bit integer values. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_104}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Saves the pixels.<br/>            This method is deprecated. Please use more effective the [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) method.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor) | The CMYK pixels array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_105}


```
 save_pixels(rectangle, pixels) 
```

Saves pixels (format specific method).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to save pixels to. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The 32-bit ARGB pixels array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_106}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_107}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_108}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_109}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_110}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_111}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_112}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_113}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_114}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_115}


```
 set_resolution(dpi_x, dpi_y) 
```

Sets the resolution for this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| dpi_x | double | The horizontal resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | double | The vertical resolution, in dots per inch, of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_116}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Writes the whole scan line to the specified scan line index.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Zero based index of the scan line. |
| argb_32_pixels | int | The 32-bit ARGB colors array to write. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_117}


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
### This example shows how to load a DJVU image from a file stream. {#example_137}
``` python
from os.path import join
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions       

dir_: str = "c:\\temp"
# Load a DJVU image from a file stream.
with open(join(dir_, "sample.djvu"), "rb") as stream:
	with DjvuImage(stream) as djvu_image:
		# Save each page as an individual PNG image.
		for djvu_page in djvu_image.pages:
			# Generate a file name based on the page number.
			file_name: str = "sample.{0}.png".format(djvu_page.page_number)
			djvu_page.save(join(dir_, file_name), PngOptions())


```

### This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_138}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Rotate, flip and save to the output file.
	with aspycore.as_of(Image.load(join(dir_, "sample.djvu")), DjvuImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example crops a DJVU image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_140}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions

with Image.load("sample.djvu") as image:
	djvuImage = as_of(image, DjvuImage)
	# Crop the image. The cropping area is the rectangular central area of the image.
	area = Rectangle(djvuImage.width // 4, djvuImage.height // 4, djvuImage.width // 2, djvuImage.height // 2)
	djvuImage.crop(area)
	# Save the cropped image to PNG
	djvuImage.save("sample.Crop.png", PngOptions())


```

### The following example binarizes a DJVU image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_141}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Binarize the image with a threshold value of 127.
	# If a corresponding gray value of a pixel is greater than 127, a value of 255 will be assigned to it, 0 otherwise.
	djvu_image.binarize_fixed(127)
	djvu_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_143}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Binarize the image with a brightness difference of 5. The brightness is a difference between a pixel and the average of an 10 x 10 window of pixels centered around this pixel.
	djvu_image.binarize_bradley(5, 10)
	djvu_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a DJVU image. {#example_145}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Set gamma coefficient for red, green and blue channels.
	djvu_image.adjust_gamma(2.5)
	djvu_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a DJVU image applying different coefficients for color components. {#example_146}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Set individual gamma coefficients for red, green and blue channels.
	djvu_image.adjust_gamma(1.5, 2.5, 3.5)
	djvu_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a DJVU image. {#example_147}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Set the brightness value. The accepted values of brightness are in the range [-255, 255].
	djvu_image.adjust_brightness(50)
	djvu_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a DJVU image. {#example_148}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Set the contrast value. The accepted values of contrast are in the range [-100f, 100f].
	djvu_image.adjust_contrast(50.0)
	djvu_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

