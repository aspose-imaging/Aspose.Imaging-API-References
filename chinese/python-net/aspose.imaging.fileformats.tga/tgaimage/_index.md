---
title: "TgaImage 类"
type: docs
weight: 10
url: /zh/python-net/aspose.imaging.fileformats.tga/tgaimage/
---

**Summary:** Manipulate TGA raster image files with our API, tailored for the TARGA<br/>            (Truevision Advanced Raster Adapter) format, enabling seamless loading and<br/>            customization. Easily update public properties such as author, timestamp,<br/>            image ID, and software version, while using various bits per pixel settings,<br/>            alpha channel and color transparency. Additionally, you can export TGA images<br/>            to other popular raster formats, ensuring compatibility for your projects.

**Module:** [aspose.imaging.fileformats.tga](/imaging/python-net/aspose.imaging.fileformats.tga/)

**Full Name:** aspose.imaging.fileformats.tga.TgaImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [TgaImage(path)](#TgaImage_path_1) | 使用提供的文件路径初始化一个新的 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 对象，用于 <br/>            加载图像内容。此构造函数高效地初始化图像 <br/>            实例，允许无缝访问 TGA 图像文件，简化了在您的应用程序工作流中的集成。 |
| [TgaImage(raster_image)](#TgaImage_raster_image_2) | 通过提供光栅 <br/>            图像对象，创建 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。此构造函数促进了现有光栅图像直接集成到 TGA 图像格式中，简化了转换过程，以提升您软件系统的兼容性。 |
| [TgaImage(stream)](#TgaImage_stream_3) | 使用流来 <br/>            加载图像，初始化 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。此构造函数允许从流中无缝集成图像数据，促进在您的软件应用程序中高效处理和操作 TGA 图像。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| author_comments | string | r/w | 检索或设置图像作者提供的注释。这些注释 <br/>            通常包含有价值的信息，如描述、标注或 <br/>            关于图像的额外上下文。通过访问或修改 Author Comments <br/>            属性，开发者可以增强与图像关联的元数据，为用户提供有关其内容或创建的有价值的洞察和上下文。<br/>            这是一个 ASCII 字段，长度为 324 字节，组织为四行 <br/>            每行 80 个字符，后跟空字符终止符。 |
| author_name | string | r/w | 检索或设置与图像关联的作者姓名。此属性 <br/>            允许开发者访问或修改作者姓名元数据，提供关于图像创作者的有价值信息。通过使用 Author Name <br/>            属性，用户可以轻松识别负责创建或 <br/>            贡献图像的个人，提升整体元数据并为观众提供有价值的 <br/>            上下文。<br/>            此字段共计 40 个 ASCII 字符用于存放姓名。如果使用该字段，<br/>            应包含创建图像的人的姓名（作者）。 |
| auto_adjust_palette | bool | r/w | 获取或设置一个值，指示是否自动调整调色板。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 检索或设置图像的背景颜色。此属性允许 <br/>            您指定用于图像背景的颜色，确保一致性并 <br/>            增强视觉呈现。它在图像显示在不同颜色的背景上或在将图像渲染到另一个画布时尤为有用。 |
| bits_per_pixel | int | r | 检索每像素位数值，提供关于图像 <br/>            色彩深度的关键信息。此属性是了解 <br/>            图像细节层次和色彩丰富度的重要指标，帮助开发者在 <br/>            优化处理算法和资源分配以实现高效图像 <br/>            操作和渲染任务时提供参考。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | 获取对象的边界。 |
| buffer_size_hint | int | r/w | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| bytes_per_pixel | int | r | 获取每像素字节数值，表示图像中每个像素占用的内存量。此属性是内存 <br/>            管理和优化的关键指标，帮助开发者高效分配资源 <br/>            并处理图像数据。 |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | 获取 [Image](/imaging/python-net/aspose.imaging/image/) 容器。 |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | 获取对象的数据流。 |
| date_time_stamp | System.Nullable`1[[System.DateTime]] | r/w | 获取或设置日期/时间戳。<br/>            此字段定义图像保存时的日期和时间值。 <br/>            虽然操作系统通常会为文件添加时间和日期戳，但提供此功能是因为如果文件被 <br/>            复制，操作系统可能会更改时间和日期戳。使用此区域，可确保日期和时间记录的区域保持未修改。 |
| disposed | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | 获取或设置 Exif 实例。 |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | 获取此 <br/>            [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 实例所表示图像的文件格式的关键信息。了解文件格式对于 <br/>            兼容性检查和确保在软件系统中无缝集成至关重要，<br/>            使图像的高效处理和操作成为可能。 |
| gamma_value_denominator | int | r | 检索伽马值的分母部分，这是决定图像颜色表示的关键因素。对于缺少伽马 <br/>            校正的图像，此值应为 1.0，以确保准确的颜色渲染。<br/>            理解并利用此参数是保持颜色 <br/>            保真度和实现精确图像可视化的基础。 |
| gamma_value_numerator | int | r | 获取伽马值的分子部分，这对于图像的准确颜色 <br/>            表示至关重要。在没有伽马校正的图像中，此值应为 <br/>            1.0。理解并使用该值对于保持颜色 <br/>            保真度和确保准确的图像渲染至关重要。 |
| has_alpha | bool | r | 检索一个布尔值，指示 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 是否包含 <br/>            alpha 通道，以实现透明效果。此属性提供处理图像合成和渲染的关键 <br/>            信息，帮助开发者实现多样的视觉效果和合成操作。 |
| has_background_color | bool | r/w | 检索或设置一个值，指示图像是否包含背景 <br/>            颜色。此属性用于判断图像是否具有与前景内容分离的 <br/>            明显背景颜色。它使您能够根据是否存在背景颜色来自定义图像处理或渲染。 |
| has_color_map | bool | r | 检索此 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 实例是否包含颜色映射表。<br/>            了解颜色映射表的存在对于准确解释 <br/>            和操作图像的颜色数据至关重要。 |
| has_transparent_color | bool | r/w | 检索或设置一个布尔值，指示图像是否包含 <br/>            透明颜色。此属性对于识别图像是否支持透明度至关重要，帮助您实现适当的透明度相关操作处理，如混合、合成或遮罩。 |
| height | int | r | 获取此 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            实例所封装图像的高度。此属性为开发者提供有关图像垂直尺寸的关键细节，<br/>            使其能够在软件解决方案中实现无缝集成和图像操作。 |
| horizontal_resolution | float | r/w | 获取或设置此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率（每英寸像素数）。 |
| image_id | string | r/w | 获取或设置与图像关联的唯一标识符。此 ID 作为 <br/>            用于在系统或应用程序中识别和区分图像的参考点。通过设置或检索 Image ID，您可以有效管理和 <br/>            跟踪图像，促进有序的图像管理和检索过程。<br/>            <br/>此可选字段包含图像的标识信息。该字段的最大长度为 255 字节。<br/> |
| image_opacity | float | r | 获取此图像的不透明度。 |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取指示图像数据当前是否已缓存的值。 |
| is_gray_scale | bool | r | 获取一个布尔值，指示此 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 是否表示 <br/>            灰度图像。此属性对于区分彩色图像和灰度图像至关重要，帮助开发者根据图像的颜色特性应用适当的处理和 <br/>            渲染技术。 |
| is_raw_data_available | bool | r | 获取指示是否支持原始数据加载的值。 |
| job_name_or_id | string | r/w | 获取或设置与图像关联的作业名称或 ID。此属性 <br/>            使您能够访问或修改与图像关联的特定作业或项目的元数据。通过使用作业名称/ID 属性，用户可以轻松 <br/>            确定图像所属的项目或任务，促进在更大工作流或项目中对图像资产的组织和管理。 |
| job_time | System.Nullable`1[[System.TimeSpan]] | r/w | 获取或设置指示与图像关联的作业时间的时间戳。<br/>            此属性允许开发者访问或修改与图像关联的特定作业或项目的时间元数据。 |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | 获取图像元数据。 |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| pixel_aspect_ratio_denominator | int | r | 获取像素纵横比的分母部分，这是在 <br/>            确定图像内像素视觉比例时的关键因素。此值对于在各种图像渲染和处理操作中保持准确的像素表示和纵横比至关重要，<br/>            确保高质量的视觉输出。 |
| pixel_aspect_ratio_numerator | int | r | 获取像素纵横比的分子组件，它影响 <br/>            图像内像素的视觉比例。理解并操作此 <br/>            值对于在图像渲染和处理时实现准确的像素表示和纵横比至关重要。 |
| premultiply_components | bool | r/w | 获取或设置一个值，指示图像组件是否必须进行预乘。 |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | 获取或设置自定义颜色转换器 |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | 获取原始数据格式。 |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | 获取当前原始数据设置。注意，使用这些设置时，数据将在不进行转换的情况下加载。 |
| raw_fallback_index | int | r/w | 获取或设置当调色板索引超出范围时使用的回退索引 |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | 获取或设置索引颜色转换器 |
| raw_line_size | int | r | 获取以字节为单位的原始行大小。 |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | 获取对象大小。 |
| software_id | string | r/w | 管理与图像关联的软件标识（ID），允许最多 <br/>            40 个 ASCII 字符。此属性作为唯一标识在创建或处理图像时使用的软件的手段，为组织和信息目的提供有价值的元数据。 |
| software_version | string | r/w | 获取或设置与图像关联的软件版本。版本字符串的长度通常为 3 到 4 个字符。<br/>            此属性有助于跟踪用于创建或处理图像的软件，并可为图像处理和兼容性检查提供有价值的上下文。 |
| software_version_letter | System.Char | r/w | 获取或设置与图像关联的软件版本的字母部分。此属性在软件版本字符串中提供 <br/>            额外细节，可用于更细致的版本区分。 |
| software_version_number | int | r/w | Retrieves or sets the numeric component of the software version associated with the image. This property represents the numerical part of the software version string, providing important information about the version of the software used to create or modify the image. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | 获取或设置与图像关联的关键颜色。此属性允许 <br/>            您访问或修改指定为特定图像处理任务或效果的关键颜色。使用关键颜色属性可让用户 <br/>            应用基于颜色的操作，如色度键或颜色替换，增强图像操作能力和创意可能性。<br/>            <br/>关键颜色可视为“背景色”或“透明色”。<br/>            它是屏幕上“非图像”区域的颜色，也是应用程序中擦除时屏幕将被清除到的相同颜色。<br/> |
| update_xmp_data | bool | r/w | 获取或设置一个值，指示是否更新 XMP 元数据。 |
| use_palette | bool | r | 获取一个值，指示是否使用图像调色板。 |
| use_raw_data | bool | r/w | 获取或设置一个值，指示在可用原始数据加载时是否使用原始数据加载。 |
| vertical_resolution | float | r/w | 获取或设置此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率（每英寸像素数）。 |
| width | int | r | 获取此 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            实例所表示图像的宽度。此属性为开发者提供有关图像尺寸的基本信息，帮助在其软件应用程序中进行各种图像操作和处理任务。 |
| x_origin | int | r/w | 获取或设置图像左下角的绝对水平坐标<br/>            当它位于原点在屏幕左下角的显示设备上时<br/>            （例如 TARGA 系列）。 |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | 获取或设置 Xmp 数据。 |
| y_origin | int | r/w | 获取或设置图像左下角的绝对垂直坐标<br/>            当它位于原点在屏幕左下角的显示设备上时<br/>            （例如 TARGA 系列）。 |
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
| [clone()](#clone__19) | 生成当前实例的副本，创建一个克隆原始所有属性和特性的新对象。<br/>            此方法有助于创建完全相同的拷贝，确保数据完整性并保留当前实例的状态，<br/>            而不影响原始对象。 |
| [clone(tga_image)](#clone_tga_image_20) | 复制另一个 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 对象的属性，创建一个 <br/>            具有相同属性的新实例。此操作确保数据完整性 <br/>            并在不更改源对象的情况下实现图像属性的复制。 |
| [create(files)](#create_files_21) | 创建包含指定文件的多页图像。 |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | 创建包含指定文件的多页图像。 |
| [create(image_options, width, height)](#create_image_options_width_height_23) | 使用指定的创建选项创建新图像。 |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | 创建一个来自提供的像素数组的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 实例。<br/>            <br/>            验证指定的宽度和高度是否与像素数据的维度匹配。<br/>            仅当库处于授权模式时才能使用此方法。 |
| [create(images)](#create_images_25) | 使用指定的图像作为页面创建新图像。 |
| [create(images, dispose_images)](#create_images_dispose_images_26) | 创建一个新图像，将指定的图像作为页面。 |
| [create(multipage_create_options)](#create_multipage_create_options_27) | 创建指定的多页创建选项。 |
| [create_from_files(files)](#create_from_files_files_28) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | 创建包含指定文件的多页图像，将其作为延迟加载页面。 |
| [create_from_image(raster_image)](#create_from_image_raster_image_30) | 初始化 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。 |
| [create_from_images(images)](#create_from_images_images_31) | 使用指定的图像作为页面创建新图像。 |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | 创建一个新图像，将指定的图像作为页面。 |
| [create_from_stream(stream)](#create_from_stream_stream_33) | 初始化 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。 |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_34) | 通过指定左、右、上、下的偏移来裁剪图像 <br/>            边界。此方法允许您通过在水平和垂直轴上独立移动其边界来修剪图像 <br/>            。通过调整这些偏移，<br/>            您可以精确控制要保留的图像部分，<br/>            有效地将其裁剪到所需的尺寸。 |
| [crop(rectangle)](#crop_rectangle_35) | 将图像裁剪到指定区域。此方法允许您定义图像内要保留的 <br/>            矩形区域，丢弃其余部分。此操作 <br/>            对于聚焦图像中的特定内容或去除不需要的 <br/>            部分非常有用。 |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | 对当前图像执行抖动处理。 |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | 对当前图像执行抖动处理。 |
| [embed_digital_signature(password)](#embed_digital_signature_password_38) | 使用隐写术将基于提供的密码的数字签名嵌入图像中。 |
| [filter(rectangle, options)](#filter_rectangle_options_39) | 过滤指定的矩形区域。 |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_40) | 获取图像的 32 位 ARGB 像素。 |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_41) | 获取默认的 32 位 ARGB 像素数组。 |
| [get_default_options(args)](#get_default_options_args_42) | 获取默认选项。 |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_43) | 使用部分像素加载器获取默认像素数组。 |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44) | 使用部分像素加载器获取默认原始数据数组。 |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_45) | 获取默认原始数据数组。 |
| [get_file_format(file_path)](#get_file_format_file_path_46) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_47) | 获取文件格式。 |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_48) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_49) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_50) | 获取适合当前图像的矩形。 |
| [get_modify_date(use_default)](#get_modify_date_use_default_51) | 获取资源图像最后修改的日期和时间。 |
| [get_original_options()](#get_original_options__52) | 根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。 |
| [get_pixel(x, y)](#get_pixel_x_y_53) | 获取图像像素。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_54) | 获取比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_55) | 获取比例宽度。 |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_56) | 转换为 aps。 |
| [get_skew_angle()](#get_skew_angle__57) | 获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。 |
| grayscale() | 将图像转换为灰度表示 |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_58) | 使用提供的密码和阈值执行快速检查，以确定图像是否已数字签名。 |
| [load(file_path)](#load_file_path_59) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(file_path, load_options)](#load_file_path_load_options_60) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| [load(stream)](#load_stream_61) | 从指定的流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_62) | 从指定的流加载新图像。 |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_63) | 加载 32 位 ARGB 像素。 |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_64) | 加载 64 位 ARGB 像素。 |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_65) | 加载 CMYK 格式的像素。 |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_66) | 加载 CMYK 格式的像素。<br/>            此方法已弃用。请使用更有效的 [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67) | 部分加载 32 位 ARGB 像素（按块）。 |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68) | 按包部分加载 64 位 ARGB 像素。 |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_69) | 按包部分加载像素。 |
| [load_pixels(rectangle)](#load_pixels_rectangle_70) | 加载像素。 |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71) | 加载原始数据。 |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72) | 加载原始数据。 |
| [load_stream(stream)](#load_stream_stream_73) | 从指定的流加载新图像。 |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_74) | 从指定的流加载新图像。 |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_75) | 从指定的文件路径或 URL 加载新图像。<br/>            如果 _filePath_ 是文件路径，方法仅打开该文件。<br/>            如果 _filePath_ 是 URL，方法会下载文件，将其存为临时文件，然后打开它。 |
| normalize_angle() | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_76) | 归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| normalize_histogram() | 归一化图像直方图 — 调整像素值以使用全部可用范围。 |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_77) | 按指定的扫描线索引读取整条扫描线。 |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_78) | 按指定的扫描线索引读取整条扫描线。 |
| remove_metadata() | 通过将此 [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) 值设置为 **None** 来移除此图像实例的元数据。 |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | 在允许的差异范围内将一种颜色替换为另一种颜色，并保留原始 alpha 值以保持平滑边缘。 |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | 将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | 使用指定的缩放类型调整图像大小，该类型决定了 <br/>            缩放操作的执行方式。此方法在 <br/>            根据不同的算法或技术对图像进行缩放时提供了灵活性。通过选择 <br/>            合适的缩放类型，您可以实现图像质量与 <br/>            计算效率之间的理想平衡，满足特定需求或偏好。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | 在应用特定设置以保持所需的 <br/>            尺寸和宽高比的同时调整图像大小。通过自定义图像设置，您可以有效地 <br/>            调整图像大小，同时确保最佳的视觉质量并兼容不同的显示设备或应用程序。 |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | 调整图像大小。 |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | 按比例调整高度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | 按比例调整高度。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | 按比例调整高度。 |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | 按比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_93) | 按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_94) | 按比例调整宽度。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_95) | 按比例调整宽度。 |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_96) | 按比例调整宽度。 |
| [rotate(angle)](#rotate_angle_97) | 围绕中心旋转图像。 |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_98) | 围绕图像中心以指定角度旋转图像，同时保持缩放 <br/>            比例并保留背景颜色。此方法允许 <br/>            精确的图像操作，确保旋转保持视觉平衡 <br/>            并与指定的背景颜色保持一致。它非常适合需要 <br/>            围绕中心精确旋转的任务，例如方向校正 <br/>            或艺术调整。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_99) | "RotateFlip" 方法可对图像进行旋转和翻转操作。它 <br/>            提供了多功能的图像方向操作，允许用户 <br/>            根据需求执行旋转和翻转，促进 <br/>            在软件应用中高效的图像处理任务。 |
| save() | 将图像数据保存到底层流中。 |
| [save(file_path)](#save_file_path_100) | 将图像保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_101) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_102) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save(file_path, over_write)](#save_file_path_over_write_103) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_104) | 保存的数据。 |
| [save(stream, options_base)](#save_stream_options_base_105) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_106) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_107) | 保存 32 位 ARGB 像素。 |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_108) | 保存像素。 |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_109) | 保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。 |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_110) | 保存像素（特定格式方法）。 |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_111) | 保存原始数据。 |
| [save_to_stream(stream)](#save_to_stream_stream_112) | 将对象的数据保存到指定的流中。 |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_113) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114) | 根据保存选项，将图像的数据保存到指定流中的指定文件格式。 |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_115) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_116) | 根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。 |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_117) | 为指定位置设置图像的 32 位 ARGB 像素。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_118) | 设置图像调色板。 |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_119) | 为指定位置设置图像像素。 |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_120) | 为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。 |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_121) | 尝试设置一个 _metadata_ 实例，前提是此 [Image](/imaging/python-net/aspose.imaging/image/) 实例支持并实现 [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) 实例。 |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122) | 将整条扫描线写入指定的扫描线索引。 |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_123) | 将整条扫描线写入指定的扫描线索引。 |


### Constructor: TgaImage(path) {#TgaImage_path_1}


```
 TgaImage(path) 
```

使用提供的文件路径初始化一个新的 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 对象，用于 <br/>            加载图像内容。此构造函数高效地初始化图像 <br/>            实例，允许无缝访问 TGA 图像文件，简化了在您的应用程序工作流中的集成。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 路径 | string | 加载图像的路径。 |

### Constructor: TgaImage(raster_image) {#TgaImage_raster_image_2}


```
 TgaImage(raster_image) 
```

通过提供光栅 <br/>            图像对象，创建 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。此构造函数促进了现有光栅图像直接集成到 TGA 图像格式中，简化了转换过程，以提升您软件系统的兼容性。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |


**See also:**

**[Example # 1](#example_216)**: Loading of the PNG image, conversion of it to the TgaImage and saving as a TG...


### Constructor: TgaImage(stream) {#TgaImage_stream_3}


```
 TgaImage(stream) 
```

使用流来 <br/>            加载图像，初始化 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。此构造函数允许从流中无缝集成图像数据，促进在您的软件应用程序中高效处理和操作 TGA 图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |

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


### Method: clone() {#clone__19}


```
 clone() 
```

生成当前实例的副本，创建一个克隆原始所有属性和特性的新对象。<br/>            此方法有助于创建完全相同的拷贝，确保数据完整性并保留当前实例的状态，<br/>            而不影响原始对象。

**Returns**

| Type | Description |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | 返回当前实例的副本的新对象。 |


### Method: clone(tga_image) {#clone_tga_image_20}


```
 clone(tga_image) 
```

复制另一个 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 对象的属性，创建一个 <br/>            具有相同属性的新实例。此操作确保数据完整性 <br/>            并在不更改源对象的情况下实现图像属性的复制。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tga_image | [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | 其他 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |

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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_30}


```
 create_from_image(raster_image) 
```

初始化 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | 光栅图像。 |

**Returns**

| Type | Description |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


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

初始化 [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |

**Returns**

| Type | Description |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_34}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

通过指定左、右、上、下的偏移来裁剪图像 <br/>            边界。此方法允许您通过在水平和垂直轴上独立移动其边界来修剪图像 <br/>            。通过调整这些偏移，<br/>            您可以精确控制要保留的图像部分，<br/>            有效地将其裁剪到所需的尺寸。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| left_shift | int | 左移。 |
| right_shift | int | 右移。 |
| top_shift | int | 上移。 |
| bottom_shift | int | 下移。 |

### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

将图像裁剪到指定区域。此方法允许您定义图像内要保留的 <br/>            矩形区域，丢弃其余部分。此操作 <br/>            对于聚焦图像中的特定内容或去除不需要的 <br/>            部分非常有用。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

对当前图像执行抖动处理。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | 抖动方法。 |
| bits_count | int | 用于抖动的最终位计数。 |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_38}


```
 embed_digital_signature(password) 
```

使用隐写术将基于提供的密码的数字签名嵌入图像中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 密码 | string | 用于生成数字签名数据的密码 |

### Method: filter(rectangle, options) {#filter_rectangle_options_39}


```
 filter(rectangle, options) 
```

过滤指定的矩形区域。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 矩形。 |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | 选项。 |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_40}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_41}


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


### Method: get_default_options(args) {#get_default_options_args_42}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_43}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

使用部分像素加载器获取默认像素数组。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 用于获取像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_45}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_46}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_47}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_48}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_49}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_50}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_51}


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


### Method: get_original_options() {#get_original_options__52}


```
 get_original_options() 
```

根据原始文件设置获取选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一个每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) 方法。

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 基于原始文件设置的选项。 |


### Method: get_pixel(x, y) {#get_pixel_x_y_53}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_54}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_55}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_56}


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


### Method: get_skew_angle() {#get_skew_angle__57}


```
 get_skew_angle() 
```

获取倾斜角度。<br/>            此方法适用于扫描的文本文件，用于在扫描时确定倾斜角度。

**Returns**

| Type | Description |
| :- | :- |
| float | 倾斜角度（单位：度）。 |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_58}


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


### Method: load(file_path)  [static] {#load_file_path_59}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_60}


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


### Method: load(stream)  [static] {#load_stream_61}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_62}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_63}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_64}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_65}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_66}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

部分加载 32 位 ARGB 像素（按块）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 加载像素的矩形。 |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | 部分像素加载器。 |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

按包部分加载 64 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | 64 位 ARGB 像素加载器。 |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_69}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

按包部分加载像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 所需的矩形。 |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | 像素加载器。 |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_70}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_73}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_74}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_75}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_76}


```
 normalize_angle(resize_proportionally, background_color) 
```

归一化角度。<br/>            此方法适用于扫描的文本文档，以消除倾斜扫描。<br/>            此方法使用 [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) 和 [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_77}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_78}


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
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | 要被替换的旧颜色。 |
| old_color_diff | System.Byte | 允许的旧颜色差异，以便能够扩大替换颜色的色调。 |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | 用于替换旧颜色的新颜色。 |

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

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | 用于替换非透明颜色的新颜色。 |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。<br/>            注意：如果在没有透明度的图像上使用，它将把所有颜色替换为单一颜色。

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

使用指定的缩放类型调整图像大小，该类型决定了 <br/>            缩放操作的执行方式。此方法在 <br/>            根据不同的算法或技术对图像进行缩放时提供了灵活性。通过选择 <br/>            合适的缩放类型，您可以实现图像质量与 <br/>            计算效率之间的理想平衡，满足特定需求或偏好。

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

在应用特定设置以保持所需的 <br/>            尺寸和宽高比的同时调整图像大小。通过自定义图像设置，您可以有效地 <br/>            调整图像大小，同时确保最佳的视觉质量并兼容不同的显示设备或应用程序。

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

按比例调整高度。

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

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_93}


```
 resize_width_proportionally(new_width) 
```

按比例调整宽度。默认使用 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/)。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_94}


```
 resize_width_proportionally(new_width, resize_type) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_95}


```
 resize_width_proportionally(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_96}


```
 resize_width_proportionally_settings(new_width, settings) 
```

按比例调整宽度。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | 图像调整大小设置。 |

### Method: rotate(angle) {#rotate_angle_97}


```
 rotate(angle) 
```

围绕中心旋转图像。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_98}


```
 rotate(angle, resize_proportionally, background_color) 
```

围绕图像中心以指定角度旋转图像，同时保持缩放 <br/>            比例并保留背景颜色。此方法允许 <br/>            精确的图像操作，确保旋转保持视觉平衡 <br/>            并与指定的背景颜色保持一致。它非常适合需要 <br/>            围绕中心精确旋转的任务，例如方向校正 <br/>            或艺术调整。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 角度 | float | 旋转角度（以度为单位）。正值将顺时针旋转。 |
| resize_proportionally | bool | 如果设置为 <c>true</c>，图像尺寸将被更改<br/>            根据旋转矩形（角点）的投影在其他<br/>            情况下，尺寸保持不变，仅<br/>            __internal__ 图像内容被旋转。 |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | 背景颜色。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_99}


```
 rotate_flip(rotate_flip_type) 
```

"RotateFlip" 方法可对图像进行旋转和翻转操作。它 <br/>            提供了多功能的图像方向操作，允许用户 <br/>            根据需求执行旋转和翻转，促进 <br/>            在软件应用中高效的图像处理任务。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | 旋转翻转类型。 |

### Method: save(file_path) {#save_file_path_100}


```
 save(file_path) 
```

将图像保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存图像的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_101}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_102}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_103}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，覆盖文件内容，否则将追加。 |

### Method: save(stream) {#save_stream_104}


```
 save(stream) 
```

保存的数据。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 该流。 |

### Method: save(stream, options_base) {#save_stream_options_base_105}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_106}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_107}


```
 save_argb_32_pixels(rectangle, pixels) 
```

保存 32 位 ARGB 像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 32 位 ARGB 像素数组。 |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_108}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

保存像素。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| 像素 | int[] | 以 32 位整数值表示的 CMYK 像素。 |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_109}


```
 save_cmyk_pixels(rectangle, pixels) 
```

保存像素。<br/>此方法已弃用。请使用更有效的 [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) 方法。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK 像素数组。 |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_110}


```
 save_pixels(rectangle, pixels) 
```

保存像素（特定格式方法）。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | 保存像素的矩形。 |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 32 位 ARGB 像素数组。 |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_111}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_112}


```
 save_to_stream(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_113}


```
 save_to_stream_with_options(stream, options_base) 
```

根据保存选项，将图像的数据保存到指定流中的指定文件格式。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 保存图像数据的流。 |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 保存选项。 |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_115}


```
 save_with_options(file_path, options) 
```

根据保存选项，将对象的数据保存到指定文件位置的指定文件格式中。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| file_path | string | 文件路径。 |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | 选项。 |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_116}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_117}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_118}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，未更改的索引如果在加载时没有对应的调色板条目，可能会导致图像崩溃。 |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_119}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_120}


```
 set_resolution(dpi_x, dpi_y) 
```

为此 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 设置分辨率。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| dpi_x | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的水平分辨率。 |
| dpi_y | float | 以每英寸点数表示的 [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) 的垂直分辨率。 |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_121}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

将整条扫描线写入指定的扫描线索引。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| scan_line_index | int | 扫描线的零基索引。 |
| argb_32_pixels | int[] | 要写入的 32 位 ARGB 颜色数组。 |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_123}


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
### Saving of the JPG image as a TGA image. {#example_215}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import TgaOptions

with Image.load("test.jpg") as image:
	image.save("test.tga"", TgaOptions())
	

```

### Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image. {#example_216}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.fileformats.tga import TgaImage

with as_of(Image.load("test.png"), RasterImage) as image:
	with TgaImage(image) as tgaImage:
		tgaImage.save("test.tga")


```

