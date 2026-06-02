---
title: "WebPImage 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.webp/webpimage/
---

**Summary:** Manipulate WebP raster images with our API, using its modern features for both<br/>            lossless and lossy compression, ensuring optimal image quality with reduced file sizes.<br/>            Seamlessly handle extended file formats, animations, and alpha channels, while easily<br/>            updating dimensions, resizing proportionally, cropping, rotating, applying filters,<br/>            adjusting image parameters, and converting to other image formats for versatile<br/>            web image optimization.

**Module:** [aspose.imaging.fileformats.webp](/imaging/python-net/aspose.imaging.fileformats.webp/)

**Full Name:** aspose.imaging.fileformats.webp.WebPImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WebPImage(path)](#WebPImage_path_1) | 实例化一个全新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类，初始化 <br/>            来自提供的文件源。利用此构造函数可无缝地直接从文件创建 WebP <br/>            图像对象，简化在应用程序中加载和 <br/>            操作 WebP 图像数据的过程。 |
| [WebPImage(path, load_options)](#WebPImage_path_load_options_2) | 使用文件和 <br/>            指定的加载选项创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类实例，以便灵活处理 WebP 图像数据。利用 <br/>            此构造函数可无缝地从文件初始化 WebP 图像对象，同时 <br/>            根据应用程序的需求自定义加载参数。 |
| [WebPImage(raster_image)](#WebPImage_raster_image_3) | 实例化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类实例，初始化 <br/>            来自提供的 rasterImage 对象。此构造函数允许无缝地 <br/>            将光栅图像转换为 WebP 格式，从而在应用程序中实现高效的图像数据处理和 <br/>            操作。 |
| [WebPImage(raster_image, load_options)](#WebPImage_raster_image_load_options_4) | 使用 rasterImage 对象和 <br/>            指定的加载选项创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类实例，以实现灵活的图像数据处理。利用此 <br/>            构造函数可无缝地从光栅图像初始化 WebP 图像对象，同时 <br/>            根据应用程序的需求自定义加载参数。 |
| [WebPImage(stream)](#WebPImage_stream_5) | 实例化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，已初始化 <br/>            来自提供的流源。利用此构造函数可无缝地直接从流创建 WebP <br/>            图像对象，实现对 WebP 图像数据的高效处理和操作 <br/>            在您的应用程序中。 |
| [WebPImage(stream, load_options)](#WebPImage_stream_load_options_6) | 从流中创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，<br/>            并结合指定的加载选项和内存管理设置。此构造函数在从流加载 WebP 图像时提供灵活性，同时<br/>            高效管理内存资源，确保最佳性能和资源<br/>            在您的应用程序中的利用率。 |
| [WebPImage(width, height, options)](#WebPImage_width_height_options_7) | 实例化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，使用空的<br/>            指定宽度和高度的图像。此构造函数允许创建空白 WebP 图像，为后续的图像<br/>            操作和内容生成提供基础。 |
| [WebPImage(width, height, options, load_options)](#WebPImage_width_height_options_load_options_8) | 创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，使用空图像并指定<br/>            加载选项。此构造函数允许使用可定制的加载参数，为图像创建和<br/>            在您的应用程序中的操作提供灵活性。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | 获取或设置一个值，指示是否自动调整调色板。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色的值。 |
| bits_per_pixel | int | r | 获取图像每像素位数计数。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取对象的边界。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取 [Image](/imaging/python-net/aspose.imaging/image/) 容器。 |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | 获取对象的数据流。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 实例。 |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 访问与图像关联的文件格式值，提供关于<br/>            图像存储格式的信息。利用此属性确定<br/>            图像的文件格式，便于兼容性检查和<br/>            在您的应用程序中的特定格式处理。 |
| [has_alpha](#has_alpha1) | bool | r | 获取图像是否包含 alpha 通道，以指示<br/>            透明度信息的存在。利用此属性确定图像是否<br/>            包含透明度，从而实现对 alpha 相关操作的适当处理和处理，在您的应用程序中。 |
| has_background_color | bool | r/w | 获取或设置指示图像是否具有背景颜色的值。 |
| has_transparent_color | bool | r/w | 获取指示图像是否具有透明颜色的值。 |
| height | int | r | 获取图像高度。 |
| horizontal_resolution | float | r/w | 获取或设置此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| image_opacity | float | r | 获取此图像的不透明度。 |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取指示图像数据当前是否已缓存的值。 |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | 获取或设置来自帧的 XMP 数据。 |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | r | 检索或修改与指定属性关联的选项，以实现<br/>            对行为和设置的精细定制。利用此属性<br/>            无缝访问和操作可配置参数，促进多样化的<br/>            在您的应用功能中的控制和优化。 |
| page_count | int | r | 检索指定文档的总页数，以便<br/>            高效导航和管理多页内容。整合此<br/>            功能以提升用户体验，实现对<br/>            完整文档结构的无缝访问。 |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | 访问图像中的 WebP 块，允许对底层块结构进行详细检查或<br/>            操作。利用此属性分析<br/>            或修改 WebP 图像数据中的单个块，以促进高级的<br/>            在您的应用程序中的图像处理技术。 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| premultiply_components | bool | r/w | 获取或设置一个值，指示图像组件是否必须进行预乘。 |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | 获取或设置自定义颜色转换器 |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取原始数据格式。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | 获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | r/w | 获取或设置当调色板索引超出范围时使用的回退索引 |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | 获取或设置索引颜色转换器 |
| raw_line_size | int | r | 获取以字节为单位的原始行大小。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | 获取对象大小。 |
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
| [add_block(block)](#add_block_block_1) | 将新的 WebP 块合并到图像中，丰富其内容并<br/>            促进高级图像操作。整合此方法以动态<br/>            提升您应用中 WebP 图像数据的结构和复杂性，<br/>            实现对图像渲染的精确控制和优化。 |
| [add_page(page)](#add_page_page_2) | 向图像追加新页面，扩展其内容并容纳额外的<br/>            视觉元素。整合此方法以促进动态页面管理<br/>            在您的应用程序中，实现多页文档或图像的无缝创建和增强。 |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | 实现图像的 _brightness_（亮度）调整，允许<br/>            整体亮度水平的修改。将此方法整合到您的图像<br/>            处理工作流中，以提升可见性并改善图像的视觉质量<br/>            在您的应用程序中。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | 增强 [Image](/imaging/python-net/aspose.imaging/image/) 的对比度，放大<br/>            明暗区域之间的差异。将此方法整合到您的图像<br/>            处理工作流中，以提升视觉清晰度和整体图像质量<br/>            在您的应用程序中。 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | 对图像应用伽马校正，调整像素强度以实现<br/>            所需的亮度和色彩平衡。将此方法整合到您的图像<br/>            处理工作流中，以提升视觉质量并提高后续分析或显示任务的准确性<br/>            在您的应用程序中。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | 使用红、<br/>            绿和蓝通道的单独系数对图像进行伽马校正，以实现对色彩平衡和<br/>            对比度的精细调节。将此方法整合到您的图像处理管线中，以实现<br/>            对颜色渲染的精确控制，并在您的<br/>            应用程序中提升视觉保真度。 |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | 计算提取数据与原始密码之间的相似度百分比。 |
| auto_brightness_contrast() | 对整个图像执行自动自适应亮度和对比度归一化。 |
| auto_rotate() | 自动根据从 Exif <br/>            元数据中提取的方向数据旋转图像。此方法确保图像以正确的方向显示，<br/>            提升用户体验并消除手动调整的需求。通过<br/>            分析 Exif 信息，图像相应旋转，提供跨不同平台和设备的无缝<br/>            浏览体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像批次时，<br/>            提高整体可用性。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | 使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | 使用 Bradley 自适应阈值算法对图像进行二值化，<br/>            结合积分图阈值。此方法动态计算局部阈值，基于图像邻域，提高对不同<br/>            光照条件的适应性，并确保后续处理任务的稳健分割<br/>            在您的应用程序中。 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | 使用预定义阈值对图像进行二值化，将其转换为<br/>            二进制图像，像素根据相对于阈值的强度被分类为前景或背景<br/>            。将此方法整合到<br/>            您的图像处理工作流中，以促进分割和特征提取<br/>            任务，提高后续分析的准确性和效率<br/>            在您的应用程序中。 |
| binarize_otsu() | 使用 Otsu 阈值法对图像进行二值化，自动<br/>            根据图像直方图确定最佳阈值。整合<br/>            此方法到您的图像处理工作流，以实现有效的分割<br/>            和特征提取，提升图像分析任务的准确性和可靠性<br/>            在您的应用程序中。 |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | 将此图像实例与 _overlay_ 图像混合。 |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | 将此图像实例与 _overlay_ 图像混合。 |
| cache_data() | 缓存私有数据。 |
| [can_load(file_path)](#can_load_file_path_13) | 确定是否可以从指定的文件路径加载图像。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| [can_load(stream)](#can_load_stream_15) | 确定是否可以从指定的流加载图像。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | 确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。 |
| [can_load_stream(stream)](#can_load_stream_stream_17) | 确定是否可以从指定的流加载图像。 |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | 确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。 |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| [can_save(options)](#can_save_options_20) | 确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。 |
| clear_blocks() | 清除图像中所有现有的 WebP 块，为后续修改或添加提供一个干净的起点。<br/>            利用此方法有效地重置<br/>            WebP 图像数据中的块结构，确保最佳的管理和<br/>            在您的应用程序中组织图像内容。 |
| [create(files)](#create_files_21) | 创建包含指定文件的多页图像。 |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | 创建包含指定文件的多页图像。 |
| [create(image_options, width, height)](#create_image_options_width_height_23) | 使用指定的创建选项创建新图像。 |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | 创建一个来自提供的像素数组的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例。<br/>            <br/>            验证指定的宽度和高度是否与像素数据的维度匹配。<br/>            仅当库处于授权模式时才能使用此方法。 |
| [create(images)](#create_images_25) | 使用指定的图像作为页面创建新图像。 |
| [create(images, dispose_images)](#create_images_dispose_images_26) | 创建一个新图像，将指定的图像作为页面。 |
| [create(multipage_create_options)](#create_multipage_create_options_27) | 创建指定的多页创建选项。 |
| [create_from_file_with_options(path, load_options)](#create_from_file_with_options_path_load_options_28) | 从文件初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。 |
| [create_from_files(files)](#create_from_files_files_29) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_30) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_image(raster_image)](#create_from_image_raster_image_31) | 从 rasterImage 初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。 |
| [create_from_image_with_options(raster_image, load_options)](#create_from_image_with_options_raster_image_load_options_32) | 从 rasterImage 初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。 |
| [create_from_images(images)](#create_from_images_images_33) | 使用指定的图像作为页面创建新图像。 |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_34) | 创建一个新图像，将指定的图像作为页面。 |
| [create_from_stream(stream)](#create_from_stream_stream_35) | 初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例<br/>                来自流。 |
| [create_from_stream_with_options(stream, load_options)](#create_from_stream_with_options_stream_load_options_36) | 从流初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。 |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | 通过左右上下平移裁剪图像，有效地<br/>            在图像中选择感兴趣的区域。利用此方法<br/>            动态提取图像所需部分，同时调整其构图<br/>            和焦点，以满足您的应用需求。 |
| [crop(rectangle)](#crop_rectangle_38) | 使用指定的矩形区域裁剪图像，去除不需要的部分<br/>            同时保留所需内容。将此方法整合到您的图像<br/>            处理工作流中，以精确提取并聚焦图像中感兴趣的特定区域<br/>            提升清晰度和构图，适用于各种应用。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | 对当前图像执行抖动以降低颜色条纹并提升视觉 <br/>            质量。将此方法集成到您的图像处理工作流中，以实现 <br/>            更平滑的颜色过渡，并改善图像在您的应用程序中的整体外观。 |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| [filter(rectangle, options)](#filter_rectangle_options_42) | 在指定矩形区域内过滤内容，应用指定的图像 <br/>            处理滤镜以增强或修改所选区域。将此方法 <br/>            集成到您的图像操作工作流中，以实现针对性的增强或 <br/>            转换，在您的应用程序中。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_43) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_44) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_45) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_46) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_48) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_49) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_50) | 获取文件格式。 |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_51) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_52) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_53) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | 获取资源图像最后修改的日期和时间。 |
| [get_original_options()](#get_original_options__55) | 根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。 |
| [get_pixel(x, y)](#get_pixel_x_y_56) | 获取图像像素。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | 获取比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | 获取比例宽度。 |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | 转换为 aps。 |
| [get_skew_angle()](#get_skew_angle__60) | 获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。 |
| grayscale() | 将图像转换为灰度表示，将其转化为 <br/>            单通道图像，其中每个像素表示强度或亮度。将 <br/>            此方法集成到您的图像处理管道中，以简化分析并提升 <br/>            与基于灰度的算法的兼容性，促进各种计算机 <br/>            视觉和图像分析任务在您的应用程序中的执行。 |
| [insert_block(index, block)](#insert_block_index_block_61) | 在图像中指定索引处插入新的 WebP 块，以实现对块序列的精确 <br/>            控制。将此方法集成以无缝地将 <br/>            额外的 WebP 块加入图像数据结构，促进高级图像 <br/>            处理和优化在您的应用程序中的实现。 |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | 使用提供的密码和阈值执行快速检查，以确定图像是否已数字签名。 |
| [load(file_path)](#load_file_path_63) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(file_path, load_options)](#load_file_path_load_options_64) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(stream)](#load_stream_65) | 从指定的流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_66) | 从流中加载数据。 |
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
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) 方法。 |
| normalize_histogram() | 归一化图像直方图 — 调整像素值以使用全部可用范围。 |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | 按指定的扫描线索引读取整条扫描线。 |
| [remove_block(block)](#remove_block_block_83) | 从图像中移除指定的 WebP 块，便于高效管理 <br/>            图像数据结构。使用此方法通过消除不必要的块或组件来简化图像处理 <br/>            工作流，在您的应用程序中。 |
| remove_metadata() | 通过将此 [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) 值设置为 **None** 来移除此图像实例的元数据。 |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_87) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_88) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_89) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_90) | 调整图像大小，改变其尺寸同时保持纵横比。<br/>            将此方法集成到您的图像处理工作流中，以动态缩放 <br/>            图像以满足应用程序中各种显示或存储需求。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_91) | 根据指定设置调整图像大小，实现对 <br/>            尺寸、纵横比和缩放行为的精确控制。将此方法集成到您的 <br/>            图像处理工作流中，以实现符合您应用程序特定需求的定制化调整操作。 |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_92) | 调整图像大小。 |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_93) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_94) | 按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_95) | 按比例调整图像高度，同时保持其纵横比 <br/>            以实现一致的缩放。将此方法集成到您的图像处理工作流中 <br/>            动态地以统一比例调整图像大小，确保在您的应用程序中获得最佳显示或 <br/>            存储效果。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_96) | 按比例调整高度。 |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_97) | 按比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_98) | 按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_99) | 按比例调整图像宽度，同时保持其纵横比。<br/>            将此方法集成到您的图像处理工作流中，以动态缩放 <br/>            图像并保持一致的比例，确保在您的应用程序中获得最佳显示或存储。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_100) | 按比例调整宽度。 |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_101) | 按比例调整宽度。 |
| [rotate(angle)](#rotate_angle_102) | 围绕中心旋转图像。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_103) | 围绕中心按指定角度旋转图像，同时按比例 <br/>            调整大小并应用指定的背景颜色参数。将此 <br/>            方法纳入您的图像处理工作流，以实现具有可自定义背景颜色的精确变换，确保在您的 <br/>            应用程序中获得最佳视觉呈现。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_104) | 将旋转、翻转或两者操作仅应用于图像中的活动帧 <br/>            。将此方法集成到您的图像处理工作流中，以 <br/>            实现对单帧的精确操作，提升灵活性和 <br/>            对帧转换的控制，在您的应用程序中。 |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_105) | 旋转并翻转全部。 |
| save() | 将图像数据保存到底层流中。 |
| [save(file_path)](#save_file_path_106) | 将图像保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_107) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_108) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, over_write)](#save_file_path_over_write_109) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_110) | 保存数据。 |
| [save(stream, options_base)](#save_stream_options_base_111) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_112) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_113) | 保存 32 位 ARGB 像素。 |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_114) | 保存像素。 |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_115) | 保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_116) | 保存像素的内部主要内容。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_117) | 保存原始数据。 |
| [save_to_stream(stream)](#save_to_stream_stream_118) | 将对象的数据保存到指定的流中。 |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_119) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_121) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_122) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_123) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_124) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_125) | 为指定位置设置图像像素。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_126) | 为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_127) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_129) | 将整条扫描线写入指定的扫描线索引。 |


### Constructor: WebPImage(path) {#WebPImage_path_1}


```
 WebPImage(path) 
```

实例化一个全新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类，初始化 <br/>            来自提供的文件源。利用此构造函数可无缝地直接从文件创建 WebP <br/>            图像对象，简化在应用程序中加载和 <br/>            操作 WebP 图像数据的过程。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | WebP 图像文件的路径 |


**See also:**

**[Example # 1](#example_164)**: This example shows how to load a WebP image from a file and save it to PNG.


### Constructor: WebPImage(path, load_options) {#WebPImage_path_load_options_2}


```
 WebPImage(path, load_options) 
```

使用文件和 <br/>            指定的加载选项创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类实例，以便灵活处理 WebP 图像数据。利用 <br/>            此构造函数可无缝地从文件初始化 WebP 图像对象，同时 <br/>            根据应用程序的需求自定义加载参数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | WebP 图像文件的路径 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

### Constructor: WebPImage(raster_image) {#WebPImage_raster_image_3}


```
 WebPImage(raster_image) 
```

实例化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类实例，初始化 <br/>            来自提供的 rasterImage 对象。此构造函数允许无缝地 <br/>            将光栅图像转换为 WebP 格式，从而在应用程序中实现高效的图像数据处理和 <br/>            操作。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |


**See also:**

**[Example # 1](#example_166)**: This example shows how to create a WebP image from another raster image.


### Constructor: WebPImage(raster_image, load_options) {#WebPImage_raster_image_load_options_4}


```
 WebPImage(raster_image, load_options) 
```

使用 rasterImage 对象和 <br/>            指定的加载选项创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类实例，以实现灵活的图像数据处理。利用此 <br/>            构造函数可无缝地从光栅图像初始化 WebP 图像对象，同时 <br/>            根据应用程序的需求自定义加载参数。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

### Constructor: WebPImage(stream) {#WebPImage_stream_5}


```
 WebPImage(stream) 
```

实例化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，已初始化 <br/>            来自提供的流源。利用此构造函数可无缝地直接从流创建 WebP <br/>            图像对象，实现对 WebP 图像数据的高效处理和操作 <br/>            在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | WebP 图像流。 |


**See also:**

**[Example # 1](#example_165)**: This example shows how to load a WebP image from a file stream and save it to...


### Constructor: WebPImage(stream, load_options) {#WebPImage_stream_load_options_6}


```
 WebPImage(stream, load_options) 
```

从流中创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，<br/>            并结合指定的加载选项和内存管理设置。此构造函数在从流加载 WebP 图像时提供灵活性，同时<br/>            高效管理内存资源，确保最佳性能和资源<br/>            在您的应用程序中的利用率。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | WebP 图像流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

### Constructor: WebPImage(width, height, options) {#WebPImage_width_height_options_7}


```
 WebPImage(width, height, options) 
```

实例化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，使用空的<br/>            指定宽度和高度的图像。此构造函数允许创建空白 WebP 图像，为后续的图像<br/>            操作和内容生成提供基础。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度。 |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | 选项。 |


**See also:**

**[Example # 1](#example_167)**: This example shows how to create a WebP image with the specified options from...


### Constructor: WebPImage(width, height, options, load_options) {#WebPImage_width_height_options_load_options_8}


```
 WebPImage(width, height, options, load_options) 
```

创建一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例，使用空图像并指定<br/>            加载选项。此构造函数允许使用可定制的加载参数，为图像创建和<br/>            在您的应用程序中的操作提供灵活性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| width | int | 图像宽度 |
| height | int | 图像高度。 |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | 选项。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

### Property: has_alpha {#has_alpha1}

获取图像是否包含 alpha 通道，以指示<br/>            透明度信息的存在。利用此属性确定图像是否<br/>            包含透明度，从而实现对 alpha 相关操作的适当处理和处理，在您的应用程序中。

**See also:**

**[Example # 1](#example_168)**: The following example loads a WEBP image and prints information about raw dat...


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

将新的 WebP 块合并到图像中，丰富其内容并<br/>            促进高级图像操作。整合此方法以动态<br/>            提升您应用中 WebP 图像数据的结构和复杂性，<br/>            实现对图像渲染的精确控制和优化。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | 要添加的 WebP 块。 |

### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

向图像追加新页面，扩展其内容并容纳额外的<br/>            视觉元素。整合此方法以促进动态页面管理<br/>            在您的应用程序中，实现多页文档或图像的无缝创建和增强。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要添加的页面。 |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

实现图像的 _brightness_（亮度）调整，允许<br/>            整体亮度水平的修改。将此方法整合到您的图像<br/>            处理工作流中，以提升可见性并改善图像的视觉质量<br/>            在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 亮度 | int | 亮度值。 |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

增强 [Image](/imaging/python-net/aspose.imaging/image/) 的对比度，放大<br/>            明暗区域之间的差异。将此方法整合到您的图像<br/>            处理工作流中，以提升视觉清晰度和整体图像质量<br/>            在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

对图像应用伽马校正，调整像素强度以实现<br/>            所需的亮度和色彩平衡。将此方法整合到您的图像<br/>            处理工作流中，以提升视觉质量并提高后续分析或显示任务的准确性<br/>            在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

使用红、<br/>            绿和蓝通道的单独系数对图像进行伽马校正，以实现对色彩平衡和<br/>            对比度的精细调节。将此方法整合到您的图像处理管线中，以实现<br/>            对颜色渲染的精确控制，并在您的<br/>            应用程序中提升视觉保真度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| gamma_red | float | 红色通道的伽马系数 |
| gamma_green | float | 绿色通道的伽马系数 |
| gamma_blue | float | 蓝色通道系数的 Gamma |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brightness_difference | float | 像素与以该像素为中心的 s x s 像素窗口的平均值之间的亮度差<br/>                。 |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

使用 Bradley 自适应阈值算法对图像进行二值化，<br/>            结合积分图阈值。此方法动态计算局部阈值，基于图像邻域，提高对不同<br/>            光照条件的适应性，并确保后续处理任务的稳健分割<br/>            在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brightness_difference | float | 像素与以该像素为中心的 s x s 像素窗口的平均值之间的亮度差<br/>            。 |
| window_size | int | 以该像素为中心的 s x s 像素窗口的大小 |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

使用预定义阈值对图像进行二值化，将其转换为<br/>            二进制图像，像素根据相对于阈值的强度被分类为前景或背景<br/>            。将此方法整合到<br/>            您的图像处理工作流中，以促进分割和特征提取<br/>            任务，提高后续分析的准确性和效率<br/>            在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 阈值 | System.Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为<br/>            255，否则为 0。 |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create(files)  [static] {#create_files_21}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


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


### Method: create(images)  [static] {#create_images_25}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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


### Method: create_from_file_with_options(path, load_options)  [static] {#create_from_file_with_options_path_load_options_28}


```
 create_from_file_with_options(path, load_options) 
```

从文件初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | WebP 图像文件的路径 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_29}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_30}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_31}


```
 create_from_image(raster_image) 
```

从 rasterImage 初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_image_with_options(raster_image, load_options)  [static] {#create_from_image_with_options_raster_image_load_options_32}


```
 create_from_image_with_options(raster_image, load_options) 
```

从 rasterImage 初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_33}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_34}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_35}


```
 create_from_stream(stream) 
```

初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例<br/>                来自流。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | WebP 图像流。 |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_stream_with_options(stream, load_options)  [static] {#create_from_stream_with_options_stream_load_options_36}


```
 create_from_stream_with_options(stream, load_options) 
```

从流初始化一个新的 [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) 类的实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | WebP 图像流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |

**Returns**

| Type | Description |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

通过左右上下平移裁剪图像，有效地<br/>            在图像中选择感兴趣的区域。利用此方法<br/>            动态提取图像所需部分，同时调整其构图<br/>            和焦点，以满足您的应用需求。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| left_shift | int | 左移。 |
| right_shift | int | 右移。 |
| top_shift | int | 上移。 |
| bottom_shift | int | 下移。 |

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

使用指定的矩形区域裁剪图像，去除不需要的部分<br/>            同时保留所需内容。将此方法整合到您的图像<br/>            处理工作流中，以精确提取并聚焦图像中感兴趣的特定区域<br/>            提升清晰度和构图，适用于各种应用。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_39}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_40}


```
 dither(dithering_method, bits_count, custom_palette) 
```

对当前图像执行抖动以降低颜色条纹并提升视觉 <br/>            质量。将此方法集成到您的图像处理工作流中，以实现 <br/>            更平滑的颜色过渡，并改善图像在您的应用程序中的整体外观。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 用于抖动的自定义调色板。 |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_41}


```
 embed_digital_signature(password) 
```

根据提供的密码将数字签名嵌入图像的每一页。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于生成数字签名数据的密码 |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

在指定矩形区域内过滤内容，应用指定的图像 <br/>            处理滤镜以增强或修改所选区域。将此方法 <br/>            集成到您的图像操作工作流中，以实现针对性的增强或 <br/>            转换，在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | 选项。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_43}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_44}


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


### Method: get_default_options(args) {#get_default_options_args_45}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_46}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_48}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_49}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_50}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_51}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_52}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_53}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_54}


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


### Method: get_original_options() {#get_original_options__55}


```
 get_original_options() 
```

根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_56}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_57}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_58}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_59}


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


### Method: get_skew_angle() {#get_skew_angle__60}


```
 get_skew_angle() 
```

获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。

**Returns**

| Type | Description |
| :- | :- |
| float | 倾斜角度（单位：度）。 |


### Method: insert_block(index, block) {#insert_block_index_block_61}


```
 insert_block(index, block) 
```

在图像中指定索引处插入新的 WebP 块，以实现对块序列的精确 <br/>            控制。将此方法集成以无缝地将 <br/>            额外的 WebP 块加入图像数据结构，促进高级图像 <br/>            处理和优化在您的应用程序中的实现。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 零基索引元素，_block_ 将在此处<br/>                插入。 |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | 要添加的 WebP 块。 |

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

从流中加载数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | WebP 图像流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项 |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) |  |


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

归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) 方法。

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


### Method: remove_block(block) {#remove_block_block_83}


```
 remove_block(block) 
```

从图像中移除指定的 WebP 块，便于高效管理 <br/>            图像数据结构。使用此方法通过消除不必要的块或组件来简化图像处理 <br/>            工作流，在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | 要删除的块。 |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


```
 replace_color(old_color, old_color_diff, new_color) 
```

在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | 允许的旧颜色差异，以便能够扩大替换颜色的色调。 |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_87}


```
 replace_non_transparent_colors(new_color) 
```

将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_88}


```
 replace_non_transparent_colors(new_color_argb) 
```

将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_argb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_89}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_90}


```
 resize(new_width, new_height, resize_type) 
```

调整图像大小，改变其尺寸同时保持纵横比。<br/>            将此方法集成到您的图像处理工作流中，以动态缩放 <br/>            图像以满足应用程序中各种显示或存储需求。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小类型。 |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_91}


```
 resize(new_width, new_height, settings) 
```

根据指定设置调整图像大小，实现对 <br/>            尺寸、纵横比和缩放行为的精确控制。将此方法集成到您的 <br/>            图像处理工作流中，以实现符合您应用程序特定需求的定制化调整操作。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 调整大小设置。 |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_92}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_93}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_94}


```
 resize_height_proportionally(new_height) 
```

按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_95}


```
 resize_height_proportionally(new_height, resize_type) 
```

按比例调整图像高度，同时保持其纵横比 <br/>            以实现一致的缩放。将此方法集成到您的图像处理工作流中 <br/>            动态地以统一比例调整图像大小，确保在您的应用程序中获得最佳显示或 <br/>            存储效果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_96}


```
 resize_height_proportionally(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_97}


```
 resize_height_proportionally_settings(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_98}


```
 resize_width_proportionally(new_width) 
```

按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_99}


```
 resize_width_proportionally(new_width, resize_type) 
```

按比例调整图像宽度，同时保持其纵横比。<br/>            将此方法集成到您的图像处理工作流中，以动态缩放 <br/>            图像并保持一致的比例，确保在您的应用程序中获得最佳显示或存储。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_100}


```
 resize_width_proportionally(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_101}


```
 resize_width_proportionally_settings(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: rotate(angle) {#rotate_angle_102}


```
 rotate(angle) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_103}


```
 rotate(angle, resize_proportionally, background_color) 
```

围绕中心按指定角度旋转图像，同时按比例 <br/>            调整大小并应用指定的背景颜色参数。将此 <br/>            方法纳入您的图像处理工作流，以实现具有可自定义背景颜色的精确变换，确保在您的 <br/>            应用程序中获得最佳视觉呈现。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将被更改<br/>            根据旋转矩形（角点）的投影在其他<br/>            情况下，尺寸保持不变，仅<br/>            __internal__ 图像内容被旋转。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_104}


```
 rotate_flip(rotate_flip_type) 
```

将旋转、翻转或两者操作仅应用于图像中的活动帧 <br/>            。将此方法集成到您的图像处理工作流中，以 <br/>            实现对单帧的精确操作，提升灵活性和 <br/>            对帧转换的控制，在您的应用程序中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转类型。 |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_105}


```
 rotate_flip_all(rotate_flip) 
```

旋转并翻转全部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转。 |

### Method: save(file_path) {#save_file_path_106}


```
 save(file_path) 
```

将图像保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存图像的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_107}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_108}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_109}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，覆盖文件内容，否则将追加。 |

### Method: save(stream) {#save_stream_110}


```
 save(stream) 
```

保存数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存图像数据的流。 |

### Method: save(stream, options_base) {#save_stream_options_base_111}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_112}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_113}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_114}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

保存像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 以 32 位整数值表示的 CMYK 像素。 |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_115}


```
 save_cmyk_pixels(rectangle, pixels) 
```

保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_116}


```
 save_pixels(rectangle, pixels) 
```

保存像素的内部主要内容。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 像素。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_117}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_118}


```
 save_to_stream(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_119}


```
 save_to_stream_with_options(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_121}


```
 save_with_options(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_122}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_123}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_124}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，未更改的索引如果在加载时没有对应的调色板条目，可能会导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_125}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_126}


```
 set_resolution(dpi_x, dpi_y) 
```

为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dpi_x | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率。 |
| dpi_y | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率。 |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_127}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int[] | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_129}


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
### This example shows how to load a WebP image from a file and save it to PNG. {#example_164}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
# 从文件加载 WebP 图像。
with WebPImage(join(dir_, "test.webp")) as web_pimage:
	# 保存为 PNG
	# 请注意，由于 PNG 不是多页格式，只有活动帧会被保存为 PNG。
	web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to load a WebP image from a file stream and save it to PNG. {#example_165}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# 从文件流加载 WebP 图像。
with open(join(dir_, "test.webp"), "w+b") as stream:
	with WebPImage(stream) as web_pimage:
		# 保存为 PNG
		# 请注意，由于 PNG 不是多页格式，只有活动帧会被保存为 PNG。
		web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to create a WebP image from another raster image. {#example_166}
``` python
from os.path import join
from aspose.imaging import Graphics, Color
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions      

dir_: str = "c:\\temp"
# 加载 100x100 像素的 PNG 图像。
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# 基于 PNG 图像创建 WebP 图像。
	with WebPImage(png_image) as web_pimage:
		# 使用默认选项保存为 WebP 文件
		web_pimage.save(join(dir_, "output.webp"), WebPOptions())


```

### This example shows how to create a WebP image with the specified options from scratch. {#example_167}
``` python
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions
from os.path import join


dir_: str = "c:\\temp"
create_options = WebPOptions()
create_options.lossless = True
create_options.quality = 100.0

# 创建 100x100 像素的 WebP 图像。
with WebPImage(100, 100, create_options) as web_pimage:
	graphics = Graphics(web_pimage)
	# 将整幅图像填充为红色。
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, web_pimage.bounds)
	# 保存为 WebP 文件
	web_pimage.save(join(dir_, "output.webp"))


```

### The following example loads a WEBP image and prints information about raw data format and alpha channel. {#example_168}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.webp import WebPImage, WebPFrameBlock

dir_ = "c:\\temp"
file_name = dir_ + "sample.webp"
with Image.load(file_name) as image:
	webp_image = aspycore.as_of(image, WebPImage)
	# 如果活动的 TIFF 帧具有 alpha 通道，则整个 TIFF 图像被视为具有 alpha 通道。
	print(f"ImageFile={file_name}, FileFormat={webp_image.raw_data_format}, HasAlpha={webp_image.has_alpha}")
	i: int = 0
	for frame in webp_image.blocks:
		if aspycore.is_assignable(frame, WebPFrameBlock):
			frame_block = aspycore.as_of(frame, WebPFrameBlock)
			print(f"Frame={i}, FileFormat={frame_block.raw_data_format}, HasAlpha={frame_block.has_alpha}")
			i += 1

# 输出可能如下所示：
# ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False
# Frame=0, FileFormat=RgbIndexed1Bpp, 使用的通道: 1, HasAlpha=False


```

