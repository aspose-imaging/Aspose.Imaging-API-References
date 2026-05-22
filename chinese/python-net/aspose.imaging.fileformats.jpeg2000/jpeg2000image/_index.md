---
title: "Jpeg2000Image 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---

**Summary:** Efficiently manipulate JPEG2000 (JP2) image files with our API, supporting<br/>            a range of bits per pixel depths and seamless processing of XMP metadata<br/>            containing essential image information. With capabilities for lossless compression,<br/>            ensure optimal image quality while maintaining file integrity, empowering you to<br/>            tailor JP2 images to your exact specifications with ease.

**Module:** [aspose.imaging.fileformats.jpeg2000](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/)

**Full Name:** aspose.imaging.fileformats.jpeg2000.Jpeg2000Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Jpeg2000Image(image)](#Jpeg2000Image_image_1) | 实例化一个新的 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类，使用光栅图像。此 <br/> 构造函数可帮助从现有光栅 <br/> 图像创建 JPEG2000 图像，提供不同图像格式之间的无缝集成和转换。 |
| [Jpeg2000Image(path)](#Jpeg2000Image_path_2) | 通过使用要加载的图像路径初始化一个新的 <br/> 实例，开始使用 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类。此构造函数实现了对 JPEG2000 图像的轻松 <br/> 访问，简化了加载和处理图像 <br/> 文件的过程。提供文件路径后，您可以快速开始在应用程序中处理和 <br/> 操作 JPEG2000 图像。 |
| [Jpeg2000Image(path, bits_per_pixel)](#Jpeg2000Image_path_bits_per_pixel_3) | 通过创建一个同时包含文件路径和所需每像素位数参数的新 <br/> 实例，轻松开始使用 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类。此 <br/> 构造函数允许对图像加载过程进行微调，确保 <br/> 与各种图像格式和质量设置兼容。凭借此 <br/> 灵活性，您可以高效地管理和操作 JPEG2000 图像，以满足 <br/> 您的特定需求。 |
| [Jpeg2000Image(raster_image, bits_per_pixel)](#Jpeg2000Image_raster_image_bits_per_pixel_4) | 使用光栅图像和 <br/> 每像素位数参数初始化一个全新的 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 实例。此构造函数实现对 <br/> 生成的 JPEG2000 图像的质量和尺寸的精确控制，适用于定制至关重要的场景。 |
| [Jpeg2000Image(stream)](#Jpeg2000Image_stream_5) | 通过 <br/> 提供流对象，轻松初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。此构造函数简化了直接从流加载 <br/> JPEG2000 图像的过程，为处理来自各种来源的图像数据提供了灵活性和便利性。 |
| [Jpeg2000Image(stream, bits_per_pixel)](#Jpeg2000Image_stream_bits_per_pixel_6) | 使用流来 <br/> 加载图像，并提供每像素位数参数，初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。此构造函数通过允许您同时指定图像数据源和所需的 <br/> 每像素位数，提供了灵活性，从而对图像加载过程实现更精细的控制。 |
| [Jpeg2000Image(width, height)](#Jpeg2000Image_width_height_7) | 创建 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例，指定 <br/> 宽度和高度参数。此构造函数允许您使用特定尺寸初始化 JPEG2000 <br/> 图像，适用于需要以编程方式创建特定大小图像的场景。 |
| [Jpeg2000Image(width, height, bits_count)](#Jpeg2000Image_width_height_bits_count_8) | 使用宽度、高度和位数参数创建 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。此构造函数支持创建具有特定尺寸和位深的 JPEG2000 <br/> 图像，为各种成像需求提供了灵活性。 |
| [Jpeg2000Image(width, height, options)](#Jpeg2000Image_width_height_options_9) | 实例化一个新的 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 对象，提供宽度、高度、<br/> 和图像选项参数。此构造函数可用于创建具有特定尺寸和附加选项的 JPEG2000 <br/> 图像，在图像生成方面提供了灵活性。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | 获取或设置一个值，指示是否自动调整调色板。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色的值。 |
| bits_per_pixel | int | r | 此属性返回图像的深度，以每像素位数 (bpp) 为单位。它 <br/> 表示存储在图像每个像素中的颜色信息量。了解图像深度对于确定颜色保真度和 <br/> 图像质量至关重要。凭借此信息，用户可以评估图像中细节水平和颜色丰富度。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取对象的边界。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| codec | [Jpeg2000Codec](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000codec/) | r | 此属性获取与图像关联的 JPEG2000 编解码器。JPEG2000 <br/> 编解码器负责对 JPEG2000 格式的图像数据进行编码和解码，提供高效压缩并保持高图像质量。<br/> 访问此编解码器可用于执行高级图像处理 <br/> 操作或针对特定需求优化图像压缩设置。 |
| 注释 | string[] | r/w | 此属性允许检索或更新与图像关联的评论。评论提供关于图像内容的额外信息，如 <br/> 注释、描述或元数据。修改这些评论有助于 <br/> 对图像进行组织和分类，并向查看者或用户传达重要细节。 |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取 [Image](/imaging/python-net/aspose.imaging/image/) 容器。 |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | 获取对象的数据流。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 实例。 |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 检索图像文件的格式。此属性提供有关图像文件格式的信息。利用此属性可编程地确定 <br/> 图像文件的格式，从而根据文件格式进行适当的处理和操作。 |
| has_alpha | bool | r | 获取指示此实例是否具有 alpha 的值。 |
| has_background_color | bool | r/w | 获取或设置指示图像是否具有背景颜色的值。 |
| has_transparent_color | bool | r/w | 获取或设置指示此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例是否具有透明颜色的值。 |
| height | int | r | 此属性检索图像的像素高度。它是了解图像垂直尺寸的关键 <br/> 信息，有助于诸如调整大小、裁剪和渲染等各种图像处理任务。访问此 <br/> 属性可让用户确定图像的垂直尺寸，从而在应用程序中实现精确的 <br/> 布局和显示。 |
| horizontal_resolution | float | r/w | 此属性允许您检索或修改 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率，单位为每英寸像素数 (PPI)。调整此 <br/> 分辨率会影响图像在打印或显示时的尺寸和质量。通过设置水平分辨率，用户可以针对特定 <br/> 输出设备或应用程序优化图像，确保获得最佳的视觉效果。 |
| image_opacity | float | r | 获取此图像的不透明度。 |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取指示图像数据当前是否已缓存的值。 |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | 获取图像元数据。 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| premultiply_components | bool | r/w | 获取或设置一个值，指示图像组件是否必须进行预乘。 |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | 获取或设置自定义颜色转换器 |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 此属性检索图像的原始数据格式。它提供关于像素数据在内存中存储方式的信息。使用此属性可了解 <br/> 图像的底层数据格式，这对于颜色转换、压缩或解压缩等各种图像 <br/> 处理操作至关重要。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | 获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | r/w | 获取或设置当调色板索引超出范围时使用的回退索引 |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | 获取或设置索引颜色转换器 |
| raw_line_size | int | r | 此属性检索原始图像数据单行的字节大小。它 <br/> 表示图像原始数据格式中单行像素占用的内存量。了解原始行大小对于内存分配、数据操作以及针对 <br/> 单独图像行进行处理的图像算法等任务至关重要。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | 获取对象大小。 |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取图像的透明颜色。 |
| update_xmp_data | bool | r/w | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| use_palette | bool | r | 获取一个值，指示是否使用图像调色板。 |
| use_raw_data | bool | r/w | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| vertical_resolution | float | r/w | 此属性提供对 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率的访问，单位为每英寸像素数 (PPI)。修改此 <br/> 分辨率会影响图像在打印或显示时的质量和尺寸。通过调整垂直分辨率，用户可以针对不同 <br/> 输出设备或应用程序优化图像，确保最佳的视觉呈现。 |
| width | int | r | 此属性返回图像的像素宽度。它提供关于图像尺寸的基本 <br/> 信息，对包括调整大小、裁剪和渲染在内的各种图像 <br/> 处理任务至关重要。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 Xmp 数据。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | 调整图像的亮度。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | 图像对比 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | 图像的伽马校正。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | 图像的伽马校正。 |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | 计算提取数据与原始密码之间的相似度百分比。 |
| auto_brightness_contrast() | 对整个图像执行自动自适应亮度和对比度归一化。 |
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
| [create_from_file_with_bpp(path, bits_per_pixel)](#create_from_file_with_bpp_path_bits_per_pixel_26) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_from_files(files)](#create_from_files_files_27) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_image(image)](#create_from_image_image_29) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_from_image_with_bpp(raster_image, bits_per_pixel)](#create_from_image_with_bpp_raster_image_bits_per_pixel_30) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_from_images(images)](#create_from_images_images_31) | 使用指定的图像作为页面创建新图像。 |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | 创建一个新图像，将指定的图像作为页面。 |
| [create_from_stream(stream)](#create_from_stream_stream_33) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_from_stream_with_bpp(stream, bits_per_pixel)](#create_from_stream_with_bpp_stream_bits_per_pixel_34) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_with_width_height(width, height)](#create_with_width_height_width_height_35) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_with_width_height_bitscount(width, height, bits_count)](#create_with_width_height_bitscount_width_height_bits_count_36) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [create_with_width_height_options(width, height, options)](#create_with_width_height_options_width_height_options_37) | 初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。 |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_38) | 使用位移裁剪图像。 |
| [crop(rectangle)](#crop_rectangle_39) | 裁剪图像。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_40) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_41) | 对当前图像执行抖动处理。 |
| [embed_digital_signature(password)](#embed_digital_signature_password_42) | 使用隐写术将基于提供的密码的数字签名嵌入图像中。 |
| [filter(rectangle, options)](#filter_rectangle_options_43) | 过滤指定的矩形区域。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_44) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_45) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_46) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_47) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_48) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_49) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_50) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_51) | 获取文件格式。 |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_52) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_53) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_54) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_55) | 获取资源图像最后修改的日期和时间。 |
| [get_original_options()](#get_original_options__56) | 根据原始文件设置检索图像选项。此方法 <br/> 有助于保持原始图像的位深度和其他参数，确保一致性并保留图像数据的完整性。<br/> 访问这些选项可实现对图像的无缝处理和操作，同时保留其原始特性。<br/> 例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/> [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，输出的 PNG 图像将是每像素 8 位。<br/> 为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将其<br/> 传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法的第二个参数。 |
| [get_pixel(x, y)](#get_pixel_x_y_57) | 获取图像像素。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_58) | 获取比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_59) | 获取比例宽度。 |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_60) | 转换为 aps。 |
| [get_skew_angle()](#get_skew_angle__61) | 获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。 |
| grayscale() | 将图像转换为灰度表示 |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | 使用提供的密码和阈值执行快速检查，以确定图像是否已数字签名。 |
| [load(file_path)](#load_file_path_63) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(file_path, load_options)](#load_file_path_load_options_64) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(stream)](#load_stream_65) | 从指定的流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_66) | 从指定的流加载新图像。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_67) | 加载 32 位 ARGB 像素。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_68) | 加载 64 位 ARGB 像素。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_69) | 加载 CMYK 格式的像素。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_70) | 加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71) | 部分加载 32 位 ARGB 像素（按块）。 |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72) | 按包部分加载 64 位 ARGB 像素。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_73) | 按包部分加载像素。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_74) | 加载像素。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75) | 加载原始数据。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76) | 加载原始数据。 |
| [load_stream(stream)](#load_stream_stream_77) | 从指定的流加载新图像。 |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_78) | 从指定的流加载新图像。 |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_79) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| normalize_angle() | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| normalize_histogram() | 归一化图像直方图 — 调整像素值以使用全部可用范围。 |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | 按指定的扫描线索引读取整条扫描线。 |
| remove_metadata() | 通过将此 [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) 值设置为 **None** 来移除此图像实例的元数据。 |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_83) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_84) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_85) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_86) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_87) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_88) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_89) | 调整图像大小。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_90) | 调整图像大小。 |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_91) | 调整图像大小。 |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_92) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_93) | 按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_94) | 按比例调整高度。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_95) | 按比例调整高度。 |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_96) | 按比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_97) | 按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_98) | 按比例调整宽度。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_99) | 按比例调整宽度。 |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_100) | 按比例调整宽度。 |
| [rotate(angle)](#rotate_angle_101) | 围绕中心旋转图像。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_102) | 围绕中心旋转图像。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_103) | 旋转、翻转或同时旋转和翻转图像。 |
| save() | 将图像数据保存到底层流中。 |
| [save(file_path)](#save_file_path_104) | 将图像保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_105) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_106) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, over_write)](#save_file_path_over_write_107) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_108) | 将对象的数据保存到指定的流中 |
| [save(stream, options_base)](#save_stream_options_base_109) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_110) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_111) | 保存 32 位 ARGB 像素。 |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_112) | 保存像素。 |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_113) | 保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_114) | 保存像素（特定格式方法）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_115) | 保存原始数据。 |
| [save_to_stream(stream)](#save_to_stream_stream_116) | 将对象的数据保存到指定的流中。 |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_117) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_118) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_119) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_120) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_121) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_122) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_123) | 为指定位置设置图像像素。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_124) | 为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_125) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_127) | 将整条扫描线写入指定的扫描线索引。 |


### Constructor: Jpeg2000Image(image) {#Jpeg2000Image_image_1}


```
 Jpeg2000Image(image) 
```

实例化一个新的 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类，使用光栅图像。此 <br/> 构造函数可帮助从现有光栅 <br/> 图像创建 JPEG2000 图像，提供不同图像格式之间的无缝集成和转换。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 图像。 |

### Constructor: Jpeg2000Image(path) {#Jpeg2000Image_path_2}


```
 Jpeg2000Image(path) 
```

通过使用要加载的图像路径初始化一个新的 <br/> 实例，开始使用 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类。此构造函数实现了对 JPEG2000 图像的轻松 <br/> 访问，简化了加载和处理图像 <br/> 文件的过程。提供文件路径后，您可以快速开始在应用程序中处理和 <br/> 操作 JPEG2000 图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | 用于加载图像并初始化像素和调色板数据的路径。 |


**See also:**

**[Example # 1](#example_158)**: This example shows how to load a JPEG2000 image from a file and save it to PNG.


### Constructor: Jpeg2000Image(path, bits_per_pixel) {#Jpeg2000Image_path_bits_per_pixel_3}


```
 Jpeg2000Image(path, bits_per_pixel) 
```

通过创建一个同时包含文件路径和所需每像素位数参数的新 <br/> 实例，轻松开始使用 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类。此 <br/> 构造函数允许对图像加载过程进行微调，确保 <br/> 与各种图像格式和质量设置兼容。凭借此 <br/> 灵活性，您可以高效地管理和操作 JPEG2000 图像，以满足 <br/> 您的特定需求。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | 用于加载图像并初始化像素和调色板数据的路径 |
| bits_per_pixel | int | 每像素位数。 |

### Constructor: Jpeg2000Image(raster_image, bits_per_pixel) {#Jpeg2000Image_raster_image_bits_per_pixel_4}


```
 Jpeg2000Image(raster_image, bits_per_pixel) 
```

使用光栅图像和 <br/> 每像素位数参数初始化一个全新的 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 实例。此构造函数实现对 <br/> 生成的 JPEG2000 图像的质量和尺寸的精确控制，适用于定制至关重要的场景。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 用于初始化像素和调色板数据的图像。 |
| bits_per_pixel | int | 每像素位数。 |

### Constructor: Jpeg2000Image(stream) {#Jpeg2000Image_stream_5}


```
 Jpeg2000Image(stream) 
```

通过 <br/> 提供流对象，轻松初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。此构造函数简化了直接从流加载 <br/> JPEG2000 图像的过程，为处理来自各种来源的图像数据提供了灵活性和便利性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于加载图像并初始化像素和调色板数据的流。 |


**See also:**

**[Example # 1](#example_159)**: This example shows how to load a JPEG2000 image from a file stream and save i...


### Constructor: Jpeg2000Image(stream, bits_per_pixel) {#Jpeg2000Image_stream_bits_per_pixel_6}


```
 Jpeg2000Image(stream, bits_per_pixel) 
```

使用流来 <br/> 加载图像，并提供每像素位数参数，初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。此构造函数通过允许您同时指定图像数据源和所需的 <br/> 每像素位数，提供了灵活性，从而对图像加载过程实现更精细的控制。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于加载图像并初始化像素和调色板数据的流。 |
| bits_per_pixel | int | 每像素位数。 |

### Constructor: Jpeg2000Image(width, height) {#Jpeg2000Image_width_height_7}


```
 Jpeg2000Image(width, height) 
```

创建 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例，指定 <br/> 宽度和高度参数。此构造函数允许您使用特定尺寸初始化 JPEG2000 <br/> 图像，适用于需要以编程方式创建特定大小图像的场景。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度 |


**See also:**

**[Example # 1](#example_160)**: This example shows how to create a JPEG2000 image and save it to a file.


### Constructor: Jpeg2000Image(width, height, bits_count) {#Jpeg2000Image_width_height_bits_count_8}


```
 Jpeg2000Image(width, height, bits_count) 
```

使用宽度、高度和位数参数创建 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。此构造函数支持创建具有特定尺寸和位深的 JPEG2000 <br/> 图像，为各种成像需求提供了灵活性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度 |
| bits_count | int | 位计数。 |

### Constructor: Jpeg2000Image(width, height, options) {#Jpeg2000Image_width_height_options_9}


```
 Jpeg2000Image(width, height, options) 
```

实例化一个新的 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 对象，提供宽度、高度、<br/> 和图像选项参数。此构造函数可用于创建具有特定尺寸和附加选项的 JPEG2000 <br/> 图像，在图像生成方面提供了灵活性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度 |
| options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | 选项。 |


**See also:**

**[Example # 1](#example_161)**: This example shows how to create a JPEG2000 image with the desired options an...

**[Example # 2](#example_163)**: This example shows how to create a PNG image and save it to JPEG2000 with the...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

调整图像的亮度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 亮度 | int | 亮度值。 |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

图像对比

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

图像的伽马校正。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |

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

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

使用预定义阈值对图像进行二值化

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 阈值 | System.Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为 255，否则为 0。 |

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


### Method: create_from_file_with_bpp(path, bits_per_pixel)  [static] {#create_from_file_with_bpp_path_bits_per_pixel_26}


```
 create_from_file_with_bpp(path, bits_per_pixel) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | 用于加载图像并初始化像素和调色板数据的路径 |
| bits_per_pixel | int | 每像素位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


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


### Method: create_from_image(image)  [static] {#create_from_image_image_29}


```
 create_from_image(image) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_image_with_bpp(raster_image, bits_per_pixel)  [static] {#create_from_image_with_bpp_raster_image_bits_per_pixel_30}


```
 create_from_image_with_bpp(raster_image, bits_per_pixel) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 用于初始化像素和调色板数据的图像。 |
| bits_per_pixel | int | 每像素位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于加载图像并初始化像素和调色板数据的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_from_stream_with_bpp(stream, bits_per_pixel)  [static] {#create_from_stream_with_bpp_stream_bits_per_pixel_34}


```
 create_from_stream_with_bpp(stream, bits_per_pixel) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于加载图像并初始化像素和调色板数据的流。 |
| bits_per_pixel | int | 每像素位数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_with_width_height(width, height)  [static] {#create_with_width_height_width_height_35}


```
 create_with_width_height(width, height) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_with_width_height_bitscount(width, height, bits_count)  [static] {#create_with_width_height_bitscount_width_height_bits_count_36}


```
 create_with_width_height_bitscount(width, height, bits_count) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度 |
| bits_count | int | 位计数。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: create_with_width_height_options(width, height, options)  [static] {#create_with_width_height_options_width_height_options_37}


```
 create_with_width_height_options(width, height, options) 
```

初始化 [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度 |
| options | [Jpeg2000Options](/imaging/python-net/aspose.imaging.imageoptions/jpeg2000options/) | 选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [Jpeg2000Image](/imaging/python-net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_38}


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

### Method: crop(rectangle) {#crop_rectangle_39}


```
 crop(rectangle) 
```

裁剪图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_40}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_41}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_42}


```
 embed_digital_signature(password) 
```

使用隐写术将基于提供的密码的数字签名嵌入图像中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于生成数字签名数据的密码 |

### Method: filter(rectangle, options) {#filter_rectangle_options_43}


```
 filter(rectangle, options) 
```

过滤指定的矩形区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | 选项。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_44}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_45}


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


### Method: get_default_options(args) {#get_default_options_args_46}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_47}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_48}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_49}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_50}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_51}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_52}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_53}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_54}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_55}


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


### Method: get_original_options() {#get_original_options__56}


```
 get_original_options() 
```

根据原始文件设置检索图像选项。此方法 <br/> 有助于保持原始图像的位深度和其他参数，确保一致性并保留图像数据的完整性。<br/> 访问这些选项可实现对图像的无缝处理和操作，同时保留其原始特性。<br/> 例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/> [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，输出的 PNG 图像将是每像素 8 位。<br/> 为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将其<br/> 传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法的第二个参数。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_57}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_58}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_59}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_60}


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


### Method: get_skew_angle() {#get_skew_angle__61}


```
 get_skew_angle() 
```

获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。

**Returns**

| Type | Description |
| :- | :- |
| float | 倾斜角度（单位：度）。 |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_62}


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


### Method: load(file_path)  [static] {#load_file_path_63}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_64}


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


### Method: load(stream)  [static] {#load_stream_65}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_66}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_67}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_68}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_69}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_70}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

部分加载 32 位 ARGB 像素（按块）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

按包部分加载 64 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_73}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

按包部分加载像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | 像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_74}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_77}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_78}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_79}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_80}


```
 normalize_angle(resize_proportionally, background_color) 
```

归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_81}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_82}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_83}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_84}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_85}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_86}


```
 replace_non_transparent_colors(new_color) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | 用于替换非透明颜色的新颜色。 |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_87}


```
 replace_non_transparent_colors(new_color_argb) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_argb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_88}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_89}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_90}


```
 resize(new_width, new_height, settings) 
```

调整图像大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 调整大小设置。 |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_91}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_92}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_93}


```
 resize_height_proportionally(new_height) 
```

按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_94}


```
 resize_height_proportionally(new_height, resize_type) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_95}


```
 resize_height_proportionally(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_96}


```
 resize_height_proportionally_settings(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_97}


```
 resize_width_proportionally(new_width) 
```

按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_98}


```
 resize_width_proportionally(new_width, resize_type) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_99}


```
 resize_width_proportionally(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_100}


```
 resize_width_proportionally_settings(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: rotate(angle) {#rotate_angle_101}


```
 rotate(angle) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_102}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_103}


```
 rotate_flip(rotate_flip_type) 
```

旋转、翻转或同时旋转和翻转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转类型。 |

### Method: save(file_path) {#save_file_path_104}


```
 save(file_path) 
```

将图像保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存图像的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_105}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_106}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_107}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，覆盖文件内容，否则将追加。 |

### Method: save(stream) {#save_stream_108}


```
 save(stream) 
```

将对象的数据保存到指定的流中

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流 |

### Method: save(stream, options_base) {#save_stream_options_base_109}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_110}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_111}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_112}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

保存像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 以 32 位整数值表示的 CMYK 像素。 |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_113}


```
 save_cmyk_pixels(rectangle, pixels) 
```

保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_114}


```
 save_pixels(rectangle, pixels) 
```

保存像素（特定格式方法）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 32 位 ARGB 像素数组。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_115}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_116}


```
 save_to_stream(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_117}


```
 save_to_stream_with_options(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_118}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_119}


```
 save_with_options(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_120}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_121}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_122}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，未更改的索引如果在加载时没有对应的调色板条目，可能会导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_123}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_124}


```
 set_resolution(dpi_x, dpi_y) 
```

为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dpi_x | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率。 |
| dpi_y | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率。 |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_125}


```
 try_set_metadata(metadata) 
```

尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | 元数据。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 如果 _metadata_ 不为 null 且 [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) 实例 <br/>            支持和/或实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例，则为 true；否则为 false。 |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int[] | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_127}


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
### This example shows how to load a JPEG2000 image from a file and save it to PNG. {#example_158}
``` python
import aspose.pycore as aspycore
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# 加载 JPEG2000 图像。
with Jpeg2000Image(join(dir_, "sample.jp2")) as jpeg2000_image:
	# 保存为 PNG
	jpeg2000_image.save(join(dir_, "sample.output.png"), PngOptions())


```

### This example shows how to load a JPEG2000 image from a file stream and save it to PNG. {#example_159}
``` python
import aspose.pycore as aspycore
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# 从流中加载 JPEG2000 图像。
with open(join(dir_, "sample.jp2"), "rb") as stream:
	with Jpeg2000Image(stream) as jpeg2000_image:
		# 保存为 PNG
		jpeg2000_image.save(join(dir_, "sample.output.png"), PngOptions())


```

### This example shows how to create a JPEG2000 image and save it to a file. {#example_160}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Image
from aspose.imaging.imageoptions import Jpeg2000Options
from os.path import join

dir_: str = "c:\\temp"
# 创建 100x100 像素的 JPEG2000 图像。
with Jpeg2000Image(100, 100) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# 保存到文件
	jpeg2000_image.save(join(dir_, "sample.output.jp2"), Jpeg2000Options())


```

### This example shows how to create a JPEG2000 image with the desired options and save it to a file. {#example_161}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Jpeg2000Image
from os.path import join as path_join     


dir_ = "c:\\temp"
create_options = Jpeg2000Options()
# 使用不可逆离散小波变换 9-7
create_options.irreversible = True
# JP2 是 JPEG 2000 码流的“容器”格式。
# J2K 是未包装的原始压缩数据。
create_options.codec = Jpeg2000Codec.J2K
# 创建 100x100 像素的 JPEG2000 图像。
with Jpeg2000Image(100, 100, create_options) as jpeg2000_image:
	graphics = Graphics(jpeg2000_image)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, jpeg2000_image.bounds)
	# 保存到文件
	jpeg2000_image.save(path_join(dir_, "sample.output.j2k"))


```

### This example shows how to create a PNG image and save it to JPEG2000 with the desired options. {#example_163}
``` python

from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import Jpeg2000Options
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec
from aspose.imaging.fileformats.png import PngImage
from os.path import join as path_join


dir_ = "c:\\temp"
# 创建一个 100x100 像素的 PNG 图像。
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	save_options = Jpeg2000Options()
	# 使用不可逆离散小波变换 9-7
	save_options.irreversible = True
	# JP2 是 JPEG 2000 码流的“容器”格式。
	# J2K 是未包装的原始压缩数据。
	save_options.codec = Jpeg2000Codec.J2K
	# 保存到文件
	png_image.save(path_join(dir_, "output.j2k"), save_options)


```

