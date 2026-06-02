---
title: "DicomImage 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.dicom/dicomimage/
---

**Summary:** This Class implements Digital Imaging and Communications in Medicine<br/>            (DICOM) raster image format support and offers a comprehensive solution for<br/>            processing DICOM images with precision and flexibility. You can seamlessly<br/>            manipulate image pages, including operations to get, add, or remove pages, and<br/>            control the default and active pages. With capabilities to work with alpha channels,<br/>            embed XMP metadata, resize, rotate, crop, binarize, adjust, apply filters,<br/>            and convert to other raster formats. This API empowers developers to handle<br/>            DICOM images effectively while meeting diverse application requirements in<br/>            medical imaging contexts.

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [DicomImage(dicom_options, width, height)](#DicomImage_dicom_options_width_height_1) | 使用此<br/>构造函数轻松初始化 DicomImage 类的新实例，利用 dicomOptions 参数。非常适合希望在项目中快速高效地深入使用 [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) 对象的开发者。 |
| [DicomImage(stream)](#DicomImage_stream_2) | 通过在此构造函数中使用流参数<br/>创建 DicomImage 类的新实例。非常适合希望以简化方式从现有数据流初始化 [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) 对象的开发者。 |
| [DicomImage(stream, load_options)](#DicomImage_stream_load_options_3) | 通过在此构造函数中使用流和<br/>loadOptions 参数，顺畅地启动 DicomImage 类的新实例。理想的选择是渴望在项目中快速有效地使用 [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) 对象的开发者。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| active_page | [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r/w | 使用此直观属性管理图像的活动页。<br/>理想的选择是希望在多页图像中动态切换页面、确保高效<br/>导航和处理的开发者。 |
| active_page_index | int | r | 使用此直观属性轻松检索活动页的索引。<br/>理想的选择是希望快速访问多页图像中当前页索引、确保高效<br/>导航和处理的开发者。 |
| auto_adjust_palette | bool | r/w | 获取或设置一个值，指示是否自动调整调色板。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置背景颜色的值。 |
| bits_per_pixel | int | r | 获取图像每像素位数计数。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取对象的边界。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取 [Image](/imaging/python-net/aspose.imaging/image/) 容器。 |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | 获取对象的数据流。 |
| dicom_pages | [DicomPage[]](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r | 使用此直观属性访问图像的页面。适用于开发者<br/>            希望与图像中的各个页面交互，确保无缝<br/>            导航和操作。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 实例。 |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 使用此直观属性轻松检索文件格式值。适用于<br/>            开发者快速获取图像文件的格式，确保基于文件类型的高效<br/>            处理和加工。 |
| file_info | [DicomImageInfo](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/) | r | 使用此<br/>            直观属性轻松检索 DICOM 文件中的有价值的头部信息。适用于开发者快速获取 DICOM 文件中封装的关键细节，确保高效的数据提取和分析。 |
| has_alpha | bool | r | 使用此直观<br/>            属性轻松检索图像是否具有 alpha 通道。适用于开发者希望确定图像是否包含透明度<br/>            信息，确保在图像处理任务中精确处理 alpha 通道数据。 |
| has_background_color | bool | r/w | 获取或设置指示图像是否具有背景颜色的值。 |
| has_transparent_color | bool | r/w | 获取指示图像是否具有透明颜色的值。 |
| height | int | r | 获取图像高度。 |
| horizontal_resolution | float | r/w | 获取或设置此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| image_opacity | float | r | 获取此图像的不透明度。 |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取指示图像数据当前是否已缓存的值。 |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | 获取或设置来自帧的 XMP 数据。 |
| page_count | int | r | 使用此直观属性检索图像的总页数。适用于<br/>            开发者快速获取图像中页面数量，确保高效的导航和管理。 |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | 使用此直观属性访问图像的页面。适用于开发者<br/>            希望与图像中的各个页面交互，确保无缝的导航<br/>            和操作。 |
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
| [add_page()](#add_page__1) | 使用此直接方法将新页面追加到图像页面列表的末尾。<br/>            适用于希望动态扩展多页图像的开发者，确保图像内容的无缝<br/>            集成和组织。 |
| [add_page(page)](#add_page_page_2) | 通过此直观方法添加新页面，扩展您的图像集合。<br/>            适用于希望动态追加页面到多页图像的开发者，<br/>            确保图像内容的无缝扩展和组织。 |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | 通过调整 _brightness_ 来增强图像亮度，<br/>            这是一种参数化方法，允许开发者精细调节图像的光照度。<br/>            该用户友好功能使开发者能够无缝操作图像<br/>            亮度，提供对视觉美感的灵活性和控制。 |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | 使用此用户友好的方法增强 [Image](/imaging/python-net/aspose.imaging/image/) 对比度，<br/>            该方法调整光暗区域之间的差异。轻松提升视觉清晰度和<br/>            细节定义，为开发者提供直观的图像对比度控制，以实现最佳渲染。 |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | 使用伽马校正提升图像质量并进行调整，这是一种强大的技术<br/>            用于微调视觉外观。非常适合希望优化图像<br/>            展示、调整色彩平衡，并确保在不同<br/>            设备和环境中保持一致渲染的开发者。 |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | 通过对图像的红、绿、蓝分量独立应用伽马校正，实现精确的颜色调整。此方法确保准确的<br/>            色彩平衡和最佳的视觉输出，满足寻求对图像渲染和颜色精度进行细粒度<br/>            控制的开发者需求。 |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | 计算提取数据与原始密码之间的相似度百分比。 |
| auto_brightness_contrast() | 对整个图像执行自动自适应亮度和对比度归一化。 |
| auto_rotate() | 自动根据从 Exif <br/>            元数据中提取的方向数据旋转图像。此方法确保图像以正确的方向显示，<br/>            提升用户体验并消除手动调整的需求。通过<br/>            分析 Exif 信息，图像相应旋转，提供跨不同平台和设备的无缝<br/>            浏览体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像批次时，<br/>            提高整体可用性。 |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | 使用 Bradley 的自适应阈值算法和积分图阈值进行图像二值化 |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | 使用 Bradley 的自适应阈值算法进行图像二值化，利用积分<br/>            图阈值提升性能。非常适合希望<br/>            根据局部亮度变化自动分割图像的开发者，确保在不同光照条件下的<br/>            准确目标检测和提取。 |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | 使用预定义阈值将图像轻松转换为二进制格式<br/>            的直接方法。非常适合希望通过根据指定强度水平将图像分割为前景和背景组件来简化图像<br/>            处理任务的开发者。 |
| binarize_otsu() | 应用 Otsu 阈值法对图像进行二值化，自动根据图像直方图确定最佳<br/>            阈值。非常适合寻求一种可靠方法将图像分割为前景和背景区域且<br/>            人为干预最小的开发者。 |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | 将此图像实例与 _overlay_ 图像混合。 |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | 将此图像实例与 _overlay_ 图像混合。 |
| cache_data() | 此方法高效缓存数据，优化性能并确保在需要时快速访问<br/>            。非常适合希望通过智能管理数据资源来提升其<br/>            应用程序速度和效率的开发者。 |
| [can_load(file_path)](#can_load_file_path_13) | 确定是否可以从指定的文件路径加载图像。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| [can_load(stream)](#can_load_stream_15) | 确定是否可以从指定的流加载图像。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | 确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。 |
| [can_load_stream(stream)](#can_load_stream_stream_17) | 确定是否可以从指定的流加载图像。 |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | 确定是否可以从指定的流加载图像，并可选地使用指定的 _loadOptions_。 |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | 确定是否可以从指定的文件路径加载图像，并可选地使用指定的打开选项。 |
| [can_save(options)](#can_save_options_20) | 确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。 |
| [create(files)](#create_files_21) | 创建包含指定文件的多页图像。 |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | 创建包含指定文件的多页图像。 |
| [create(image_options, width, height)](#create_image_options_width_height_23) | 使用指定的创建选项创建新图像。 |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | 创建一个来自提供的像素数组的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例。<br/>            <br/>            验证指定的宽度和高度是否与像素数据的维度匹配。<br/>            仅当库处于授权模式时才能使用此方法。 |
| [create(images)](#create_images_25) | 使用指定的图像作为页面创建新图像。 |
| [create(images, dispose_images)](#create_images_dispose_images_26) | 创建一个新图像，将指定的图像作为页面。 |
| [create(multipage_create_options)](#create_multipage_create_options_27) | 创建指定的多页创建选项。 |
| [create_from_files(files)](#create_from_files_files_28) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_images(images)](#create_from_images_images_30) | 使用指定的图像作为页面创建新图像。 |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | 创建一个新图像，将指定的图像作为页面。 |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | 通过使用此多功能方法应用位移来调整图像的裁剪区域。<br/>            非常适合需要对裁剪过程进行精确控制的开发者，确保保留重要细节，同时消除不必要的元素。 |
| [crop(rectangle)](#crop_rectangle_33) | 使用此<br/>            简单方法裁剪图像，以去除不需要的区域并聚焦于关键内容。非常适合希望自定义图像视觉构图的开发者，确保图像有效传达预期信息。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | 通过使用此直接的<br/>            方法对当前图像应用抖动效果来增强图像。非常适合希望为图像添加纹理和深度的开发者，提升其视觉质量和整体吸引力。 |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | 根据提供的密码将数字签名嵌入图像的每一页。 |
| [filter(rectangle, options)](#filter_rectangle_options_37) | 通过对指定的<br/>            矩形应用滤镜，轻松增强图像的特定区域。此方法为开发者提供对图像操作的精确控制，能够进行有针对性的调整，以轻松实现期望的视觉效果。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_40) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_44) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_45) | 获取文件格式。 |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | 获取资源图像最后修改的日期和时间。 |
| [get_original_options()](#get_original_options__50) | 根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。 |
| [get_pixel(x, y)](#get_pixel_x_y_51) | 获取图像像素。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | 获取比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | 获取比例宽度。 |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | 转换为 aps。 |
| [get_skew_angle()](#get_skew_angle__55) | 获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。 |
| grayscale() | 轻松将图像转换为灰度表示，简化视觉<br/>            分析和处理任务。非常适合希望提升图像清晰度、<br/>            降低复杂度并促进高效灰度算法的开发者<br/>            用于各种应用。 |
| [insert_page(page_index)](#insert_page_page_index_56) | 使用此直观的<br/>            方法在指定索引处向图像的页面列表插入新页面。非常适合希望对多页图像中页面排列进行精确控制的开发者，确保图像内容的无缝组织和自定义。 |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | 使用提供的密码和阈值执行快速检查，以确定图像是否已数字签名。 |
| [load(file_path)](#load_file_path_58) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(file_path, load_options)](#load_file_path_load_options_59) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(stream)](#load_stream_60) | 从指定的流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_61) | 从指定的流加载新图像。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | 加载 32 位 ARGB 像素。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | 加载 64 位 ARGB 像素。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | 加载 CMYK 格式的像素。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | 加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | 部分加载 32 位 ARGB 像素（按块）。 |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | 按包部分加载 64 位 ARGB 像素。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | 按包部分加载像素。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | 加载像素。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | 加载原始数据。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | 加载原始数据。 |
| [load_stream(stream)](#load_stream_stream_72) | 从指定的流加载新图像。 |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | 从指定的流加载新图像。 |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| normalize_angle() | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) 方法。 |
| normalize_histogram() | 归一化图像直方图 — 调整像素值以使用全部可用范围。 |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | 按指定的扫描线索引读取整条扫描线。 |
| remove_metadata() | 通过将此 [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) 值设置为 **None** 来移除此图像实例的元数据。 |
| [remove_page(page_index)](#remove_page_page_index_78) | 使用此便捷方法从页面列表中删除指定索引处的页面。<br/>            非常适合希望对多页图像的管理进行精确控制的开发者，确保图像内容的无缝组织和自定义。 |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | 将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | 使用此便捷方法在保持宽高比的同时调整图像大小。非常适合希望按比例调整图像尺寸、确保一致性并保留原始内容比例的开发者。<br/>            比例缩放将根据 _newWidth_/width 和 _newHeight_/height 的比例来调整每个帧的大小。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | 使用此简单的调整大小方法来调整图像尺寸。无论您需要<br/>缩小或放大图像，此函数都能确保满足您的调整大小需求<br/>高效且准确，使其成为寻求快速简便<br/>图像尺寸调整的开发者的完美选择。 |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | 调整图像大小。 |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | 按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | 在保持宽高比的同时调整图像高度，使用此<br/>用户友好方法。非常适合希望动态调整图像大小<br/>并保持比例的开发者，确保在其应用程序中实现最佳显示和可用性<br/>。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | 按比例调整高度。 |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | 按比例调整高度。 |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_93) | 使用此便捷方法在保持宽高比的同时调整图像大小。非常适合希望按比例调整图像尺寸、确保一致性并保留原始内容比例的开发者。<br/>            比例缩放将根据 _newWidth_/width 和 _newHeight_/height 的比例来调整每个帧的大小。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | 按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | 在保持宽高比的同时调整图像宽度，使用此便捷<br/>方法。适用于希望按比例调整图像的开发者，确保<br/>在不同显示环境中获得一致且视觉上令人满意的结果。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | 按比例调整宽度。 |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | 按比例调整宽度。 |
| [rotate(angle)](#rotate_angle_98) | 围绕中心旋转图像。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | 使用此便捷方法围绕中心旋转图像。非常适合希望<br/>动态调整图像方向的开发者，确保在其应用程序中实现最佳呈现和<br/>对齐。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | 通过旋转、翻转或同时执行这两种操作<br/>来轻松操作活动帧，使用此直接方法。适用于需要<br/>在图像序列中动态调整特定帧方向的开发者，确保最佳呈现和对齐。 |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_101) | 旋转并翻转全部。 |
| save() | 将图像数据保存到底层流中。 |
| [save(file_path)](#save_file_path_102) | 将图像保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_103) | 通过将对象的数据保存到指定的文件（索引器 + 文件名）<br/>位置以及指定的文件格式和选项来保留对象的数据。非常适合希望<br/>在保持灵活性和对保存参数的控制的同时，安全地以各种格式存储数据的开发者。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_104) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, over_write)](#save_file_path_over_write_105) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_106) | 保存数据。 |
| [save(stream, options_base)](#save_stream_options_base_107) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_108) | 使用此便捷方法轻松将图像数据保存到指定流的所需文件格式<br/>中。无论您使用 JPEG、PNG 还是其他格式，<br/>此函数都能确保图像数据高效且准确地保存，<br/>使其成为希望简化文件保存流程的开发者的理想选择。 |
| [save_all(file_path, options)](#save_all_file_path_options_109) | 通过将对象的数据保存到指定的文件（索引器 + 文件名）<br/>位置以及指定的文件格式和选项来保留对象的数据。非常适合希望<br/>在保持灵活性和对保存参数的控制的同时，安全地以各种格式存储数据的开发者。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | 保存 32 位 ARGB 像素。 |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | 保存像素。 |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | 保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | 保存像素（特定格式方法）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | 保存原始数据。 |
| [save_to_stream(stream)](#save_to_stream_stream_115) | 将对象的数据保存到指定的流中。 |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_121) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_122) | 为指定位置设置图像像素。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | 使用此<br/>            简单方法精确调整此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的分辨率。非常适合希望根据<br/>            特定需求定制图像分辨率的开发者，确保最佳显示质量和文件大小管理。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | 将整条扫描线写入指定的扫描线索引。 |


### Constructor: DicomImage(dicom_options, width, height) {#DicomImage_dicom_options_width_height_1}


```
 DicomImage(dicom_options, width, height) 
```

使用此<br/>构造函数轻松初始化 DicomImage 类的新实例，利用 dicomOptions 参数。非常适合希望在项目中快速高效地深入使用 [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) 对象的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dicom_options | [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) | dicom 选项。 |
| width | int | 宽度。 |
| height | int | 高度。 |

### Constructor: DicomImage(stream) {#DicomImage_stream_2}


```
 DicomImage(stream) 
```

通过在此构造函数中使用流参数<br/>创建 DicomImage 类的新实例。非常适合希望以简化方式从现有数据流初始化 [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) 对象的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |


**See also:**

**[Example # 1](#example_130)**: This example shows how to load a DICOM image from a file stream.


### Constructor: DicomImage(stream, load_options) {#DicomImage_stream_load_options_3}


```
 DicomImage(stream, load_options) 
```

通过在此构造函数中使用流和<br/>loadOptions 参数，顺畅地启动 DicomImage 类的新实例。理想的选择是渴望在项目中快速有效地使用 [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) 对象的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | 加载选项。 |


**See also:**

**[Example # 1](#example_131)**: This example shows how to load a DICOM image from a file stream to stay withi...


### Method: add_page() {#add_page__1}


```
 add_page() 
```

使用此直接方法将新页面追加到图像页面列表的末尾。<br/>            适用于希望动态扩展多页图像的开发者，确保图像内容的无缝<br/>            集成和组织。

**Returns**

| Type | Description |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | 新创建的 [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/)。 |


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

通过此直观方法添加新页面，扩展您的图像集合。<br/>            适用于希望动态追加页面到多页图像的开发者，<br/>            确保图像内容的无缝扩展和组织。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 要添加的页面。 |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

通过调整 _brightness_ 来增强图像亮度，<br/>            这是一种参数化方法，允许开发者精细调节图像的光照度。<br/>            该用户友好功能使开发者能够无缝操作图像<br/>            亮度，提供对视觉美感的灵活性和控制。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 亮度 | int | 亮度值。 |


**See also:**

**[Example # 1](#example_143)**: The following example performs brightness correction of a DICOM image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

使用此用户友好的方法增强 [Image](/imaging/python-net/aspose.imaging/image/) 对比度，<br/>            该方法调整光暗区域之间的差异。轻松提升视觉清晰度和<br/>            细节定义，为开发者提供直观的图像对比度控制，以实现最佳渲染。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 对比度 | float | 对比度值（范围为 [-100; 100]） |


**See also:**

**[Example # 1](#example_144)**: The following example performs contrast correction of a DICOM image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

使用伽马校正提升图像质量并进行调整，这是一种强大的技术<br/>            用于微调视觉外观。非常适合希望优化图像<br/>            展示、调整色彩平衡，并确保在不同<br/>            设备和环境中保持一致渲染的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 伽马 | float | 红、绿、蓝通道的伽马系数 |


**See also:**

**[Example # 1](#example_141)**: The following example performs gamma-correction of a DICOM image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

通过对图像的红、绿、蓝分量独立应用伽马校正，实现精确的颜色调整。此方法确保准确的<br/>            色彩平衡和最佳的视觉输出，满足寻求对图像渲染和颜色精度进行细粒度<br/>            控制的开发者需求。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| gamma_red | float | 红色通道的伽马系数 |
| gamma_green | float | 绿色通道的伽马系数 |
| gamma_blue | float | 蓝色通道系数的 Gamma |


**See also:**

**[Example # 1](#example_142)**: The following example performs gamma-correction of a DICOM image applying dif...


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

使用 Bradley 的自适应阈值算法进行图像二值化，利用积分<br/>            图阈值提升性能。非常适合希望<br/>            根据局部亮度变化自动分割图像的开发者，确保在不同光照条件下的<br/>            准确目标检测和提取。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| brightness_difference | float | 像素与以该像素为中心的 s x s 像素窗口的平均值之间的亮度差<br/>            。 |
| window_size | int | 以该像素为中心的 s x s 像素窗口的大小 |


**See also:**

**[Example # 1](#example_139)**: The following example binarizes a DICOM image with Bradley's adaptive thresho...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

使用预定义阈值将图像轻松转换为二进制格式<br/>            的直接方法。非常适合希望通过根据指定强度水平将图像分割为前景和背景组件来简化图像<br/>            处理任务的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 阈值 | System.Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为<br/>            255，否则为 0。 |


**See also:**

**[Example # 1](#example_137)**: The following example binarizes a DICOM image with the predefined threshold. ...


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


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

通过使用此多功能方法应用位移来调整图像的裁剪区域。<br/>            非常适合需要对裁剪过程进行精确控制的开发者，确保保留重要细节，同时消除不必要的元素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| left_shift | int | 左移。 |
| right_shift | int | 右移。 |
| top_shift | int | 上移。 |
| bottom_shift | int | 下移。 |


**See also:**

**[Example # 1](#example_136)**: The following example crops a DICOM image. The cropping area is specified via...


### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

使用此<br/>            简单方法裁剪图像，以去除不需要的区域并聚焦于关键内容。非常适合希望自定义图像视觉构图的开发者，确保图像有效传达预期信息。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |


**See also:**

**[Example # 1](#example_135)**: The following example crops a DICOM image. The cropping area is be specified ...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

通过使用此直接的<br/>            方法对当前图像应用抖动效果来增强图像。非常适合希望为图像添加纹理和深度的开发者，提升其视觉质量和整体吸引力。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 用于抖动的自定义调色板。 |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

根据提供的密码将数字签名嵌入图像的每一页。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于生成数字签名数据的密码 |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

通过对指定的<br/>            矩形应用滤镜，轻松增强图像的特定区域。此方法为开发者提供对图像操作的精确控制，能够进行有针对性的调整，以轻松实现期望的视觉效果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | 选项。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


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


### Method: get_default_options(args) {#get_default_options_args_40}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。

**Returns**

| Type | Description |
| :- | :- |
| float | 倾斜角度（单位：度）。 |


### Method: insert_page(page_index) {#insert_page_page_index_56}


```
 insert_page(page_index) 
```

使用此直观的<br/>            方法在指定索引处向图像的页面列表插入新页面。非常适合希望对多页图像中页面排列进行精确控制的开发者，确保图像内容的无缝组织和自定义。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page_index | int | 页面索引。 |

**Returns**

| Type | Description |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | 新创建的 [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/)。 |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


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


### Method: load(file_path)  [static] {#load_file_path_58}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


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


### Method: load(stream)  [static] {#load_stream_60}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

部分加载 32 位 ARGB 像素（按块）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

按包部分加载 64 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

按包部分加载像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | 像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


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


### Method: remove_page(page_index) {#remove_page_page_index_78}


```
 remove_page(page_index) 
```

使用此便捷方法从页面列表中删除指定索引处的页面。<br/>            非常适合希望对多页图像的管理进行精确控制的开发者，确保图像内容的无缝组织和自定义。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| page_index | int | 页面索引。 |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。<br/>                注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color_argb | int | 用于替换非透明颜色的新颜色 ARGB 值。 |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

使用此便捷方法在保持宽高比的同时调整图像大小。非常适合希望按比例调整图像尺寸、确保一致性并保留原始内容比例的开发者。<br/>            比例缩放将根据 _newWidth_/width 和 _newHeight_/height 的比例来调整每个帧的大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小类型。 |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

使用此简单的调整大小方法来调整图像尺寸。无论您需要<br/>缩小或放大图像，此函数都能确保满足您的调整大小需求<br/>高效且准确，使其成为寻求快速简便<br/>图像尺寸调整的开发者的完美选择。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 调整大小设置。 |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

在保持宽高比的同时调整图像高度，使用此<br/>用户友好方法。非常适合希望动态调整图像大小<br/>并保持比例的开发者，确保在其应用程序中实现最佳显示和可用性<br/>。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

按比例调整高度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_93}


```
 resize_proportional(new_width, new_height, resize_type) 
```

使用此便捷方法在保持宽高比的同时调整图像大小。非常适合希望按比例调整图像尺寸、确保一致性并保留原始内容比例的开发者。<br/>            比例缩放将根据 _newWidth_/width 和 _newHeight_/height 的比例来调整每个帧的大小。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小类型。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

在保持宽高比的同时调整图像宽度，使用此便捷<br/>方法。适用于希望按比例调整图像的开发者，确保<br/>在不同显示环境中获得一致且视觉上令人满意的结果。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

使用此便捷方法围绕中心旋转图像。非常适合希望<br/>动态调整图像方向的开发者，确保在其应用程序中实现最佳呈现和<br/>对齐。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将被更改<br/>            根据旋转矩形（角点）的投影在其他<br/>            情况下，尺寸保持不变，仅<br/>            __internal__ 图像内容被旋转。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

通过旋转、翻转或同时执行这两种操作<br/>来轻松操作活动帧，使用此直接方法。适用于需要<br/>在图像序列中动态调整特定帧方向的开发者，确保最佳呈现和对齐。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转类型。 |


**See also:**

**[Example # 1](#example_132)**: This example loads a DICOM image, rotates it by 90 degrees clockwise and opti...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_101}


```
 rotate_flip_all(rotate_flip) 
```

旋转并翻转全部。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转。 |

### Method: save(file_path) {#save_file_path_102}


```
 save(file_path) 
```

将图像保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存图像的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_103}


```
 save(file_path, options) 
```

通过将对象的数据保存到指定的文件（索引器 + 文件名）<br/>位置以及指定的文件格式和选项来保留对象的数据。非常适合希望<br/>在保持灵活性和对保存参数的控制的同时，安全地以各种格式存储数据的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_104}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_105}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，覆盖文件内容，否则将追加。 |

### Method: save(stream) {#save_stream_106}


```
 save(stream) 
```

保存数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存数据的流。 |

### Method: save(stream, options_base) {#save_stream_options_base_107}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_108}


```
 save(stream, options_base, bounds_rectangle) 
```

使用此便捷方法轻松将图像数据保存到指定流的所需文件格式<br/>中。无论您使用 JPEG、PNG 还是其他格式，<br/>此函数都能确保图像数据高效且准确地保存，<br/>使其成为希望简化文件保存流程的开发者的理想选择。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 目标图像边界矩形。将空矩形设置为使用源边界。 |


**See also:**

**[Example # 1](#example_133)**: The following example loads a DICOM image from a file, then saves the image t...


### Method: save_all(file_path, options) {#save_all_file_path_options_109}


```
 save_all(file_path, options) 
```

通过将对象的数据保存到指定的文件（索引器 + 文件名）<br/>位置以及指定的文件格式和选项来保留对象的数据。非常适合希望<br/>在保持灵活性和对保存参数的控制的同时，安全地以各种格式存储数据的开发者。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

保存像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 以 32 位整数值表示的 CMYK 像素。 |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

保存像素（特定格式方法）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 像素数组。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_121}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，未更改的索引如果在加载时没有对应的调色板条目，可能会导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_122}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_123}


```
 set_resolution(dpi_x, dpi_y) 
```

使用此<br/>            简单方法精确调整此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的分辨率。非常适合希望根据<br/>            特定需求定制图像分辨率的开发者，确保最佳显示质量和文件大小管理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dpi_x | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率。 |
| dpi_y | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率。 |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_124}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int[] | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_126}


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
### This example shows how to load a DICOM image from a file stream. {#example_130}
``` python
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# 从文件流加载 DICOM 图像。
with open(join(dir_, "sample.dicom"), "rb") as stream:
	with DicomImage(stream) as dicom_image:
		# 将每页保存为单独的 PNG 图像。
		for dicom_page in dicom_image.dicom_pages:
			# 根据页索引生成文件名。
			file_name = "sample.{0}.png".format(dicom_page.index)
			# DICOM 页面是光栅图像，因此对光栅图像的所有允许操作都适用于 DICOM 页面。
			dicom_page.save(join(dir_, file_name), PngOptions())


```

### This example shows how to load a DICOM image from a file stream to stay within the specified memory limit. {#example_131}
``` python
from aspose.imaging import LoadOptions, Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join as path_join


dir_: str = "c:\\temp"
# 从文件流加载 DICOM 图像。
with open(path_join(dir_, "multiframe.dicom"), "rb") as stream:
	# 所有内部缓冲区允许的最大大小为 256KB。
	load_options = LoadOptions()
	load_options.buffer_size_hint = 256 * 1024
	with DicomImage(stream, load_options) as dicom_image:
		# 将每页保存为单独的 PNG 图像。
		for dicom_page in dicom_image.dicom_pages:
			# 根据页索引生成文件名。
			file_name = "multiframe.{0}.png".format(dicom_page.index)
			# DICOM 页面是光栅图像，因此对光栅图像的所有允许操作都适用于 DICOM 页面。
			dicom_page.save(path_join(dir_, file_name), PngOptions())


```

### This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_132}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# 旋转、翻转并保存到输出文件。
	with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a DICOM image from a file, then saves the image to a PNG file stream. {#example_133}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions     

dir_: str = "c:\\temp"
with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width // 2, image.height // 2)
	with open(join(dir_, "output.png"), "wb") as output_stream:
		# 将图像的左上四分之一保存到文件流。
		image.save(output_stream, save_options, bounds)


```

### The following example crops a DICOM image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_135}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions    


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 裁剪图像。裁剪区域是图像的矩形中心区域。
	area = Rectangle(dicom_image.width // 4, dicom_image.height // 4, dicom_image.width // 2, dicom_image.height // 2)
	dicom_image.crop(area)
	# 将裁剪后的图像保存为 PNG。
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a DICOM image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_136}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 再次裁剪。设置图像大小的10%边距。
	horizontal_margin = dicom_image.width // 10
	vertical_margin = dicom_image.height // 10
	dicom_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# 将裁剪后的图像保存为 PNG。
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a DICOM image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_137}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 使用阈值127对图像进行二值化。
	# 如果像素的对应灰度值大于127，则赋值为255，否则为0。
	dicom_image.binarize_fixed(127)
	dicom_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_139}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 使用亮度差5对图像进行二值化。亮度是指像素与以该像素为中心的10×10窗口像素平均值之间的差异。
	dicom_image.binarize_bradley(5, 10)
	dicom_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image. {#example_141}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 设置红、绿、蓝通道的伽马系数。
	dicom_image.adjust_gamma(2.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image applying different coefficients for color components. {#example_142}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 为红、绿、蓝通道分别设置伽马系数。
	dicom_image.adjust_gamma(1.5, 2.5, 3.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a DICOM image. {#example_143}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 设置亮度值。亮度的可接受范围为 [-255, 255]。
	dicom_image.adjust_brightness(50)
	dicom_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a DICOM image. {#example_144}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# 设置对比度值。对比度的可接受范围为 [-100f, 100f]。
	dicom_image.adjust_contrast(50.0)
	dicom_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Use JPEG compression in DICOM image. {#example_211}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions, DicomOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode, SampleRoundingMode
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import Compression, ColorType, CompressionType

with Image.load("original.jpg") as input_image:
	obj_init = JpegOptions()
	obj_init.compression_type = JpegCompressionMode.BASELINE
	obj_init.sample_rounding_mode = SampleRoundingMode.TRUNCATE
	obj_init.quality = 50
	obj_init2 = Compression()
	obj_init2.type = CompressionType.JPEG
	obj_init2.jpeg = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG.dcm", options)


```

### Use JPEG 2000 compression in DICOM image. {#example_212}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import Jpeg2000Options, DicomOptions
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Compression, CompressionType, ColorType

with Image.load("original.jpg") as input_image:
	obj_init = Jpeg2000Options()
	obj_init.codec = Jpeg2000Codec.JP2
	obj_init.irreversible = False
	obj_init2 = Compression()
	obj_init2.type_ = CompressionType.JPEG2000
	obj_init2.jpeg2000 = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG2000.dcm", options)


```

### Use RLE compression in DICOM image. {#example_213}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import Compression, CompressionType, ColorType
from aspose.imaging.imageoptions import DicomOptions

with Image.load("original.jpg") as input_image:
	compr = Compression()
	compr.type_ = CompressionType.RLE
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = compr
	input_image.save("original_RLE.dcm", options)


```

### Change the color type in DICOM compression. {#example_214}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import ColorType

with Image.load("original.jpg") as inputImage:
	options = DicomOptions()
	options.color_type = ColorType.GRAYSCALE_8_BIT
	inputImage.save("original_8Bit.dcm", options)


```

