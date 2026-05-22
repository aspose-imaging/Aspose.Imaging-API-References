---
title: "RasterImage 类"
type: docs
weight: 7060
url: /zh/python-net/aspose.imaging/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RasterImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | 获取或设置一个值，指示是否自动调整调色板。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色的值。 |
| bits_per_pixel | int | r | 获取图像每像素位数计数。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取图像的边界。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取 [Image](/imaging/python-net/aspose.imaging/image/) 容器。 |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | 获取对象的数据流。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 数据。 |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 获取文件格式的值 |
| [has_alpha](#has_alpha1) | bool | r | 获取指示此实例是否具有 alpha 的值。 |
| has_background_color | bool | r/w | 获取或设置指示图像是否具有背景颜色的值。 |
| has_transparent_color | bool | r/w | 获取或设置指示此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例是否具有透明颜色的值。 |
| height | int | r | 获取图像高度。 |
| horizontal_resolution | float | r/w | 获取或设置此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| image_opacity | float | r | 获取此图像的不透明度。 |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| is_raw_data_available | bool | r | 获取指示是否可用原始数据加载的值。 |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | 获取图像元数据。 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| [premultiply_components](#premultiply_components2) | bool | r/w | 获取或设置一个值，指示图像组件是否必须进行预乘。 |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | 获取或设置自定义颜色转换器 |
| [raw_data_format](#raw_data_format3) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取原始数据格式。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | 获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | r/w | 获取或设置当调色板索引超出范围时使用的回退索引 |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | 获取或设置索引颜色转换器 |
| raw_line_size | int | r | 获取以字节为单位的原始行大小。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | 获取图像尺寸。 |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取图像的透明颜色。 |
| update_xmp_data | bool | r/w | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| use_palette | bool | r | 获取一个值，指示是否使用图像调色板。 |
| use_raw_data | bool | r/w | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| vertical_resolution | float | r/w | 获取或设置此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| width | int | r | 获取图像宽度。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 Xmp 数据。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | 调整图像的亮度。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | 图像对比 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | 图像的伽马校正。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | 图像的伽马校正。 |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | 计算提取数据与原始密码之间的相似度百分比。 |
| auto_brightness_contrast() | 对整幅图像进行自动自适应亮度和对比度归一化。 |
| auto_rotate() | 自动根据从 Exif <br/>            元数据中提取的方向数据旋转图像。此方法确保图像以正确的方向显示，<br/>            提升用户体验并消除手动调整的需求。通过<br/>            分析 Exif 信息，图像相应旋转，提供跨不同平台和设备的无缝<br/>            浏览体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像批次时，<br/>            提高整体可用性。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | 使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | 使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | 使用预定义阈值对图像进行二值化 |
| binarize_otsu() | 使用 Otsu 阈值法对图像进行二值化 |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | 将此图像实例与 _overlay_ 图像混合。 |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | 将此图像实例与 _overlay_ 图像混合。 |
| cache_data() | 缓存数据，并确保不会从底层 [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) 进行额外的数据加载。 |
| [can_load(file_path)](#can_load_file_path_11) | 确定是否可以从指定的文件路径加载图像。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| [can_load(stream)](#can_load_stream_13) | 确定是否可以从指定的流加载图像。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | 确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。 |
| [can_load_stream(stream)](#can_load_stream_stream_15) | 确定是否可以从指定的流加载图像。 |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | 确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。 |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| [can_save(options)](#can_save_options_18) | 确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。 |
| [create(files)](#create_files_19) | 创建包含指定文件的多页图像。 |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | 创建包含指定文件的多页图像。 |
| [create(image_options, width, height)](#create_image_options_width_height_21) | 使用指定的创建选项创建新图像。 |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | 创建一个来自提供的像素数组的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例。<br/>            <br/>            验证指定的宽度和高度是否与像素数据的维度匹配。<br/>            仅当库处于授权模式时才能使用此方法。 |
| [create(images)](#create_images_23) | 使用指定的图像作为页面创建新图像。 |
| [create(images, dispose_images)](#create_images_dispose_images_24) | 创建一个新图像，将指定的图像作为页面。 |
| [create(multipage_create_options)](#create_multipage_create_options_25) | 创建指定的多页创建选项。 |
| [create_from_files(files)](#create_from_files_files_26) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_images(images)](#create_from_images_images_28) | 使用指定的图像作为页面创建新图像。 |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | 创建一个新图像，将指定的图像作为页面。 |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | 使用位移裁剪图像。 |
| [crop(rectangle)](#crop_rectangle_31) | 裁剪指定的矩形。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | 对当前图像执行抖动处理。 |
| [embed_digital_signature(password)](#embed_digital_signature_password_34) | 使用隐写术将基于提供的密码的数字签名嵌入图像中。 |
| [filter(rectangle, options)](#filter_rectangle_options_35) | 过滤指定的矩形区域。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_36) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_37) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_38) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_39) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_41) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_42) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_43) | 获取文件格式。 |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_44) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_45) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_46) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_47) | 获取资源图像最后修改的日期和时间。 |
| [get_original_options()](#get_original_options__48) | 根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。 |
| [get_pixel(x, y)](#get_pixel_x_y_49) | 获取图像像素。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_50) | 获取比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_51) | 获取比例宽度。 |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_52) | 转换为 aps。 |
| [get_skew_angle()](#get_skew_angle__53) | 获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。 |
| grayscale() | 将图像转换为灰度表示 |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_54) | 使用提供的密码和阈值执行快速检查，以确定图像是否已数字签名。 |
| [load(file_path)](#load_file_path_55) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(file_path, load_options)](#load_file_path_load_options_56) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(stream)](#load_stream_57) | 从指定的流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_58) | 从指定的流加载新图像。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | 加载 32 位 ARGB 像素。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | 加载 64 位 ARGB 像素。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | 加载 CMYK 格式的像素。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | 加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | 按包部分加载 32 位 ARGB 像素。 |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64) | 按包部分加载 64 位 ARGB 像素。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_65) | 按包部分加载像素。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_66) | 加载像素。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67) | 加载原始数据。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68) | 加载原始数据。 |
| [load_stream(stream)](#load_stream_stream_69) | 从指定的流加载新图像。 |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_70) | 从指定的流加载新图像。 |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_71) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| normalize_angle() | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_72) | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| normalize_histogram() | 归一化图像直方图 — 调整像素值以使用全部可用范围。 |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_73) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_74) | 按指定的扫描线索引读取整条扫描线。 |
| remove_metadata() | 通过将此 [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) 值设置为 **None** 来移除此图像实例的元数据。 |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_75) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_76) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_77) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_78) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_79) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_80) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_81) | 调整图像大小。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_82) | 使用扩展选项调整图像大小。 |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_83) | 调整图像大小。 |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_84) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_85) | 按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_86) | 按比例调整高度。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_87) | 按比例调整高度。 |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_88) | 按比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_89) | 按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_90) | 按比例调整宽度。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_91) | 按比例调整宽度。 |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_92) | 按比例调整宽度。 |
| [rotate(angle)](#rotate_angle_93) | 围绕中心旋转图像。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_94) | 围绕中心旋转图像。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_95) | 旋转、翻转或同时旋转和翻转图像。 |
| save() | 将图像数据保存到底层流中。 |
| [save(file_path)](#save_file_path_96) | 将图像保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_97) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_98) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, over_write)](#save_file_path_over_write_99) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_100) | 将对象的数据保存到指定的流中。 |
| [save(stream, options_base)](#save_stream_options_base_101) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_102) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_103) | 保存 32 位 ARGB 像素。 |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_104) | 保存像素。 |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_105) | 保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_106) | 保存像素。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_107) | 保存原始数据。 |
| [save_to_stream(stream)](#save_to_stream_stream_108) | 将对象的数据保存到指定的流中。 |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_109) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_111) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_112) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_113) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_114) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_115) | 为指定位置设置图像像素。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_116) | 为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_117) | 尝试设置 _metadata_ 实例，如果此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 类型。 |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_119) | 将整条扫描线写入指定的扫描线索引。 |


### Property: has_alpha {#has_alpha1}

获取指示此实例是否具有 alpha 的值。

**See also:**

**[Example # 1](#example_38)**: The following example loads raster images and prints information about raw da...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: premultiply_components {#premultiply_components2}

获取或设置一个值，指示图像组件是否必须进行预乘。

**See also:**

**[Example # 1](#example_37)**: The following example creates a new raster image, saves the specified semi-tr...


### Property: raw_data_format {#raw_data_format3}

获取原始数据格式。

**See also:**

**[Example # 1](#example_38)**: The following example loads raster images and prints information about raw da...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

调整图像的亮度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 亮度 | int | 亮度值。 |


**See also:**

**[Example # 1](#example_57)**: The following example performs brightness correction of an image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

图像对比

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |


**See also:**

**[Example # 1](#example_58)**: The following example performs contrast correction of an image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

图像的伽马校正。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |


**See also:**

**[Example # 1](#example_55)**: The following example performs gamma-correction of an image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

图像的伽马校正。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| gamma_red | float | 红色通道的伽马系数 |
| gamma_green | float | 绿色通道的伽马系数 |
| gamma_blue | float | 蓝色通道系数的 Gamma |


**See also:**

**[Example # 1](#example_56)**: The following example performs gamma-correction of an image applying differen...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


```
 analyze_percentage_digital_signature(password) 
```

计算提取数据与原始密码之间的相似度百分比。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于提取嵌入数据的密码。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 百分比相似度值。 |



**See also:**

**[Example # 1](#example_234)**: The example illustrates how to determine the probability (from 0% to 100%) th...


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brightness_difference | float | 像素与其周围以该像素为中心的 s x s 窗口像素平均值之间的亮度差。 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brightness_difference | float | 像素与其周围以该像素为中心的 s x s 窗口像素平均值之间的亮度差。 |
| window_size | int | 以该像素为中心的 s x s 像素窗口的大小 |


**See also:**

**[Example # 1](#example_53)**: The following example binarizes a raster image with Bradley's adaptive thresh...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

使用预定义阈值对图像进行二值化

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 阈值 | System.Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |


**See also:**

**[Example # 1](#example_51)**: The following example binarizes a raster image with the predefined threshold....


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


```
 blend(origin, overlay, overlay_alpha) 
```

将此图像实例与 _overlay_ 图像混合。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | 背景图像混合的原点。 |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 覆盖图像。 |
| overlay_alpha | System.Byte | 覆盖的 alpha。 |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

将此图像实例与 _overlay_ 图像混合。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | 背景图像混合的原点。 |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 覆盖图像。 |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 覆盖区域。 |
| overlay_alpha | System.Byte | 覆盖的 alpha。 |

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


```
 can_load(file_path) 
```

确定是否可以从指定的文件路径加载图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


```
 can_load(file_path, load_options) 
```

确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_load(stream)  [static] {#can_load_stream_13}


```
 can_load(stream) 
```

确定是否可以从指定的流加载图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


```
 can_load(stream, load_options) 
```

确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


```
 can_load_stream(stream) 
```

确定是否可以从指定的流加载图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


```
 can_load_stream_with_options(stream, load_options) 
```

确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


```
 can_load_with_options(file_path, load_options) 
```

确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_save(options) {#can_save_options_18}


```
 can_save(options) 
```

确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 要使用的保存选项。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> 如果图像可以保存为由传入的保存选项表示的指定文件格式；否则为 <c>false</c>。 |


### Method: create(files)  [static] {#create_files_19}


```
 create(files) 
```

创建包含指定文件的多页图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 文件 | string[] | 文件。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 多页图像 |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


```
 create(files, throw_exception_on_load_error) 
```

创建包含指定文件的多页图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 文件 | string[] | 文件。 |
| throw_exception_on_load_error | bool | 如果设置为 <c>true</c> [throw exception on load error]。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 多页图像 |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


```
 create(image_options, width, height) 
```

使用指定的创建选项创建新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 图像选项。 |
| width | int | 宽度。 |
| height | int | 高度。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 新创建的图像。 |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


```
 create(image_options, width, height, pixels) 
```

创建一个来自提供的像素数组的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例。<br/>            <br/>            验证指定的宽度和高度是否与像素数据的维度匹配。<br/>            仅当库处于授权模式时才能使用此方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 用于创建 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的选项。 |
| width | int | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的宽度。 |
| height | int | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的高度。 |
| 像素 | int[] | 用于填充图像的像素值数组。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 使用提供的像素数据填充的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)。 |


### Method: create(images)  [static] {#create_images_23}


```
 create(images) 
```

使用指定的图像作为页面创建新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | 图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Image 作为 IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


```
 create(images, dispose_images) 
```

创建一个新图像，将指定的图像作为页面。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | 图像。 |
| dispose_images | bool | 如果设置为 <c>true</c> [dispose images]。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Image 作为 IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


```
 create(multipage_create_options) 
```

创建指定的多页创建选项。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | 多页创建选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 多页图像 |


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


```
 create_from_files(files) 
```

创建包含指定文件的多页图像，将其作为延迟加载页面。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 文件 | string[] | 文件。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 多页图像 |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


```
 create_from_files(files, throw_exception_on_load_error) 
```

创建包含指定文件的多页图像，将其作为延迟加载页面。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 文件 | string[] | 文件。 |
| throw_exception_on_load_error | bool | 如果设置为 <c>true</c> 抛出加载错误异常。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 多页图像 |


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


```
 create_from_images(images) 
```

使用指定的图像作为页面创建新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | 图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Image 作为 IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


```
 create_from_images(images, dispose_images) 
```

创建一个新图像，将指定的图像作为页面。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | 图像。 |
| dispose_images | bool | 如果设置为 <c>true</c> [dispose images]。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Image 作为 IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

使用位移裁剪图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| left_shift | int | 左移。 |
| right_shift | int | 右移。 |
| top_shift | int | 上移。 |
| bottom_shift | int | 下移。 |


**See also:**

**[Example # 1](#example_50)**: The following example crops a raster image. The cropping area is specified vi...


### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

裁剪指定的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |


**See also:**

**[Example # 1](#example_49)**: The following example crops a raster image. The cropping area is be specified...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |


**See also:**

**[Example # 1](#example_39)**: The following example loads a raster image and performs threshold and Floyd d...


### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


```
 dither(dithering_method, bits_count, custom_palette) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 用于抖动的自定义调色板。 |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_34}


```
 embed_digital_signature(password) 
```

使用隐写术将基于提供的密码的数字签名嵌入图像中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于生成数字签名数据的密码 |


**See also:**

**[Example # 1](#example_232)**: The example shows how to embed digital signature based on provided password i...


### Method: filter(rectangle, options) {#filter_rectangle_options_35}


```
 filter(rectangle, options) 
```

过滤指定的矩形区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | 选项。 |


**See also:**

**[Example # 1](#example_59)**: The following example applies various types of filters to a raster image.


### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_36}


```
 get_argb_32_pixel(x, y) 
```

获取图像的 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 指定位置的 32 位 ARGB 像素。 |



**See also:**

**[Example # 1](#example_36)**: The following example shows how image caching affects performance. In general...

**[Example # 2](#example_40)**: The following example loads a raster image and obtains the color of an arbitr...


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_37}


```
 get_default_argb_32_pixels(rectangle) 
```

获取默认的 32 位 ARGB 像素数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 默认像素数组。 |


### Method: get_default_options(args) {#get_default_options_args_38}


```
 get_default_options(args) 
```

获取默认选项。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| args | System.Object | 参数。 |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 默认选项 |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_39}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

使用部分像素加载器获取默认原始数据数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | 部分原始数据加载器。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 原始数据设置。 |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_41}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

获取默认原始数据数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取原始数据的矩形。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 原始数据设置。 |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | 默认原始数据数组。 |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_42}


```
 get_file_format(file_path) 
```

获取文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | 确定的文件格式。 |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_43}


```
 get_file_format(stream) 
```

获取文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | 确定的文件格式。 |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_44}


```
 get_file_format_of_stream(stream) 
```

获取文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | 确定的文件格式。 |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_45}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

获取适合当前图像的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取合适矩形的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素。 |
| width | int | 对象宽度。 |
| height | int | 对象高度。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 适配矩形，若未找到适配矩形则抛出异常。 |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_46}


```
 get_fitting_rectangle(rectangle, width, height) 
```

获取适合当前图像的矩形。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取合适矩形的矩形。 |
| width | int | 对象宽度。 |
| height | int | 对象高度。 |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 适配矩形，若未找到适配矩形则抛出异常。 |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_47}


```
 get_modify_date(use_default) 
```

获取资源图像最后修改的日期和时间。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| use_default | bool | 如果设置为 <c>true</c>，则使用 FileInfo 中的信息作为默认值。 |

**Returns**

| Type | Description |
| :- | :- |
| System.DateTime | 资源图像上次修改的日期和时间。 |


### Method: get_original_options() {#get_original_options__48}


```
 get_original_options() 
```

根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_49}


```
 get_pixel(x, y) 
```

获取图像像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | 指定位置的像素颜色。 |



**See also:**

**[Example # 1](#example_41)**: The following example loads a raster image and obtains the color of an arbitr...


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_50}


```
 get_proportional_height(width, height, new_width) 
```

获取比例高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 宽度。 |
| height | int | 高度。 |
| new_width | int | 新的宽度。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 比例高度。 |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_51}


```
 get_proportional_width(width, height, new_height) 
```

获取比例宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 宽度。 |
| height | int | 高度。 |
| new_height | int | 新的高度。 |

**Returns**

| Type | Description |
| :- | :- |
| int | 比例宽度。 |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_52}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

转换为 aps。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 图像选项。 |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 裁剪矩形。 |
| page_number | int[] | 页码。 |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | 序列化流 |


### Method: get_skew_angle() {#get_skew_angle__53}


```
 get_skew_angle() 
```

获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。

**Returns**

| Type | Description |
| :- | :- |
| float | 倾斜角度（单位：度）。 |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_54}


```
 is_digital_signed(password, percentage_threshold) 
```

使用提供的密码和阈值执行快速检查，以确定图像是否已数字签名。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于检查签名的密码。 |
| percentage_threshold | int | 阈值（百分比）[0-100] 用于确定图像是否被视为已签名。<br/>            如果未指定，将使用默认阈值（<c>75</c>）。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果图像已签名则为 true，否则为 false。 |



**See also:**

**[Example # 1](#example_231)**: The example shows how to validate that the embedded digital signature matches...

**[Example # 2](#example_233)**: The example demonstrates how to verify that the embedded digital signature ma...


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 加载图像的文件路径或 URL。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 加载图像的文件路径或 URL。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

从指定的流加载新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

从指定的流加载新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

加载 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 已加载的 32 位 ARGB 像素数组。 |



**See also:**

**[Example # 1](#example_43)**: The following example shows how to load and process pixels of a raster image....


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

加载 64 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 已加载的 64 位 ARGB 像素数组。 |



**See also:**

**[Example # 1](#example_44)**: The following example shows how to load and process pixels of a raster image....


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

加载 CMYK 格式的像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 已加载的 CMYK 像素以 32 位整数值呈现。 |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | 已加载的 CMYK 像素数组。 |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

按包部分加载 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 32 位 ARGB 像素加载器。 |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

按包部分加载 64 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_65}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

按包部分加载像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | 像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_66}


```
 load_pixels(rectangle) 
```

加载像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 已加载的像素数组。 |



**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...

**[Example # 2](#example_45)**: The following example shows how to load and process pixels of a raster image....


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

加载原始数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于加载原始数据的矩形。 |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | 原始数据加载器。 |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

加载原始数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于加载原始数据的矩形。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | 原始数据加载器。 |

### Method: load_stream(stream)  [static] {#load_stream_stream_69}


```
 load_stream(stream) 
```

从指定的流加载新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_70}


```
 load_stream_with_options(stream, load_options) 
```

从指定的流加载新图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_71}


```
 load_with_options(file_path, load_options) 
```

从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 加载图像的文件路径或 URL。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | 已加载的图像。 |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_72}


```
 normalize_angle(resize_proportionally, background_color) 
```

归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |


**See also:**

**[Example # 1](#example_184)**: Skew is an artifact that might appear during document scanning process when t...


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_73}


```
 read_argb_32_scan_line(scan_line_index) 
```

按指定的扫描线索引读取整条扫描线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |

**Returns**

| Type | Description |
| :- | :- |
| int[] | 扫描线 32 位 ARGB 颜色值数组。 |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_74}


```
 read_scan_line(scan_line_index) 
```

按指定的扫描线索引读取整条扫描线。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | 扫描线像素颜色值数组。 |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_75}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| old_color_argb | int | 要替换的旧颜色 ARGB 值。 |
| old_color_diff | System.Byte | 允许的旧颜色差异，以便能够扩大替换颜色的色调。 |
| new_color_argb | int | 用于替换旧颜色的新颜色 ARGB 值。 |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_76}


```
 replace_color(old_color, old_color_diff, new_color) 
```

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | 要被替换的旧颜色。 |
| old_color_diff | System.Byte | 允许的旧颜色差异，以便能够扩大替换颜色的色调。 |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | 用于替换旧颜色的新颜色。 |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_77}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| old_color_argb | int | 要替换的旧颜色 ARGB 值。 |
| old_color_diff | System.Byte | 允许的旧颜色差异，以便能够扩大替换颜色的色调。 |
| new_color_argb | int | 用于替换旧颜色的新颜色 ARGB 值。 |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_78}


```
 replace_non_transparent_colors(new_color) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | 用于替换非透明颜色的新颜色。 |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_79}


```
 replace_non_transparent_colors(new_color_argb) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_argb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_80}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_81}


```
 resize(new_width, new_height, resize_type) 
```

调整图像大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小类型。 |


**See also:**

**[Example # 1](#example_61)**: This example loads a raster image and resizes it using various resizing methods.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_82}


```
 resize(new_width, new_height, settings) 
```

使用扩展选项调整图像大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 调整大小设置。 |


**See also:**

**[Example # 1](#example_62)**: This example loads a raster image and resizes it using various resizing setti...


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_83}


```
 resize_by_settings(new_width, new_height, settings) 
```

调整图像大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 调整大小设置。 |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_84}


```
 resize_by_type(new_width, new_height, resize_type) 
```

调整图像大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小类型。 |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_85}


```
 resize_height_proportionally(new_height) 
```

按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_86}


```
 resize_height_proportionally(new_height, resize_type) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_87}


```
 resize_height_proportionally(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_88}


```
 resize_height_proportionally_settings(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_89}


```
 resize_width_proportionally(new_width) 
```

按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_90}


```
 resize_width_proportionally(new_width, resize_type) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_91}


```
 resize_width_proportionally(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_92}


```
 resize_width_proportionally_settings(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: rotate(angle) {#rotate_angle_93}


```
 rotate(angle) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_94}


```
 rotate(angle, resize_proportionally, background_color) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_95}


```
 rotate_flip(rotate_flip_type) 
```

旋转、翻转或同时旋转和翻转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转的类型。 |

### Method: save(file_path) {#save_file_path_96}


```
 save(file_path) 
```

将图像保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存图像的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_97}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_98}


```
 save(file_path, options, bounds_rectangle) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_99}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，覆盖文件内容，否则将追加。 |

### Method: save(stream) {#save_stream_100}


```
 save(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save(stream, options_base) {#save_stream_options_base_101}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_102}


```
 save(stream, options_base, bounds_rectangle) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_103}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |


**See also:**

**[Example # 1](#example_46)**: The following example fills the central area of a raster image with black pix...


### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_104}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

保存像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 以 32 位整数值表示的 CMYK 像素。 |


**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_105}


```
 save_cmyk_pixels(rectangle, pixels) 
```

保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_106}


```
 save_pixels(rectangle, pixels) 
```

保存像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 像素数组。 |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...

**[Example # 2](#example_47)**: The following example fills the central area of a raster image with black pix...


### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_107}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

保存原始数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 数据 | System.Byte | 原始数据。 |
| data_offset | int | 起始原始数据偏移。 |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 原始数据矩形。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | 原始数据所在的设置。 |

### Method: save_to_stream(stream) {#save_to_stream_stream_108}


```
 save_to_stream(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_109}


```
 save_to_stream_with_options(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_111}


```
 save_with_options(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_112}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_113}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

为指定位置设置图像的 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |
| argb_32_color | int | 指定位置的 32 位 ARGB 像素。 |


**See also:**

**[Example # 1](#example_42)**: The following example loads a raster image, and sets the color of an arbitrar...


### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_114}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，未更改的索引如果在加载时没有对应的调色板条目，可能会导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_115}


```
 set_pixel(x, y, color) 
```

为指定位置设置图像像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| x | int | 像素的 x 位置。 |
| y | int | 像素的 y 位置。 |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | 指定位置的像素颜色。 |


**See also:**

**[Example # 1](#example_42)**: The following example loads a raster image, and sets the color of an arbitrar...


### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_116}


```
 set_resolution(dpi_x, dpi_y) 
```

为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dpi_x | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率。 |
| dpi_y | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率。 |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_117}


```
 try_set_metadata(metadata) 
```

尝试设置 _metadata_ 实例，如果此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 类型。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | 元数据。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 类型，则为 true；否则为 false。 |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int[] | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_119}


```
 write_scan_line(scan_line_index, pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 要写入的像素颜色数组。 |

## **Examples**
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# 创建 MemoryStream 的实例
with strm_ext.create_memory_stream() as stream:
	#创建 GifOptions 的实例并设置其各种属性，包括 Source 属性
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# 创建 Image 的实例
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# 通过将区域指定为图像边界来获取图像的像素
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#遍历数组并设置交替索引像素的颜色
			for index in range(pixel.length):
				if index % 2 == 0:
					#将索引像素颜色设置为黄色
					pixels[index] = yellow_color
				else:
					#将索引像素颜色设置为蓝色
					pixels[index] = blue_color

			#将像素更改应用于图像
			image.save_pixels(image.bounds, pixels)

			# 保存所有更改。
			image.save()

	# 将 MemoryStream 写入文件
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

### The following example shows how image caching affects performance. In general case, reading cached data is performed faster than reading non-cached data. {#example_36}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

# 从 PNG 文件加载图像。
with Image.load(path_join(directory, "sample.png")) as image:
	# 缓存所有像素数据，以便不会从底层数据流执行额外的数据加载
	image.cache_daata()

	start_time = timedelta()

	# 读取所有像素相当快。
	rasterImage = as_of(image, RasterImage)
	for y in range(image.height):
		for x in range(image.width):
			color = rasterImage.get_argb_32_pixel(x, y)
			
	end_time = timedelta()
	time = (end_time.microseconds - start_time.microseconds) / 1000000
	print(f"Reading all cached pixels took {time} ms.")


# 从 PNG 文件加载图像
with Image.load(path_join(directory, "sample.png")) as image:
	start_time = timedelta()

	# 读取所有像素的速度不如缓存时快
	rasterImage = as_of(image, RasterImage)
	for y in range(image.height):
		for x in range(image.width):
			color = rasterImage.get_argb_32_pixel(x, y)

	end_time = timedelta()
	time = (end_time.microseconds - start_time.microseconds) / 1000000
	print(f"Reading all pixels without preliminary caching took {time} ms.")

# 输出可能如下所示：
# 读取所有已缓存像素耗时 1500 毫秒。
# 在没有预先缓存的情况下读取所有像素耗时 150000 毫秒。


```

### The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form. {#example_37}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging.fileformats.png import PngColorType

image_width = 3
image_height = 2

colors = [
	Color.from_argb(127, 255, 0, 0),
	Color.from_argb(127, 0, 255, 0),
	Color.from_argb(127, 0, 0, 255),
	Color.from_argb(127, 255, 255, 0),
	Color.from_argb(127, 255, 0, 255),
	Color.from_argb(127, 0, 255, 255)
]

create_options = PngOptions()
create_options.source = StreamSource()
create_options.color_type = PngColorType.TRUECOLOR_WITH_ALPHA

with Image.create(create_options, image_width, image_height) as image:
	raster_image = as_of(image, RasterImage)

	# 保存整幅图像的像素。
	raster_image.save_pixels(raster_image.bounds, colors)

	# 像素以非预乘形式存储在原始图像中。
	# 需要显式指定相应选项以获取预乘颜色分量。
	# 预乘颜色分量通过以下公式计算：
	# red = original_red * alpha / 255;
	# green = original_green * alpha / 255;
	# blue = original_blue * alpha / 255;
	raster_image.premultiply_components = True
	premultiplied_colors = raster_image.load_pixels(raster_image.bounds)
	for i in range(len(colors)):
		print(f"Original color: {colors[i]}")
		print(f"Premultiplied color: {premultiplied_colors[i]}")


```

### The following example loads raster images and prints information about raw data format and alpha channel. {#example_38}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

# 要加载的图像文件。
fileNames = (r"c:\temp\sample.bmp", r"c:\temp\alpha.png")

for fileName in fileNames:
	with Image.load(fileName) as image:
		raster_image = as_of(image, RasterImage)
		print(f"ImageFile={fileName}, FileFormat={raster_image.raw_data_format}, HasAlpha={raster_image.has_alpha}")

# 输出可能如下所示：
# ImageFile=c:\temp\sample.bmp, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
# ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True

```

### The following example loads a raster image and performs threshold and Floyd dithering using different palette depth. {#example_39}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, DitheringMethod
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用包含 16 种颜色的 4 位颜色调色板执行阈值抖动。
	# 指定的位数越多，输出图像的质量越高且尺寸越大。
	# 请注意，目前仅支持 1 位、4 位和 8 位调色板。
	rasterImage.dither(DitheringMethod.THRESHOLD_DITHERING, 4)

	rasterImage.save(join_path(directory, "sample.ThresholdDithering4.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)

	# 使用仅包含 2 种颜色（黑色和白色）的 1 位颜色调色板执行 Floyd 抖动。
	# 指定的位数越多，输出图像的质量越高且尺寸越大。
	# 请注意，目前仅支持 1 位、4 位和 8 位调色板。
	rasterImage.dither(DitheringMethod.FLOYD_STEINBERG_DITHERING, 1)
	rasterImage.save(join_path(directory, "sample.FloydSteinbergDithering1.png"))


```

### The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value. {#example_40}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)

	# 获取图像左上像素颜色的整数表示。
	color = rasterImage.get_argb_32_pixel(0, 0)

	# 要获取各个颜色分量的值，需要将颜色值按相应的位数进行移位
	alpha = (color >> 24) & 0xff
	red = (color >> 16) & 0xff
	green = (color >> 8) & 0xff
	blue = (color >> 0) & 0xff

	print(f"The color of the pixel(0,0) is A={alpha},R={red},G={green},B={blue}")


```

### The following example loads a raster image and obtains the color of an arbitrary pixel. {#example_41}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)
	# 获取图像左上像素的颜色。
	color = rasterImage.get_pixel(0, 0)

	# 获取各个颜色分量的值
	alpha = color.a
	red = color.r
	green = color.g
	blue = color.b

	print(f"The color of the pixel(0,0) is A={alpha},R={red},G={green},B={blue}")


```

### The following example loads a raster image, and sets the color of an arbitrary pixel. {#example_42}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)
	# 设置左上像素的颜色。
	rasterImage.set_argb_32_pixel(0, 0, Color.aqua.to_argb())
	# 另一种方法是直接传递 aspose.imaging.Color 的实例
	rasterImage.set_pixel(0, 0, Color.aqua)


```

### The following example shows how to load and process pixels of a raster image. The pixels are represented as 32-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image. {#example_43}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("alpha.png") as image:
	rasterImage = as_of(image, RasterImage)

	# 加载整幅图像的像素。图像的任意矩形部分都可以作为参数传递给 aspose.imaging.RasterImage.load_argb_32_pixels(rectangle) 方法。
	pixels = rasterImage.load_argb_32_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		alpha = (pixel >> 24) & 0xff
		if alpha == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example shows how to load and process pixels of a raster image. The pixels are represented as 64-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image. {#example_44}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("16rgba.png") as image:
	rasterImage = as_of(image, RasterImage)
	# 加载整幅图像的像素。图像的任意矩形部分都可以作为参数传递给 aspose.imaging.RasterImage.load_argb_64_pixels 方法。
	# 请注意，图像本身必须每个样本为 16 位，因为 aspose.imaging.RasterImage.load_argb_64_pixels 不支持每个样本为 8 位。
	# 为了使用每个样本为 8 位，请使用老牌的 aspose.imaging.RasterImage.load_argb_64_pixels 方法。
	pixels = rasterImage.load_argb_64_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		# 请注意，所有颜色分量（包括 alpha）均以 16 位值表示，因此其允许的取值范围为 [0, 63535]。
		alpha = (pixel >> 48) & 0xffff
		if alpha == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example shows how to load and process pixels of a raster image. For example, consider a problem of counting of fully transparent pixels of an image. {#example_45}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("alpha.png") as image:
	rasterImage = as_of(image, RasterImage)
	# 加载整幅图像的像素。图像的任意矩形部分都可以作为参数传递给 aspose.imaging.RasterImage.load_pixels 方法。
	pixels = rasterImage.load_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		if pixel.a == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_argb_32_pixels method. {#example_46}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 黑色方块
	pixel_count = ((rasterImage.width // 2) * (rasterImage.height // 2))
	black_color = Color.black.to_argb()
	pixels = [black_color] * pixel_count

	# 在图像中心绘制黑色方块。
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_argb_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveArgb32Pixels.png"))


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_pixels method. {#example_47}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 黑色方块
	pixel_count = ((rasterImage.width // 2) * (rasterImage.height // 2))
	black_color = Color.black
	pixels = [black_color] * pixel_count

	# 在图像中心绘制黑色方块。
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SavePixels.png"))


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 获取 CMYK 颜色空间中黑色的整数表示。
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# 黑色方块。
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# 在图像中心绘制黑色方块。
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_cmyk_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveCmyk32Pixels.png"))


```

### The following example crops a raster image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_49}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 裁剪图像。裁剪区域是图像的矩形中心区域。
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.crop(area)
	# 将裁剪后的图像保存为 PNG。
	rasterImage.save(join_path(directory, "sample.Crop.png"))


```

### The following example crops a raster image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_50}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 再次裁剪。设置图像大小的10%边距。
	horizontalMargin = rasterImage.width // 10
	verticalMargin = rasterImage.height // 10
	rasterImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin)
	# 将裁剪后的图像保存为 PNG。
	rasterImage.save(join_path(directory, "sample.Crop.png"))


```

### The following example binarizes a raster image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_51}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用阈值127对图像进行二值化。
	# 如果像素的对应灰度值大于127，则赋值为255，否则为0。
	rasterImage.binarize_fixed(127)
	rasterImage.save(join_path(directory, "sample.BinarizeFixed.png"))


```

### The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_53}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用亮度差5对图像进行二值化。亮度是指像素与以该像素为中心的10×10窗口像素平均值之间的差异。
	rasterImage.binarize_bradley(5, 10)
	rasterImage.save(join_path(directory, "sample.BinarizeBradley5_10x10.png"))


```

### The following example performs gamma-correction of an image. {#example_55}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 设置红、绿、蓝通道的伽马系数。
	rasterImage.adjust_gamma(2.5f)
	rasterImage.save(join_path(directory, "sample.AdjustGamma.png"))


```

### The following example performs gamma-correction of an image applying different coefficients for color components. {#example_56}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 设置红、绿、蓝通道的伽马系数。
	rasterImage.adjust_gamma(1.5f, 2.5f, 3.5f)
	rasterImage.save(join_path(directory, "sample.AdjustGamma.png"))


```

### The following example performs brightness correction of an image. {#example_57}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 设置亮度值。亮度的可接受范围为 [-255, 255]。
	rasterImage.adjust_brightness(50)
	rasterImage.save(join_path(directory, "sample.AdjustBrightness.png"))


```

### The following example performs contrast correction of an image. {#example_58}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
	rasterImage.adjust_contrast(50)
	rasterImage.save(join_path(directory, "sample.AdjustContrast.png"))


```

### The following example applies various types of filters to a raster image. {#example_59}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.imagefilters.filteroptions import *
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用矩形大小为 5 的中值滤波器。
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用核大小为 5 的双边平滑滤波器。
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用半径为 5、sigma 值为 4.0 的高斯模糊滤波器。
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# 对整幅图像应用核大小为 5、sigma 值为 4.0 的锐化滤波器。
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

### This example loads a raster image and resizes it using various resizing methods. {#example_61}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, ResizeType
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用最近邻重采样将尺寸放大 2 倍。
	rasterImage.resize(image.width * 2, image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(join_path(directory, "upsample.nearestneighbour.gif"))

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用最近邻重采样将尺寸缩小 2 倍。
	rasterImage.resize(image.width // 2, image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE);
	image.Save(dir + "downsample.nearestneighbour.gif");

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用双线性重采样将尺寸放大 2 倍。
	rasterImage.resize(image.width * 2, image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(join_path(directory, "upsample.bilinear.gif"))

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用双线性重采样将尺寸缩小 2 倍。
	rasterImage.resize(image.width // 2, image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.Save(dir + "downsample.bilinear.gif");


```

### This example loads a raster image and resizes it using various resizing settings. {#example_62}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, ImageResizeSettings, ResizeType,\
	ImageFilterType, ColorQuantizationMethod, ColorCompareMethod
from os.path import join as join_path

directory = r"c:\temp"

resizeSettings = ImageResizeSettings()
# 基于加权混合有理函数和 lanczos3 插值的自适应算法。
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# 小矩形滤波器
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# 调色板中的颜色数量。
resizeSettings.entries_count = 256
# 未使用颜色量化
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE
# 欧几里得方法
resizeSettings.color_compare_method = ColorCompareMethod.EUCLIDIAN

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# 使用自适应重采样将尺寸缩小 2 倍。
	rasterImage.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(join_path(directory, "downsample.adaptive.gif"))


```

### The following example shows how to extract information about raw data format and alpha channel from a BMP image. {#example_86}
``` python
from aspose.imaging.fileformats.bmp import BmpImage

# 创建一个 100 x 100 像素、32 位 BMP 图像。
with BmpImage(100, 100, 32, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))


# 创建一个 100 x 100 像素、24 位 BMP 图像。
with BmpImage(100, 100, 24, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))

# 通常，BMP 不支持 alpha 通道，因此输出将如下所示：
# FileFormat = BMP, RawDataFormat = Rgb32Bpp, 使用的通道: 8,8,8,8, HasAlpha = False
# FileFormat = BMP, RawDataFormat = Rgb24Bpp, 使用的通道: 8,8,8, HasAlpha = False

```

### Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle. It can have various causes but the most common is that the paper get misplaced during a scan. Therefore, deskew is the process of detecting and fixing this issue on scanned files(i.e. bitmap) so deskewed documents will have the text/images correctly and horizontally adjusted. {#example_184}
``` python
from aspose.imaging import Image, RasterImage, Color
from aspose.pycore import as_of

dir_: str = "c:\\3567\\"
input_file_path: str = dir_ + "skewed.png"
output_file_path: str = dir_ + "skewed.out.png"
# 使用默认参数去除倾斜扫描
with as_of(Image.load(input_file_path), RasterImage) as image:
	# 去倾斜
	image.normalize_angle(False, Color.light_gray)
	image.save(output_file_path)


```

### The example shows how to validate that the embedded digital signature matches the provided password. {#example_231}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, -1)


```

### The example shows how to embed digital signature based on provided password into image pixel data. {#example_232}
``` python

from aspose.imaging import Image

image_file_path = "ball.png"
password = "veryStr0ngPassword"
with Image.load(image_file_path) as image:
	image.embed_digital_signature(password)
	image.save(output_path)


```

### The example demonstrates how to verify that the embedded digital signature matches the provided password against the specified probability threshold. {#example_233}
``` python

from aspose.imaging import Image
  
threshold = 100
with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, threshold)


```

### The example illustrates how to determine the probability (from 0% to 100%) that an image contains a digital signature created with the specified password. {#example_234}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	signed_percentage = image.analyze_percentage_digital_signature(password)


```

