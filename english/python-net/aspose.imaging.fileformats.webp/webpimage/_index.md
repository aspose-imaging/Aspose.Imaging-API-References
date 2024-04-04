---
title: WebPImage Class
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.webp/webpimage/
---

**Summary:** Manipulate WebP raster images with our API, using its modern features for both<br/>            lossless and lossy compression, ensuring optimal image quality with reduced file sizes.<br/>            Seamlessly handle extended file formats, animations, and alpha channels, while easily<br/>            updating dimensions, resizing proportionally, cropping, rotating, applying filters,<br/>            adjusting image parameters, and converting to other image formats for versatile<br/>            web image optimization.

**Module:** [aspose.imaging.fileformats.webp](/imaging/python-net/aspose.imaging.fileformats.webp/)

**Full Name:** aspose.imaging.fileformats.webp.WebPImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

**Aspose.Imaging Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WebPImage(path)](#WebPImage_path_1) | Instantiate a fresh instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class, initialized <br/>            from a provided file source. Utilize this constructor to seamlessly create WebP <br/>            image objects directly from files, streamlining the process of loading and <br/>            manipulating WebP image data within your application. |
| [WebPImage(path, load_options)](#WebPImage_path_load_options_2) | Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class using a file and <br/>            specified load options, facilitating flexible handling of WebP image data. Utilize <br/>            this constructor to seamlessly initialize WebP image objects from files while <br/>            customizing loading parameters according to your application's requirements. |
| [WebPImage(raster_image)](#WebPImage_raster_image_3) | Instantiate a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class, initialized <br/>            from a provided rasterImage object. This constructor allows for seamless <br/>            conversion of raster images to WebP format, enabling efficient handling and <br/>            manipulation of image data within your application. |
| [WebPImage(raster_image, load_options)](#WebPImage_raster_image_load_options_4) | Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class using a rasterImage object and <br/>            specified load options, enabling flexible handling of image data. Utilize this <br/>            constructor to seamlessly initialize WebP image objects from raster images while <br/>            customizing loading parameters according to your application's requirements. |
| [WebPImage(stream)](#WebPImage_stream_5) | Instantiate a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class, initialized <br/>            from a provided stream source. Utilize this constructor to seamlessly create WebP <br/>            image objects directly from streams, enabling efficient handling and manipulation <br/>            of WebP image data within your application. |
| [WebPImage(stream, load_options)](#WebPImage_stream_load_options_6) | Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class using a stream and <br/>            specified load options, facilitating versatile handling of WebP image data. <br/>            Incorporate this constructor to seamlessly initialize WebP image objects from <br/>            streams while customizing loading parameters as needed within your application. |
| [WebPImage(width, height, options)](#WebPImage_width_height_options_7) | Instantiate a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class with an empty <br/>            image of specified width and height dimensions. This constructor allows for the <br/>            creation of blank WebP images, providing a foundation for subsequent image <br/>            manipulation and content generation within your application. |
| [WebPImage(width, height, options, load_options)](#WebPImage_width_height_options_load_options_8) | Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class with an empty image and specified <br/>            load options. This constructor allows for the initialization of WebP images with <br/>            customizable loading parameters, providing flexibility in image creation and <br/>            manipulation within your application. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Access the file format value associated with the image, providing information <br/>            about the format in which the image is stored. Utilize this property to determine <br/>            the file format of the image, facilitating compatibility checks and <br/>            format-specific processing within your application. |
| has_alpha | bool | r | Retrieve whether the image contains an alpha channel, indicating the presence of <br/>            transparency information. Utilize this property to determine whether the image <br/>            includes transparency, enabling appropriate handling and processing of <br/>            alpha-related operations within your application. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| has_transparent_color | bool | r/w | Gets a value indicating whether image has transparent color. |
| height | int | r | Gets the image height. |
| horizontal_resolution | double | r/w | Gets or sets the horizontal resolution, in pixels per inch, of this [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Gets opacity of this image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether image data is cached currently. |
| is_raw_data_available | bool | r | Gets a value indicating whether raw data loading is supported. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | r | Retrieve or modify the options associated with the specified property, enabling <br/>            fine-tuned customization of behavior and settings. Utilize this property to <br/>            seamlessly access and manipulate configurable parameters, facilitating versatile <br/>            control and optimization within your application's functionality. |
| page_count | int | r | Retrieve the total count of pages within the specified document, facilitating <br/>            efficient navigation and management of multi-page content. Incorporate this <br/>            functionality to enhance user experience, enabling seamless access to <br/>            comprehensive document structures. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image) | r | Access the WebP blocks within the image, allowing detailed examination or <br/>            manipulation of the underlying block structure. Utilize this property to analyze <br/>            or modify individual blocks within the WebP image data, facilitating advanced <br/>            image processing techniques within your application. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether the image components must be premultiplied. |
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
| [add_block(block)](#add_block_block_1) | Incorporate a new WebP block into the image, enriching its content and <br/>            facilitating advanced image manipulation. Integrate this method to dynamically <br/>            enhance the structure and complexity of the WebP image data within your <br/>            application, enabling precise control and optimization of image rendering. |
| [add_page(page)](#add_page_page_2) | Append a new page to the image, expanding its content and accommodating additional <br/>            visual elements. Integrate this method to facilitate dynamic page management <br/>            within your application, enabling seamless creation and augmentation of multi-page <br/>            documents or images. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Implement _brightness_ adjustment for the image, allowing the <br/>            modification of overall luminance levels. Incorporate this method into your image <br/>            processing workflow to enhance visibility and improve the visual quality of images <br/>            within your application. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Enhance the contrast of the [Image](/imaging/python-net/aspose.imaging/image/), amplifying the <br/>            differences between light and dark areas. Integrate this method into your image <br/>            processing workflow to improve visual clarity and overall image quality within <br/>            your application. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Apply gamma correction to the image, adjusting pixel intensities to achieve <br/>            desired brightness and color balance. Incorporate this method into your image <br/>            processing workflow to enhance visual quality and improve the accuracy of <br/>            subsequent analysis or display tasks within your application. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Perform gamma correction on the image using individual coefficients for the red, <br/>            green, and blue channels, allowing for fine-tuned adjustments of color balance and <br/>            contrast. Integrate this method into your image processing pipeline to achieve <br/>            precise control over color rendering and enhance visual fidelity within your <br/>            application. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_7) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_8) | Apply binarization to the image using Bradley's adaptive thresholding algorithm <br/>            with integral image thresholding. This method dynamically computes local <br/>            thresholds based on the image's neighborhood, enhancing adaptability to varying <br/>            lighting conditions and ensuring robust segmentation for subsequent processing <br/>            tasks within your application. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_9) | Perform binarization on the image using a predefined threshold value, converting <br/>            it into a binary image where pixels are classified as foreground or background <br/>            based on their intensity relative to the threshold. Integrate this method into <br/>            your image processing workflow to facilitate segmentation and feature extraction <br/>            tasks, enhancing the accuracy and efficiency of subsequent analysis within your <br/>            application. |
| binarize_otsu() | Perform binarization on the image using Otsu's thresholding method, automatically <br/>            determining the optimal threshold value based on the image's histogram. Integrate <br/>            this method into your image processing workflow to achieve effective segmentation <br/>            and feature extraction, enhancing the accuracy and reliability of image analysis <br/>            tasks within your application. |
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
| clear_blocks() | Clear all existing WebP blocks from the image, facilitating a clean slate for <br/>            subsequent modifications or additions. Utilize this method to effectively reset <br/>            the block structure within the WebP image data, ensuring optimal management and <br/>            organization of image content within your application. |
| [create(image_options, width, height)](#create_image_options_width_height_20) | Creates a new image using the specified create options. |
| [create(images)](#create_images_21) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_22) | Creates a new image the specified images as pages. |
| [create_from_file_with_options(path, load_options)](#create_from_file_with_options_path_load_options_23) | Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from file. |
| [create_from_image(raster_image)](#create_from_image_raster_image_24) | Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from rasterImage. |
| [create_from_image_with_options(raster_image, load_options)](#create_from_image_with_options_raster_image_load_options_25) | Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from rasterImage. |
| [create_from_stream(stream)](#create_from_stream_stream_26) | Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class<br/>                from stream. |
| [create_from_stream_with_options(stream, load_options)](#create_from_stream_with_options_stream_load_options_27) | Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from stream. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_28) | Crop the image by applying left, right, top, and bottom shifts, effectively <br/>            selecting a region of interest within the image. Utilize this method to <br/>            dynamically extract desired portions of the image while adjusting its composition <br/>            and focus according to your application's requirements. |
| [crop(rectangle)](#crop_rectangle_29) | Crop the image using a specified rectangle region, removing unwanted portions <br/>            while retaining the desired content. Integrate this method into your image <br/>            processing workflow to precisely extract and focus on specific areas of interest <br/>            within the image, enhancing clarity and composition for various applications. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_30) | Performs dithering on the current image. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_31) | Perform dithering on the current image to reduce color banding and enhance visual <br/>            quality. Integrate this method into your image processing workflow to achieve <br/>            smoother transitions between colors and improve the overall appearance of the <br/>            image within your application. |
| [filter(rectangle, options)](#filter_rectangle_options_32) | Filter the content within the specified rectangle, applying a designated image <br/>            processing filter to enhance or modify the selected region. Integrate this method <br/>            into your image manipulation workflow to achieve targeted enhancements or <br/>            transformations within your application. |
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
| grayscale() | Convert the image to its grayscale representation, transforming it into a <br/>            single-channel image where each pixel represents intensity or luminance. Integrate <br/>            this method into your image processing pipeline to simplify analysis and enhance <br/>            compatibility with grayscale-based algorithms, facilitating various computer <br/>            vision and image analysis tasks within your application. |
| [insert_block(index, block)](#insert_block_index_block_51) | Insert a new WebP block at the specified index within the image, enabling precise <br/>            control over the block sequence. Integrate this method to seamlessly incorporate <br/>            additional WebP blocks into the image data structure, facilitating advanced image <br/>            processing and optimization within your application. |
| [load(file_path)](#load_file_path_52) | Loads a new image from the specified file. |
| [load(file_path, load_options)](#load_file_path_load_options_53) | Loads a new image from the specified file. |
| [load(stream)](#load_stream_54) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_55) | Loads the data from stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_56) | Loads 32-bit ARGB pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_57) | Loads 64-bit ARGB pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_58) | Loads pixels in CMYK format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_59) | Loads pixels in CMYK format.<br/>            This method is deprecated. Please use more effective the [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) method. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_60) | Loads 32-bit ARGB pixels partially (by blocks). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_61) | Loads 64-bit ARGB pixels partially by packs. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_62) | Loads pixels partially by packs. |
| [load_pixels(rectangle)](#load_pixels_rectangle_63) | Loads pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_64) | Loads raw data. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_65) | Loads raw data. |
| [load_stream(stream)](#load_stream_stream_66) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_67) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_68) | Loads a new image from the specified file. |
| normalize_angle() | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) methods. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_69) | Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_70) | Reads the whole scan line by the specified scan line index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_71) | Reads the whole scan line by the specified scan line index. |
| [remove_block(block)](#remove_block_block_72) | Remove the specified WebP block from the image, facilitating efficient management <br/>            of image data structure. Utilize this method to streamline image processing <br/>            workflows by eliminating unnecessary blocks or components within your application. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_73) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_74) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_75) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_76) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_77) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges.<br/>                Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [resize(new_width, new_height)](#resize_new_width_new_height_78) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_79) | Resizes the image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_80) | Resizes the image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_81) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_82) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_83) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_84) | Adjust the height of the image proportionally, while preserving its aspect ratio <br/>            for consistent resizing. Integrate this method into your image processing workflow <br/>            to dynamically resize images with uniform proportions, ensuring optimal display or <br/>            storage within your application. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_85) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_86) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_87) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_88) | Proportionally adjust the width of the image while maintaining its aspect ratio. <br/>            Integrate this method into your image processing workflow to dynamically resize <br/>            images with consistent proportions, ensuring optimal display or storage within <br/>            your application. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_89) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_90) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_91) | Rotate image around the center. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_92) | Rotate the image around its center by a specified angle, while proportionally <br/>            resizing it and applying specified background color parameters. Incorporate this <br/>            method into your image processing workflow to achieve precise transformations with <br/>            customizable background colors, ensuring optimal visual presentation within your <br/>            application. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_93) | Apply rotation, flipping, or both operations exclusively to the active frame <br/>            within the image. Integrate this method into your image processing workflow to <br/>            achieve precise manipulation of individual frames, enhancing flexibility and <br/>            control over frame transformations within your application. |
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
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_105) | Saves the pixels internal main. |
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


### Constructor: WebPImage(path) {#WebPImage_path_1}


```
 WebPImage(path) 
```

Instantiate a fresh instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class, initialized <br/>            from a provided file source. Utilize this constructor to seamlessly create WebP <br/>            image objects directly from files, streamlining the process of loading and <br/>            manipulating WebP image data within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to file WebP Image |

### Constructor: WebPImage(path, load_options) {#WebPImage_path_load_options_2}


```
 WebPImage(path, load_options) 
```

Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class using a file and <br/>            specified load options, facilitating flexible handling of WebP image data. Utilize <br/>            this constructor to seamlessly initialize WebP image objects from files while <br/>            customizing loading parameters according to your application's requirements.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to file WebP Image |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

### Constructor: WebPImage(raster_image) {#WebPImage_raster_image_3}


```
 WebPImage(raster_image) 
```

Instantiate a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class, initialized <br/>            from a provided rasterImage object. This constructor allows for seamless <br/>            conversion of raster images to WebP format, enabling efficient handling and <br/>            manipulation of image data within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |

### Constructor: WebPImage(raster_image, load_options) {#WebPImage_raster_image_load_options_4}


```
 WebPImage(raster_image, load_options) 
```

Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class using a rasterImage object and <br/>            specified load options, enabling flexible handling of image data. Utilize this <br/>            constructor to seamlessly initialize WebP image objects from raster images while <br/>            customizing loading parameters according to your application's requirements.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

### Constructor: WebPImage(stream) {#WebPImage_stream_5}


```
 WebPImage(stream) 
```

Instantiate a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class, initialized <br/>            from a provided stream source. Utilize this constructor to seamlessly create WebP <br/>            image objects directly from streams, enabling efficient handling and manipulation <br/>            of WebP image data within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream WebP image. |

### Constructor: WebPImage(stream, load_options) {#WebPImage_stream_load_options_6}


```
 WebPImage(stream, load_options) 
```

Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class using a stream and <br/>            specified load options, facilitating versatile handling of WebP image data. <br/>            Incorporate this constructor to seamlessly initialize WebP image objects from <br/>            streams while customizing loading parameters as needed within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream WebP image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

### Constructor: WebPImage(width, height, options) {#WebPImage_width_height_options_7}


```
 WebPImage(width, height, options) 
```

Instantiate a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class with an empty <br/>            image of specified width and height dimensions. This constructor allows for the <br/>            creation of blank WebP images, providing a foundation for subsequent image <br/>            manipulation and content generation within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | The options. |

### Constructor: WebPImage(width, height, options, load_options) {#WebPImage_width_height_options_load_options_8}


```
 WebPImage(width, height, options, load_options) 
```

Create a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class with an empty image and specified <br/>            load options. This constructor allows for the initialization of WebP images with <br/>            customizable loading parameters, providing flexibility in image creation and <br/>            manipulation within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width |
| height | int | The image height. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | The options. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Incorporate a new WebP block into the image, enriching its content and <br/>            facilitating advanced image manipulation. Integrate this method to dynamically <br/>            enhance the structure and complexity of the WebP image data within your <br/>            application, enabling precise control and optimization of image rendering.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe) | The Webp block to add. |

### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Append a new page to the image, expanding its content and accommodating additional <br/>            visual elements. Integrate this method to facilitate dynamic page management <br/>            within your application, enabling seamless creation and augmentation of multi-page <br/>            documents or images.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The page to add. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Implement _brightness_ adjustment for the image, allowing the <br/>            modification of overall luminance levels. Incorporate this method into your image <br/>            processing workflow to enhance visibility and improve the visual quality of images <br/>            within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness | int | Brightness value. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Enhance the contrast of the [Image](/imaging/python-net/aspose.imaging/image/), amplifying the <br/>            differences between light and dark areas. Integrate this method into your image <br/>            processing workflow to improve visual clarity and overall image quality within <br/>            your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| contrast | float | Contrast value (in range [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Apply gamma correction to the image, adjusting pixel intensities to achieve <br/>            desired brightness and color balance. Incorporate this method into your image <br/>            processing workflow to enhance visual quality and improve the accuracy of <br/>            subsequent analysis or display tasks within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma | float | Gamma for red, green and blue channels coefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Perform gamma correction on the image using individual coefficients for the red, <br/>            green, and blue channels, allowing for fine-tuned adjustments of color balance and <br/>            contrast. Integrate this method into your image processing pipeline to achieve <br/>            precise control over color rendering and enhance visual fidelity within your <br/>            application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gamma_red | float | Gamma for red channel coefficient |
| gamma_green | float | Gamma for green channel coefficient |
| gamma_blue | float | Gamma for blue channel coefficient |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_7}


```
 binarize_bradley(brightness_difference) 
```

Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels<br/>                centered around this pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_8}


```
 binarize_bradley(brightness_difference, window_size) 
```

Apply binarization to the image using Bradley's adaptive thresholding algorithm <br/>            with integral image thresholding. This method dynamically computes local <br/>            thresholds based on the image's neighborhood, enhancing adaptability to varying <br/>            lighting conditions and ensuring robust segmentation for subsequent processing <br/>            tasks within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| brightness_difference | double | The brightness difference between pixel and the average of an s x s window of pixels<br/>            centered around this pixel. |
| window_size | int | The size of s x s window of pixels centered around this pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_9}


```
 binarize_fixed(threshold) 
```

Perform binarization on the image using a predefined threshold value, converting <br/>            it into a binary image where pixels are classified as foreground or background <br/>            based on their intensity relative to the threshold. Integrate this method into <br/>            your image processing workflow to facilitate segmentation and feature extraction <br/>            tasks, enhancing the accuracy and efficiency of subsequent analysis within your <br/>            application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| threshold | byte | Threshold value. If corresponding gray value of a pixel is greater than threshold, a value of<br/>            255 will be assigned to it, 0 otherwise. |

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


### Method: create_from_file_with_options(path, load_options)  [static] {#create_from_file_with_options_path_load_options_23}


```
 create_from_file_with_options(path, load_options) 
```

Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to file WebP Image |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage) |  |


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_24}


```
 create_from_image(raster_image) 
```

Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from rasterImage.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage) |  |


### Method: create_from_image_with_options(raster_image, load_options)  [static] {#create_from_image_with_options_raster_image_load_options_25}


```
 create_from_image_with_options(raster_image, load_options) 
```

Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from rasterImage.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage) | The raster image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage) |  |


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_26}


```
 create_from_stream(stream) 
```

Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class<br/>                from stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream WebP image. |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage) |  |


### Method: create_from_stream_with_options(stream, load_options)  [static] {#create_from_stream_with_options_stream_load_options_27}


```
 create_from_stream_with_options(stream, load_options) 
```

Initializes a new instance of the [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) class from stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream WebP image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_28}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Crop the image by applying left, right, top, and bottom shifts, effectively <br/>            selecting a region of interest within the image. Utilize this method to <br/>            dynamically extract desired portions of the image while adjusting its composition <br/>            and focus according to your application's requirements.

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

Crop the image using a specified rectangle region, removing unwanted portions <br/>            while retaining the desired content. Integrate this method into your image <br/>            processing workflow to precisely extract and focus on specific areas of interest <br/>            within the image, enhancing clarity and composition for various applications.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |

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

Perform dithering on the current image to reduce color banding and enhance visual <br/>            quality. Integrate this method into your image processing workflow to achieve <br/>            smoother transitions between colors and improve the overall appearance of the <br/>            image within your application.

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

Filter the content within the specified rectangle, applying a designated image <br/>            processing filter to enhance or modify the selected region. Integrate this method <br/>            into your image manipulation workflow to achieve targeted enhancements or <br/>            transformations within your application.

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


### Method: insert_block(index, block) {#insert_block_index_block_51}


```
 insert_block(index, block) 
```

Insert a new WebP block at the specified index within the image, enabling precise <br/>            control over the block sequence. Integrate this method to seamlessly incorporate <br/>            additional WebP blocks into the image data structure, facilitating advanced image <br/>            processing and optimization within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The zero-based element, at which _block_ will be<br/>                inserted. |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe) | The Webp block to add. |

### Method: load(file_path)  [static] {#load_file_path_52}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_53}


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


### Method: load(stream)  [static] {#load_stream_54}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_55}


```
 load(stream, load_options) 
```

Loads the data from stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream WebP image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_56}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_57}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_58}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_59}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_60}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Loads 32-bit ARGB pixels partially (by blocks).

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to load pixels from. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader) | The partial pixel loader. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_61}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Loads 64-bit ARGB pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader) | The 64-bit ARGB pixel loader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_62}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Loads pixels partially by packs.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The desired rectangle. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader) | The pixel loader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_63}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_64}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_65}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_66}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_67}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_68}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_69}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizes the angle.<br/>            This method is applicable to scanned text documents to get rid of the skewed scan.<br/>            This method uses [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) and [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) methods.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | if set to <c>true</c> you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | Color of the background. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_70}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_71}


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


### Method: remove_block(block) {#remove_block_block_72}


```
 remove_block(block) 
```

Remove the specified WebP block from the image, facilitating efficient management <br/>            of image data structure. Utilize this method to streamline image processing <br/>            workflows by eliminating unnecessary blocks or components within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe) | The block to remove. |

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

Resizes the image.

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

Resizes the image.

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

Adjust the height of the image proportionally, while preserving its aspect ratio <br/>            for consistent resizing. Integrate this method into your image processing workflow <br/>            to dynamically resize images with uniform proportions, ensuring optimal display or <br/>            storage within your application.

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

Proportionally adjust the width of the image while maintaining its aspect ratio. <br/>            Integrate this method into your image processing workflow to dynamically resize <br/>            images with consistent proportions, ensuring optimal display or storage within <br/>            your application.

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

Rotate the image around its center by a specified angle, while proportionally <br/>            resizing it and applying specified background color parameters. Incorporate this <br/>            method into your image processing workflow to achieve precise transformations with <br/>            customizable background colors, ensuring optimal visual presentation within your <br/>            application.

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

Apply rotation, flipping, or both operations exclusively to the active frame <br/>            within the image. Integrate this method into your image processing workflow to <br/>            achieve precise manipulation of individual frames, enhancing flexibility and <br/>            control over frame transformations within your application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | The rotate flip type. |

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
| stream | _io.BufferedRandom | The stream to save image data to. |

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

Saves the pixels internal main.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color) | The pixels. |

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

